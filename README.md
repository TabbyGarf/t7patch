# READ ME NOW
### This patch does not need to be updated all the time to work. It has not been bypassed; there are no new threats. The repo will be updated if there is ever a need to do so. As of 9/17/2024, the game is still safe to play with a network password. Your antivirus is mistakingly flagging the game; it is a false alarm.

# Black Ops 3 Community Patch
A new and improved community patch for a large list of Black Ops III exploits. 

Please do not try to use any public cheats with this patch. Almost all of them are incompatible.
# Windows Instructions

1. Download [the patch](https://github.com/shiversoftdev/t7patch/releases/tag/Current).
2. Extract the files into a folder of your choice
3. Edit your settings in the t7patch.exe.confing file provided (name, friends only, etc). **You can edit these while the game is running too**.
4. If not playing in matchmaking, set a network password to enable the best protection. Note that anyone who wants to play with you needs to have the same network password. If you want to play in normal matchmaking again, clear the network password.

# Linux/Steamdeck Instructions
1. Download [the linux zip](https://github.com/shiversoftdev/t7patch/releases/tag/Current) and extract the files into your Black Ops 3 installation folder
2. Open steam properties\
![s1](/steam1.png)
3. Change the launch options to match the image below\
![s2](/steam2.png)
4. Change your proton version and enable steam play compatibility\
![s3](/steam3.png)
5. Edit your settings in the t7patch.conf file provided (name, friends only, etc). **You can edit these while the game is running too**.

# Known Incompatibilities
1. Overwolf OBS plugin causes fatal crash in BO3 when patch is loading.

# Frequently Asked Questions

### Q: Does this patch fix the FPS issue?
A: Yes
### Q: Do I need to run the patch if I am playing solo offline?
A: Simple answer, no. Technical answer, maybe. If you are high profile, run it regardless because steam networking is complicated.
### Q: Does this fix the RCE vulnerabilities you mentioned in your video?
A: Yes. This fixes 4 of the known RCE vulnerabilities. Additionally, the BO3 update recently patched RCE.
### Q: Do I need a VPN?
A: If you are high profile or a streamer, yes. Otherwise, not likely. If you are getting hit offline (internet) often, run a VPN.
### Q: Do I need an alternate steam profile? My stats don't transfer over!
A: Steam alts are only recommended for high profile players or streamers. If you are not being attacked, you don't need an alt.
Your stats will not transfer to your new account, and if you wish to retain stats you may need to resort to third party tools.
### Q: Does this patch work on Steam deck? Linux?
A: As of 2.03, yes. Please use the Linux installation instructions. Thanks again to @InvoxiPlayGames for making this possible.
### Q: Does this patch work on Mac?
A: No, however, you can use [BO3MacFix by Emma](https://github.com/InvoxiPlayGames/BO3MacFix) which is fully compatible with network passwords, fixes custom maps, and allows crossplay between Mac and Windows players.
### Q: Can you make this patch compatible with other mod menus, cheats, or third party tools?
A: No. The patch uses a lot of complicated techniques to patch the game that interfere with most third party tools. This is due to the fact that Black Ops III is heavily resistant to patching by non-official sources. Additionally, I consider it a bonus that cheaters must choose to play unprotected to the griefing mechanisms that they have used against the community for so long.
### Q: Does the patch work with custom maps?
A: Yes.
### Q: Will you ever post source code?
A: Most of the source can be found here: https://github.com/shiversoftdev/Black-Ops-3-Projects/tree/main -- ZBR Native is the dll
### Q: Why does my anti-virus say this is malware?
A: Some of the techniques used to patch the game are similar to techniques used by malware, which causes antivirus to be upset.
### Q: What is the LPC file for?
A: The LPC file is to fix the A.B.C error on sign in. Not necessary for most users.
### Q: Is this tool still updated?
A: Yes.
### Q: Are the security concerns still valid?
A: Partially. The RCE vulnerabilities are no longer a concern, but the patch fixes many remote crashes which can be used to grief people.
### Q: Is there a ban risk when using this tool?
A: No.
### Q: Will this affect other games? Can another anticheat ban me for using this on BO3?
A: No.
### Q: What is the network password for?
A: [Please watch this video.](https://www.youtube.com/watch?v=ykoH31p61_E)
### Q: Will this work for Linux? Will this work for Windows 7?
A: Windows 7 and below is not supported. Linux is supported.
### Q: Error at hooking API "LoadStringA"
A: [Install the visual c++ redistributables](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
### Q: I was in a public game and still got crashed!
A: Yes, without the network password you are still vulnerable to certain crashing exploits.


# Credits
Serious - Creator of the patch
# Special Thanks
SyGnUs - Exception handler help\
Emma/IPG - Linux/steamdeck support\
momo5502 - Report of critical RCE method and how it works\
ItsFebiven, Kai, ssno - Testing\
Kenshin9977, Obey, Dawson - Crash Reports\
Snowy. - Crash Report for CL_HandleRelayPacket\
Lerggy, Vortex - Additional information\
Mikey0006 - UI Error report\
Aqua - Name spoofing bug report and friends only bug report\
IceGrenade - Reported Server Browser IP Leaking\
FragsAreUs - Proton and Win7 ntdll binaries
