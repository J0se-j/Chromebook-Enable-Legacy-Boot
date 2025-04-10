# Chromebook Enable Legacy Boot
So, to Legacy Boot, you need to enter dev mode(__This will remove your data. Please back import files!__). So, you would need to press the power, refresh, and escape buttons simultaneously. You will see one of these screens. Don't be alarmed. __DO NOT PLUG IN A USB DRIVE!__

![download](https://github.com/user-attachments/assets/fd118d69-ac8f-43cc-9def-bee67558ffa0)
![download](https://github.com/user-attachments/assets/5df5410e-4593-40f7-a837-ebfcea9b6d31)


Press Ctrl + D once until you see this screen.

![download](https://github.com/user-attachments/assets/2931ce3a-a751-4e0f-9dc3-6fd64bd7c281)


Press Ctrl + D once again. You will see  this screen.

![images](https://github.com/user-attachments/assets/2e0fa362-ecb2-46b2-8da4-f355f059bc79)

Wait a while until you are at the login screen. __Every time you restart your Chromebook, you will have to press Ctrl + D__

![images](https://github.com/user-attachments/assets/cb588d04-aa97-41e6-b0fe-8fba6e1cccda)

Press Ctrl-Alt-(F2/Right arrow/Refresh.) You will see this screen.

Type in "chronos" __If__ there is a password, type in something random __IT WILL SAY IT's WRONG!__ Type in "root" the password is "test0000" then type in "chromeos-setdevpasswd" Leave it blank or type in your own. (__If you type your own, it will be blank for security purposes.__) Type in "exit," then log in as "chronos" Type in the password. If you left it blank before, leave it blank now.
Now type in ("__sudo crossystem dev_boot_usb=1 dev_boot_altfw=1__") Now to return press  Ctrl + Alt + F1 (Left Arror) Now, log into your Chromebook.
Now, Ctrl + L will work now!
