## UE4打包流程说明
版本：4.25

### Code Plugin
1. 关闭Editor
2. 打开IDE
3. Build 插件工程
4. 打开Editor
5. 打开插件窗口
6. 点击Package


### Game
打包配置，Window -> Project Launcher

Project: AnyProject



Do you wish to build?: Build

Build Configuration: Shipping

Build UAT: false

Additional Command Line Parameters:



How would you like to cook the content?: By the book

Cooked Platforms: 勾上需要的平台（WindowsNoEditor）

Cooked Cultures: en

Cooked Maps: 勾上需要的地图，至少选择一个

Create a release version of the game for distribution: true

Name of the new release to create.: 1.0

Release version this is based on.:

Generate patch: false

Build DLC: false

Name of the DLC to build.:

Include engine content: false

Iterative cooking: Only cook content modified from previous cook: false

Stage base release pak files: false

Compress content: true

Add a new patch tier: false

Save packages without versions: true

Num cookers to spawn: 0

Store all content in a single file(UnrealPak): true

Encrypt ini files(only with use pak file): false

Generate Chunks: false

Don't include editor content in the build: false

Create Http Chunk install data: false

Http Chunk Install Data Path:

Http Chunk Install Release Name:

Cooker build configuration: Shipping

Additional Cooker Options:



How would you like to package the build?: Package & store locally

Local Directory Path:

Is this build for distribution to the public: false

Include an installer for prerequisites of packaged games: false

Use container files for optimized loading(I/O Store): false



Do you wish to archive?: false



How would you like to deploy the build?: Do not deploy

### DLC
Project: AnyProject



Do you wish to build?: Do not build

Build Configuration: Shipping

Build UAT: false

Additional Command Line Parameters:



How would you like to cook the content?: By the book

Cooked Platforms: 勾上需要的平台（WindowsNoEditor）

Cooked Cultures: en

Cooked Maps: 一般不选地图

Create a release version of the game for distribution: false

Name of the new release to create.:

Release version this is based on.: 1.0

Generate patch: false

Build DLC: true

Name of the DLC to build.: 填插件的名字

Include engine content: true

Iterative cooking: Only cook content modified from previous cook: false

Stage base release pak files: true

Compress content: true

Add a new patch tier: false

Save packages without versions: true

Num cookers to spawn: 0

Store all content in a single file(UnrealPak): true

Encrypt ini files(only with use pak file): false

Generate Chunks: false

Don't include editor content in the build: false

Create Http Chunk install data: false

Http Chunk Install Data Path:

Http Chunk Install Release Name:

Cooker build configuration: Shipping

Additional Cooker Options:



How would you like to package the build?: Do not package



Do you wish to archive?: false



How would you like to deploy the build?: Do not deploy
