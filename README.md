# Objectives
Resolve ticket #1007 and document the process.
Equipment/Requirements
Computer with internet connection and VirtualBox installed.
The Ticket #1007 VM (Open Virtual Appliance (OVA) file).


Ticket ID #
1007
User Name
Learner01
User’s email
learner01@TechSolutions.com
Priority
Medium
Category
Peripheral
Status
Resolved
Subject
No sound
Asset
capstone120
Assigned to
Gregg Nicholas
Description
Hello,

I am trying to play some Christmas music on YouTube, but I have no sound. There is a red X on the speaker icon on the lower right-hand side of the screen (see image), but the speakers are plugged in.

I can live with this for now, but later, I have some Skype meetings.
Please help.

Thank you,
Learner01


# Tasks
I began troubleshooting by clicking the sound icon in the lower-right system tray and selecting Troubleshoot, but this did not resolve the issue. Next, I opened Device Manager by typing it into the search bar and navigated to the High Definition Audio Device under "Sound, Video, and Game Controllers." Windows indicated that the device was disabled. I enabled the device, which immediately removed the "X" from the sound icon in the taskbar.

To confirm the fix, I logged back into Learner01 and verified that the "X" on the sound icon was no longer present. I tested sound functionality by playing a video on YouTube, and audio output was restored. Case closed.

# Resolution (Internal-Facing):
I began by clicking the sound icon in the lower-right corner of the taskbar and selected "Troubleshoot sound problems," but this didn’t resolve the issue. Next, I opened Device Manager by searching for it in the taskbar. Under Sound, video, and game controllers, I located High Definition Audio Device and noticed that Windows indicated the device was disabled, which explained the red X on the sound icon. I enabled the device, and the red X on the sound icon disappeared immediately.
To confirm that sound functionality was restored, I logged back into Learner01, where the sound icon displayed without the red X, and sound was working properly.
The issue was that the audio device had been disabled, likely due to a setting change or a previous system update. By re-enabling the device in Device Manager, I restored full sound functionality.


# Resolution (Client-facing)
Hello Learner01,
The sound issue has been resolved. The audio device on your computer was disabled, which caused the red X on the sound icon and prevented audio playback. I enabled the device, and you should now have full sound functionality. The red X is gone, and your sound is back to normal for your YouTube and Skype meetings.
Let me know if you need any more assistance!

Best,
Gregg Nicholas
IT Support Specialist

![Identify no sound issue](https://github.com/GreggNicholas/Ticket-1007-No-sound/blob/main/Screen%20Shot%202024-12-01%20at%2023.15.41%20PM.png?raw=true)

![enable audio device](https://github.com/GreggNicholas/Ticket-1007-No-sound/blob/main/Screen%20Shot%202024-12-01%20at%2023.14.40%20PM.png?raw=true)




