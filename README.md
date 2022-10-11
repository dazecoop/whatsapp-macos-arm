# WhatsApp for MacOS Arm/M1 machines

<img width="524" alt="image" src="https://user-images.githubusercontent.com/4234732/195083454-ecc4497d-c9f8-4b08-81f6-49b8ac2c447f.png">

This is a step-by-step that seemed to work for me (dated October 2022).

Tried to add the application I generated directly here, but file limit in Github prevents this.

## Steps

1. `npm install -g nativefier` (see https://github.com/nativefier/nativefier)
2. `nativefier 'web.whatsapp.com'`
3. Open generated folder and move **WhatsApp Web** application to your **Applications** folder
4. Open it
5. Open **Activity Monitor**, right-click on columns and ensure **Kind** is selected
6. Search for WhatsApp to double check **Kind=Apple**. If yes, this is a Universal App ✅

