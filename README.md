
</p>

<h1>Formatting A USB Drive Using Powershell In Windows</h1>

<h2>Description<h2>
Project consists of a concise script that allows the user to format their USB drive instantaneously. Though this can be done manually this utility allots for mass conversion of many USB drives. This format script connects many file systems through the usage of Powershell, as it will configure a script formatting the data of any drive, through simple steps.

<h2>Environments and Technologies Used</h2>

- Powershell
- USB Drive


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
  

<h2>High-Level Steps</h2>

- Launch Powershell ISE as Administrator 
- Use formatting script format-volume
- Input drive letter
- Select file system
- Run script and format drive

<h2>Actions and Observations</h2>

![IMG_1446](https://github.com/user-attachments/assets/3637c672-ba4a-4b06-aa29-de3f598ca609)

 Launch Windows Powershell ISE, though it must be run as administrator for this specific formatting to work effectively.

</![IMG_1447](https://github.com/user-attachments/assets/bffbcb21-33a6-4215-8d19-e5ed30963ee3)
Once the system is launched input the script format-volume.
![IMG_1453](https://github.com/user-attachments/assets/b29ad189-b11a-4482-b052-d61391bc7c08)

After format-volume is inputted as a script, the next step would be to implement -Driveletter into the script, and then identifying the specific drive letter of your USB and inputting that into the script.
![IMG_1448](https://github.com/user-attachments/assets/9e297e5e-d5b5-4ffe-a984-fea693da2b0f)

![IMG_1449](https://github.com/user-attachments/assets/588c592e-a9a5-4964-b08c-778eb66b2b69)
After identifying and correctly inputting the drive letter, the next part of the script is to select the file system using -Filesystem
![IMG_1450](https://github.com/user-attachments/assets/bcf40743-e19f-4586-8fdb-4d739ac89bdf)
Lastly, in order to finish the script and ensure an effectively formatted drive using the Powershell application select the file system NTFS

![IMG_1452](https://github.com/user-attachments/assets/d2eb2e20-80f6-49ae-9801-c170a329a159)

Run the system and wait patiently for completion.

![IMG_1451](https://github.com/user-attachments/assets/4f14b6d5-04f4-4b5b-b2ac-6b8edad38ba2)

Once completed ensure that the drive data has been properly formatted by checking the USB in the folder, if empty the script was run successfully and you have properly formatted a USB drive using Powershell.
</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />
