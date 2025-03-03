# Changelog since 1.7.2
- ♻️ Adjusted the folder mappings to new structure 
- Merge pull request #6 from Poeschl-HomeAssistant-Addons/containerfile-dependency/openssh-client-default

⬆️ Update openssh-client-default to version 9.3_p2-r3 
- Merge pull request #5 from MB901/feature-bidirectional-sync

✨ bidirectional sync 
- ⬆️ Update openssh-client-default to version 9.3_p2-r3 
- 'config' folder has been replaced by 'homeassistant_config' and delete write access to prevent erasing 
- Lists should be surrounded by blank lines 
- use match to ensure only push or pull 
- remove old remote_folder 
- Create local directories if they don't exist 
- Add bidirectional sync support with push/pull directions 
- switch source/destination to local/remote 
