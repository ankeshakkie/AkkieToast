Introduction to a Toast
Users have to do only
Add it in your root build.gradle at the end of repositories:
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Add the dependency
  dependencies {
	        implementation 'com.github.ankeshakkie:AkkieToast:Tag'
	}
  
  Example: ToasterMessage.s(Context,String)
        
