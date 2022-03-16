# <img src="https://cdn.discordapp.com/attachments/751304558453719176/936194213199093810/rsz_1rsz_1apple_logo_greysvg.png" alt="Apple Logo" width="20" height="24"> iOS Guide for Fortnite

Hey, I've been asked a bit about this "how to install this, how to use this, what do I do?" so I decided to make a quick yet clear and effective guide for you, so you can understand how to get Fortnite working on iOS.

![Example of Fortnite Season 3 working with a .pak console by Galaxify](https://cdn.discordapp.com/attachments/952386927984775209/953746877654917170/main.png)

## Part 0 - Before you start

Before we start, I'll answer some questions you might ask before doing this.

**Do I need to have my iPhone jailbreaked?**
- Yes and no. For some stuff, you don't need it, but if you wanna use stuff such as LawinServer, you will definitely need it.

**What version of iOS does my iPhone have to run?**
- Any that supported Fortnite.

**What iPhone do I need?**
- You will need a iPhone 6s and higher.
- Not supported: iPhone 5s, 6, 6+ (Plus), iPad Air, Mini 2, 3, iPod Touch 6th gen and lower.

**Is this safe?**
- No.... just kidding, of course it is :D

**Should I do this on my main Epic Games account?**
- Honestly, I've done it on my main multiple times and nothing happened, so I'm **pretty sure** you can just use your main account on this (if you don't feel save just make a new, throwaway account).

**Does this come with all skins, emotes, backblings etc?**
- If you connect via LawinServer **(method will be available below)**, you got all of it.
- If you connect via Epic Games Servers, you get the ones you had on the account you logged into.



## Part 1 - Choose your build
Well you know, to begin you have to choose one of the builds listed on my archive [here.](https://github.com/Crunnie/FNiOS-Archive)

You can see what season you are getting right **here.**
![Season Example](https://media.discordapp.net/attachments/952386927984775209/953748401504264273/unknown.png)

For testing purposes, I will download Fortnite+Release-3.5-CL-3994867.
![Downloading the Example](https://cdn.discordapp.com/attachments/952386927984775209/953747885948805240/unknown.png)

A new window should pop up, showing you a blue **Download** button.
Just click on it and continue.
![Big Blue Download Button :3](https://media.discordapp.net/attachments/952386927984775209/953748731499515924/unknown.png)

Great! The selected build should now pop up in your browser, for me it looks like **this.**
![Example of Downloading on Chrome](https://cdn.discordapp.com/attachments/952386927984775209/953748774524702820/unknown.png)

After downloading move the file anywhere, for testing purposes I've moved it to my desktop, and put it in a folder called **'Fortnite iOS Archive Guide'.**
![Folder Example](https://cdn.discordapp.com/attachments/952386927984775209/953749387723550740/unknown.png)

## Part 2 - "Patching" the IPA file

I've heard this part isn't needed in some cases, but since this is a **Beginner-Friendly** tutorial I will include it.

> .IPA Files are basically just .ZIP files, so you can easily extract it via [7-zip ](https://www.7-zip.org/) or [Winrar](https://www.win-rar.com/). 
> Since I use 7-Zip, I will showcase it using 7-Zip.

You can either extract the package, or edit in it. I'll show you the way of editing in it.

Simply just open it to start.
![Opening our IPA File](https://cdn.discordapp.com/attachments/952386927984775209/953757267180785674/unknown.png)

Opening the archive, this window should pop-up.
![7-Zip Archive IPA Window](https://cdn.discordapp.com/attachments/952386927984775209/953757904220078110/unknown.png)

The file that we will need to edit is called 'ue4commandline.txt', which is located in 
**\YourFortniteVersion.ipa\Payload\FortniteClient.app\ue4commandline.txt**
 
To access that file we have to go 2 folders deep, first clicking Payload and then FortniteClient.app
![FortniteClient.app Folder](https://cdn.discordapp.com/attachments/952386927984775209/953758605008592946/unknown.png)

We will end up here, from here we just need to open ue4commandline.txt
![ue4commandline.txt](https://cdn.discordapp.com/attachments/952386927984775209/953758733941497876/unknown.png)

Inside this .txt file, there should be something like this:\
![Insides of ue4commandline.txt](https://cdn.discordapp.com/attachments/952386927984775209/953758913822588998/unknown.png)

We need to add one simple argument behind the .uproject text.
Add **--skippatchcheck** behind the .uproject text.
![Added an argument to the commandline .txt file](https://cdn.discordapp.com/attachments/952386927984775209/953759414320504862/unknown.png)

> Context:
> -skippatchcheck turns off the update check, meaning it won't bother you with "New Fortnite Update on App Store!" + it will let us launch the app just normally without weird methods.


After that simply save the file and you are done patching the IPA file.

![Saving our "patch"](https://cdn.discordapp.com/attachments/952386927984775209/953759712468426812/unknown.png)

7-Zip will simply ask us if we want to modify the file, just click **OK.**
![Saving our "patch": Part II](https://cdn.discordapp.com/attachments/952386927984775209/953759851979374592/unknown.png)

And we are done! Close out of 7-Zip and we can continue installing Fortnite on iOS.

## Step 3 - Installing the IPA file on our iPhone

This step is really easy, it might sound hard but it simply isn't.
For this part you will need additional software ([Sideloadly](https://sideloadly.io/)).

> Remember to plug in your iPhone to your PC.

Click on the **blue** link above and download Sideloadly.
![Sideloadly Downloading](https://cdn.discordapp.com/attachments/952386927984775209/953760442528985168/unknown.png)

Open the setup and install it wherever you want to.
![Sideloadly Installation](https://cdn.discordapp.com/attachments/952386927984775209/953761076711940136/unknown.png)

After it's finished, this window will pop-up.
![Sideloadly App](https://cdn.discordapp.com/attachments/952386927984775209/953761876695744583/unknown.png)

Click on the big **IPA** button on the left and select your modified IPA file.![IPA Selection](https://cdn.discordapp.com/attachments/952386927984775209/953762204795170976/unknown.png)

Your Sideloadly app will look like this.
![Sideloadly App: Part II](https://cdn.discordapp.com/attachments/952386927984775209/953762472576303175/unknown.png)

Before we install Fortnite, we need to link our Apple ID account to Sideloadly.

Simply put your Apple ID email (you can make a new one just for this).
![Sideloadly App: Part III](https://cdn.discordapp.com/attachments/952386927984775209/953762712842801212/unknown.png)

After adding your Apple ID account, you can simply click Start.

Sideloadly will do a lot of stuff in the background, but this bar will update you on what it's currently doing.
![Progress Bar](https://cdn.discordapp.com/attachments/952386927984775209/953763088686006312/unknown.png)

Sideloadly will ask you for your password, just put it in and login.
![Logging into Sideloadly](https://cdn.discordapp.com/attachments/952386927984775209/953763362246897724/unknown.png)

A notification will be sent towards your iPhone, just put the code in Sideloadly and click **OK.**
![Apple ID Auth](https://cdn.discordapp.com/attachments/952386927984775209/953763827051266048/unknown.png)

You can also leave the field **empty** if you want to get a phone-number code instead.

After inputting the code, Sideloadly will do it's job and install the app for you.

> Note, you can use this for other apps too, if you want to :p

Sideloadly will say **Done.** whenever it finished the installing.
![Sideloadly Finish](https://cdn.discordapp.com/attachments/952386927984775209/953764404716011551/unknown.png)

You can now switch over to your iPhone device.

You successfully installed Fortnite on your phone!![Fortnite Success](https://cdn.discordapp.com/attachments/952386927984775209/953765134537474138/unknown.png)


## Step 4 - Launching Fortnite & downloading missing files

Launching the game is as simple as on other apps, since we already patched out the update check.
Just click on it and it will show you this:
![Fortnite Epic Games](https://cdn.discordapp.com/attachments/952386927984775209/953766533744705566/Default-IPhoneX-Landscape.png)

Wait a bit...

After some time the screen will change to this:
![Installation](https://cdn.discordapp.com/attachments/952386927984775209/953766046836346990/IMG_0493.png)

Since we only installed the 'Fortnite Launcher' we need to download other required files.
The amount of time this will take to download depends on your internet connection.

After the download is complete, this will pop-up.
![Fortnite Loading Screen](https://cdn.discordapp.com/attachments/952386927984775209/953766959210721350/IMG_0494.png)

When that happens, close the app completely.
Relaunch the app, wait for the blue screen to pop-up and turn off your Wi-Fi.

 **Why do I need to turn off Wi-Fi?**
- This is required due to Fortnite checking if the version matches with their latest one.
- Sometimes even **-skippatchcheck** in the IPA file won't help, so that's all we can do to fix it.

When you hit this screen, you can turn your Wi-Fi back on.
![Fortnite Tap To Start](https://cdn.discordapp.com/attachments/952386927984775209/953767587592941568/IMG_0495.png)

## Step 5 - Logging into Epic Games Servers

You might think it will be simple to login into Epic Games Servers.
Sadly, it's not as simple as logging in, but it requires a simple work-around.

You will **have to** login via Google.
For some reason logging via Google lets you login into the servers with no issues.

Here's a quick video showing how easy it is to use Google and launch into Fortnite.

> Note: This image is a redirect link to YouTube, no other way of playing videos on Github :(


[![iOS Fortnite Google Login Showcase](https://media.discordapp.net/attachments/952386927984775209/953767587592941568/IMG_0495.png?width=1440&height=665)](https://www.youtube.com/watch?v=LsE2i0sqwfs "iOS Fortnite Google Login Showcase")

## Step 6 - Work in Progress

I will add more stuff, such as Console .PAK, LawinServer and stuff like that later.

I'm currently trying to do something else, I've already spent a shit ton of time doing this.
Hope it helps though, since that's why I did it!

Love you!
**Made with love by Crunnie**  😘
