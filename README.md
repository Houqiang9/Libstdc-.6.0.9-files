# Libstdc-.6.0.9-files
该项目用于Xcode 10+ 不支持使用lbstdc++插件报错异常解决方案
`Error: ld: library not found for "-lstdc++.6"`

## Usage
根据调试方式不同，真机和模拟器文件放置路径存在差异，分别复制对应的Lib文件到下面的路径即可解决Xcode编译报错

### for device
put tbd copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/

### for simulator
put dylib copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/

put tdb copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/
