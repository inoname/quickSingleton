# quickSingleton
##快速定义单例的宏
##应用示例

//  SoundTools.h
```
#import <Foundation/Foundation.h>
#import "Singleton.h"
@interface SoundTools : NSObject
singletonInterface(SoundTools)
@end
```
//  SoundTools.m
```
#import "SoundTools.h"
@implementation SoundTools
singletonImplementation(SoundTools)
@end
```
