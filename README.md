# ToasterLibrary
[Android Library] Simple Library to create toast messages

# To use the library - 

## In project level gradle file.

`
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
 ` 
  ## In app level gradle file
  
  `
  dependencies {
	        implementation 'com.github.ho-dor:ToasterLibrary:1.0.1'
	}
  `
  # Create Toast
  
 ` ToasterMessage.toast(Context c, String message) `
