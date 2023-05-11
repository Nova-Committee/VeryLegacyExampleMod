# Use [VeryLegacyExampleMod-Voldeloom](https://github.com/Nova-Committee/VeryLegacyExampleMod-Voldeloom) instead

# How To install

1.	Download and extract VeryLegacyExampleMod into your project folder:
	https://github.com/Nova-Committee/VeryLegacyExampleMod
	Do NOT also extract a Forge source MDK.
  
2.	Get and install IntelliJ IDEA 2019.3.5, because it supports JDK 7 and 8, and also Gradle 2.6:
	https://www.jetbrains.com/idea/download/other.html
	Get [2019.3.5 - Windows with Bundled JBR 8 (exe)] COMMUNITY edition.
	Community edition does not require a license.
	JBR 8 is JDK 8, as opposed to 11.
  
3.	Get and install some form of JDK 7.

4.	Get a copy of fernflower.jar and place it into C:/Users/${userName}/.gradle/caches/minecraft/
	Apparently, auto-downloading fernflower was actually implemented in ForgeGradle 1.0, but somehow it won't work for 2.6 and make sure you also delete the 		fernflower.jar in the project as well
  
5.	Import the project using JDK 8.

6.	Make sure Settings / Build, Execution, Deployment > Build Tools > Gradle is using JDK 8.

7.	From the IDE's Gradle tab, click Reimport All Gradle Projects.

8.	Switch to JDK 7

9.	From the IDE's Gradle tab, run Tasks > forgegrade > setupDecompWorkspace to install the Forge workspace

10.	To build the project, run Tasks > build > build using JDK 8.

11.     include the .main folder in the project from the "add configurations" menu in order for Minecraft to start up


## Making the mod
This itself is not a modding tutorial, so if you would like to learn 1.6.4 modding, you have to do it yourself, but here are some great tutorials that we recommend in order:

[PersistentPixels](https://www.youtube.com/watch?v=SM9xRAAjUPw&list=PLPuEDzUkbdN660wJhwf2PB_0eAX-oaRMb&index=2)

[EsvDefcon](https://www.youtube.com/playlist?list=PLXS6DF7GdLvImonSLAo8HVSPwwCUhSS4d)

[ScratchForFun](https://www.youtube.com/@ScratchForFun/search?query=1.6.4%20Modding%20Tutorials)

For modeling in 1.6.4, you need Techne, but you can no longer install it now as the servers are down for the installer to work. In order to install it now, you need to go to:https://archive.org/download/techne_editor/techne-fixed.zip

