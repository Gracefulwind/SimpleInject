### SimpleInject  

# 用于自定义Annotation的一个简单注入器。由于JCenter上传太慢。。。先新建个工程在JitPack上做测试用。

# 用法：
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  	dependencies {
          ...
	        compile 'com.github.Gracefulwind:SimpleInject:848957b497'
	}
