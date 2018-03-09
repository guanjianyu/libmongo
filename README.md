# libmongo
Unreal Engine ThirdParty Plugins of MongoDB
## Quick Start
* Git clone this package into your project Plugins directory
* Edit your project Build.cs file.

  * add *`"libmongo"`* in *`PublicDependencyModuleNames.AddRange(new string[] { "Core", "CoreUObject", "Engine", "InputCore","libmongo" });`*
  
* Regenerate Visual studio project file.

Then you can easily use mongo c driver by including following head file:
* `#include "mongoc.h"`
* `#include "bson.h"`
