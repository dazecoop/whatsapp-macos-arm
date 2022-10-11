# WhatsApp for MacOS Arm/M1 machines

<img width="524" alt="image" src="https://user-images.githubusercontent.com/4234732/195083454-ecc4497d-c9f8-4b08-81f6-49b8ac2c447f.png">

This is a step-by-step that seemed to work for me (dated October 2022).

Tried to add the application I generated directly here, but file limit in Github prevents this.

## Install steps

1. `npm install -g nativefier` (see https://github.com/nativefier/nativefier)
2. Move `icon.icns` into your user directory
3. Move `site.css` into your user directory
3. Within your user directory, run `nativefier 'web.whatsapp.com' --inject site.css --title-bar-style 'hiddenInset' --icon icon.icns --name WhatsApp`
4. Open generated folder and move **WhatsApp** application to your **Applications** folder
5. Open it
6. Open **Activity Monitor**, right-click on columns and ensure **Kind** is selected
7. Search for WhatsApp to double check **Kind=Apple**. If yes, this is a Universal App ✅
