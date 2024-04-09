# Modrinth App

Modrinth App is an incredibly powerful launcher that makes managing your mods and modded instances much easier. It can do everything the official launcher can do, but allows for much more customization and ease of access. The official launcher has had several issues that have taken weeks to fix or are currently still not fixed, despite their severity. For modded and vanilla users alike, it is recommended to switch to Modrinth Launcher for an issue-less experience.

This guide will explain the install process for Modrinth, as well as how we can use it for SkyClient. Please take the time after setting up to better learn your way around the launcher, as you may end up using it as your go-to launcher from now on!

## How to Install (Windows)

- Despite looking long, this is a very simple process and should only take a few minutes! This guide will also assume you are migrating from SkyClient, but steps will be largely the same, except for the migrating data section.

### Step 1 - Installing Modrinth

[Download Modrinth App](https://modrinth.com/app). It should automatically recommend the correct version to download (a `.msi`). Once it is finished downloading, run it. It may warn you that it is an executable file and could be malicious. Press `OK` and continue the setup process.

### Step 2 - Logging in

After launching, it will then ask you to log into your Microsoft account so that it can log you into your Minecraft account. Follow the on screen instructions. It may then ask you to sign into Modrinth. You are not tied down to one method, you can link multiple accounts later. Modrinth will now guide you through how to use the app, please pay attention!

### Step 3 - Creating an Profile/Instance

This guide will focus on Forge 1.8.9, but steps for other versions should also be obvious.

Click on the green `+` button on the bottom left of the app. Make sure the `Custom` tag is selected. Give it an icon if you wish, any name you want, and set the Loader to `Forge`, and Game version to `1.8.9`. Then press `+ Create`.

### Step 4 - Installing our mods / SkyClient

Now that we've installed Forge 1.8.9, we need to move all our mods to the new Modrinth App folder. To do that, we'll right click our new instance and press `Open folder`. A File Explorer window should open, this is the equivalent of your ".minecraft" for this instance. Now, open a new File Explorer by either pressing `Win + E` on your keyboard or right clicking the file explorer icon and pressing "File Explorer". Navigate to your old .minecraft folder, which is `C:\Users\USER\AppData\Roaming\.minecraft` (change USER to your computer's name, or if you don't know it, press the `Windows` key and `r` at the same time to open up Run, and type `%appdata%` to open your Roaming folder, then open the `.minecraft` folder). Then open the `skyclient` file if you are using SkyClient. Simply move everything in this folder into the Modrinth App ".minecraft" folder that you opened earlier. Once this is done, you should be able to see all your mods in the Content tab, and can launch the profile. The Content tab can be opened by clicking on the instance (not the green start arrow), and clicking Content on the sidebar.

When downloading mods from now on, you can simply drag and drop them into the Mods tab in Prism Launcher. Additionally, if the mod is on Modrinth, you can download them within the launcher using the `Add content` button at the top right of the Content tab.

### Step 5 - Explore

Modrinth Launcher has a lot of things to offer, such as themes if you don't like the look of it, as well as a lot of options for your instances, including the ability to see all your mods, resource packs, and worlds in the launcher before launching. You can use these menus to install mods and resource packs, and even update mods if they are hosted on Modrinth or CurseForge! Please take the time to actually learn how the launcher works and experiment with it! Prism is an incredibly powerful launcher and it's important to know exactly what you can do with it!

## Common Issues

#### `My mods arent showing up in-game!`

There are 2 common causes for this, open the profile view (click on it or right click then `View instance`), then check the Content tab. If you do not see any mods here, [you should redo step 4](#step-5-installing-our-mods-skyclient).

If you see a list of mods here then you should click the `Options` tab, then `Edit versions`, then make sure to choose Forge. Click `Save changes` and Forge should be installed, and the mods should work.

<br>

If you encounter any issues not shown here you should ask for help in my [discord server](https://discord.gg/rejfv9kFJj).

# Contributors