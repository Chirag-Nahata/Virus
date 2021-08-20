# Virus

## How to Create a Fake Virus to Prank Someone (Harmless)

To make a fake virus that looks real you need to write some codes in VBS which is easy to write. It does not require knowledge of any such scripting language. You can create some pop-ups with some text written on them.

Easily add some buttons to make it look more real. You can make this virus prank on any Windows computer whether it is Windows 7, 8.1, or Windows 10.

![image](https://user-images.githubusercontent.com/63905783/130200407-2abe71e0-b864-4de1-8fe2-4d97f3d69b16.png)

This kind of Prank Virus is easy to create with notepad and a few lines of simple code. Follow these steps-

### Step 1. Writing Sample Code

1. Open Notepad or Notepad++.

Here is the code to generate a message box on a windows computer.

#### X=MsgBox(“Message Description”,0+16,”Title”)

Type the above code in Notepad and save this notepad on your desktop, Give it some convincing name like “My Computer” and Save the file as .vbs  extension, and select all files instead of *txt.  Like My Computer.vbs

![image](https://user-images.githubusercontent.com/63905783/130200505-7b09b4aa-28db-47f4-abd7-364486b122f8.png)

### Step 2. Understanding the Code

Now open the saved file and you will a message box as shown in the image below.

![image](https://user-images.githubusercontent.com/63905783/130200547-c8e782cf-dcda-4735-a797-29db5a470210.png)

In above Code  X=MsgBox(“Message Description”,0+16,”Title”)  here is the explanation of this code.

Message Description  – This is what you want to show as a Message.

Button – Type of button, like OK, Yes, No, Cancel, etc

Icon – Type of icon you want to show like Info icon, critical icon, etc

Title – Title of message Box.

1. You can write any number from 1,2,3 or 4 instead of 0 (before the ‘+’ symbol)
Here is the meaning of these numbers:

0 = OK Button,

1 = OK / Cancel Button,

2 = Abort / Retry / Ignore Button,

3 = Yes / No / Cancel Button,

4 = Yes / No Button,

5 = Retry / Cancel Button

2. You can write 32 or 48 or 64 instead of 16.
Here is the meaning of each number:
16 = Critical Icon,
32 = Help Icon,
48 = Warning Icon,
64 = Information Icon,

Type the above code with your message, desired button, icon, and title, one line of code generates one message box so you need to write code in a separate line to generate another message box like

X=MsgBox(“Error while opening Computer. Do you want to Fix this Error?”,4+64,”Computer”)
X=MsgBox(“Unable to Fix this Error. Do you want to scan this Computer”,3+48,”Computer”)

It will look like the below image –

![image](https://user-images.githubusercontent.com/63905783/130200666-e243a377-deb8-496a-a008-883bd4e20f1b.png)

Type convening message with proper buttons, relative icons, and title, and save this notepad on your desktop but don’t forget to assign .vbs extension and select all files instead of *txt while saving this notepad. When you save it you will get an icon that looks like 

![image](https://user-images.githubusercontent.com/63905783/130200702-0dbe93a6-15cd-477b-bd95-4cabc80570ce.png) 

## Step 3. Changing the Icon Of Harmless Virus

You need to change the icon of this file so that victim is intended to open the file. You can change this icon to a Computer icon to make it looks original, but you can’t directly change the icon, follow this step to change the icon.

Copy and paste the file to another location like in C drive.
Create Shortcut – right-click on it and send it to desktop.
On the desktop you will get the shortcut, Right-click on it go to properties and click on the Change icon Now select the computer icon and hit OK.

### Watch This Video Tutorial to Create Prank Virus

https://www.youtube.com/watch?v=ZdV6wKo5o1A

If you face any trouble or want the similar prank Virus with exact messages as shown in the above video then you can download this file on your computer, copy and paste the code in Notepad and save it as Computer.vbs

### Download Prank Virus
[Download](https://github.com/Chirag-Nahata/Virus/blob/main/code.txt)

Just download the file on your computer and create a shortcut of it on your desktop and change its icon. You may get an error while downloading the above file that it is a Malicious file which is not at all, download it anyway.

#### OR

Download the text file and save it as .vbs extension, Like My Computer.vbs Select all files while Saving, create a shortcut, and change the icon. You can also change this icon to Chrome, Firefox, MS Office, or any other shortcuts on your desktop.

#### Thank You

Source: https://www.itechfever.com/create-prank-virus/
