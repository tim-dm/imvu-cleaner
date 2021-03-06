# imvu-cleaner

IMVU Cleaner is a utility for cleaning common IMVU related folders. 

![](https://raw.githubusercontent.com/tim-dm/imvu-cleaner/main/preview.png)


### Features 

- Classic Client Cache Cleaning

      Deletes all of the classic client's cache files

      Over time the classic client can become slow as the cache builds up to several 
      hundred megabytes or a few gigabytes. This can cause it to take longer to load the 
      user's inventory, the shop and other places depending on the user's hardware.
      
- Classic Client Log Cleaning

      Deletes the IMVU log files
      
      Log files can contain sensitive data such as chat history and account information. Over time multiple
      log files are created. Deleting them can protect your privacy and make it easier to find the relevant log files 
      if necessary as they are generated when logging in and when a crash occurs.

- Project Files Cleaning

      Deletes the files and folders in the project files directories
      
      When creating a product in Create Mode or IMVU Studio, the assets for the product get saved in the respective project folder. Assests includes textures,
      animations, poses, meshes, music, etc. 
      
      By Default, the assets get saved to the projects directory located in my documents (on Windows). When a project
      is saved to a different location, remnants can still be left behind in the projects directory. This can cause the projects directory 
      to fill up over time with useless folders if you do a lot of creating.
      
      Before running this option, it is advised to make sure you have backed up or moved your import project files somewhere else. If you store all your
      projects in the default location, do not use this feature.
