haii... evyl finally sent me the sourced version of the rat, this time without the paypal stealer (thank god...)! dont question too much, just go with the source code. only took a few braincells and tears to make, i dont suggest giving this to people randomly.
***use it wisely*** -souk

**What it does:**

- Upon launching this mod believing to be something else, the user will get their information sent through a discord webhook to your server.
- Webhook nuking is very difficult, protected by encryption.
- Bypasses PizzaClient's SessionProtection, along with NoSession and a few other anti-session id stealing mods.
- Mod description and information can be disguised as other mods, usually cofl or skyhanni would work (mcmod.info)
  
**What it takes:**

(Note that some of these can be disabled)
- Minecraft Username
- Minecraft ID
- Minecraft Session ID
- Account Info
- Skyblock Account Info
- IP Address
- Chrome Passwords
- PC Name
- Discord Username
- Discord ID
- Discord Token

**Installation Process:**

- Compile the code yourself or just download the preinstalled version :)
- Use any decent java editor and upload the .jar or source code folder into the editor.
- Go to net -> jodah -> typetools -> Ben.class
- Inside Ben.class, edit each of LDC:"discord/token/here" and replace within the quotations your discord webhook link.
- Exit Ben.class and go to HWIDUtil.class
- Scroll down to the bottom of the class file and then edit the *single* LDC:"discord/token/here" and replace within the quotations your discord webhook link.
- Export and you have your working rat :D

**Discord Webhook Creation:**

- Go to a server that you own (maybe dont use your friends server)
- Server settings -> Apps -> Integrations -> Webhooks -> New Webhook -> Copy Webhook URL
- Paste into LDC:"discord/token/here"

**Notes:**

- Jar openers such as Visual Studio Code are a bit stupid when it comes to class files, as it's basically just java but converted into binary.
- Tools such as [recaf](https://github.com/Col-E/Recaf) allow you to edit the class file without any issues.
- Other tools such as [java decompilier](https://github.com/java-decompiler/jd-gui) or [vineflower](https://github.com/Vineflower/vineflower) might work to assist in vscode, but I haven't used then before.

**Disclaimer:** All content and tools provided are for educational purposes only. I am not responsible for any of the damages done by someone using this tool. Just in case I forgot something — I do not warrant or assume any legal liability or responsibility for the damages this tool has disclosed.

**Much Thanks to:** souwuk and literallysakura on discord. Please dm literallysakura for any troubleshooting issues :)


