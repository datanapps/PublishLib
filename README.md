# PublishLibSample

#### Step 1. Add the JitPack repository to your build file 
This section could be either project root gradle (older project) or setting gradle (new project)

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
#### Step 2. Add the dependency
version : v1.0.0

	dependencies {
	        implementation 'com.github.datanapps:PublishLib:v1.0.0'
	}
