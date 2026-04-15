FMOD AUdio Project for [Project Rippit]( https://github.com/Rippit-productions/RippitGame/)

- Using Version **FMOD Studio 2.02.04**
  - ⚠️ Make sure to use the same FMOD version or below. Otherwise your Audio Build files may not be supported when imported into Unity.

Download FMOD Studio : https://www.fmod.com/


# <ins>Setup / Refreshing FMOD Audio</ins>

1. Open the project file
  
   <img width="1030" height="83" alt="image" src="https://github.com/user-attachments/assets/804ef947-d045-46db-bf6c-636ff052db0c" />
   
2. Bulid the project by pressing **F7**
3. Copy the contents of *Build\Main* to *RippitGame\Assets\StreamingAssets\FMODAudio\Main*

- Re-copy files when you want to update changes from FMOD to Unity.
- You can keep Unity open when doing so. The FMOD for Unity Package will recognise the changes and prompt refresh

_____

- ⚠️ You can setup the FMOD App to build to a specific path. Please don't commit these changes on a Shared/Main Branch as the setting will apply to other users
