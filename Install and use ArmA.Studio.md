This Page will guide you through all steps needed to Install and use ArmA.Studio

> NOTE: Screenshots from german OS, Menu names may be different on your computer

## Install

1. Download the executable from [www.x39.io](https://x39.io/projects?project=ArmA.Studio)
2. Install it as you would install every other .exe

## Use

1. When first launching ArmA.Studio you will be promoted to select a Workspace

   > The Workspace is used to store general Information about the Projects inside, it does not need to be at the same location as the actual code

   You can choose between selecting a new Workspace from your Drive **[1]** or a previously used one **[2]** (not on first launch)

   ![Workspace Selector](https://raw.githubusercontent.com/wiki/ArmA-Studio/ArmA.Studio/images/workspace.png)

2. Open the Solution Explorer

   ![Solution Explorer](https://raw.githubusercontent.com/wiki/ArmA-Studio/ArmA.Studio/images/explorer.png)

3. Right click in the Explorer Panel and choose between creating a new Project **[1]** or opening an existing one from anywhere on your Computer **[2]**

   ![Project](https://raw.githubusercontent.com/wiki/ArmA-Studio/ArmA.Studio/images/project.png)

4. Now you can open and edit files inside your Projects just as you do in most other editors



## Using the Debugger

> These are just basics instructions on how to use the Debugger, a full Tutorial needs to be made at some point

1. Download the Arma 3 Debug Engine for [64 Bit](https://ci.appveyor.com/api/projects/dedmen/armadebugengine/artifacts/BIDebugEngine/x64/Release/BIDebugEngine.dll?job=Platform:%20x64&branch=master latest x64) or [32 Bit](https://ci.appveyor.com/api/projects/dedmen/armadebugengine/artifacts/BIDebugEngine/Release/BIDebugEngine.dll?job=Platform:%20X86&branch=master latest x86) (depending on your OS)

2. Place it in your Arma 3 directory

3. For best results use the [Arma 3 Profiling build](https://forums.bistudio.com/forums/topic/160288-arma-3-stable-server-168-performance-binary-feedback/)

4. Start your Game, make sure Battleye is disabled, as it will block the `BIDebugEngine.dll`

5. Start the Debugger by pressing Start

   ![Debugger Start](https://raw.githubusercontent.com/wiki/ArmA-Studio/ArmA.Studio/images/debugger.png))

6. Run the Script you set a Breakpoint for and use the different Panels to see Variables, Call stack, ...




For more information on how to use the Debugger see [this Video](https://www.youtube.com/watch?v=R4Q79bpeA10)
