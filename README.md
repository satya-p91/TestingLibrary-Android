# TestingLibrary-Android
Learing how to create library in android and publish it to jitpack.

To add this library add following

in project level gradle file
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
  
  
in app level gradle file

  dependencies {
      implementation 'com.github.satya-p91:TestingLibrary-Android:0.3'
  }


Features :
 function to show Toast
 function to scankbar in Linear and relative layout
 
class : 
  ToastAndScackBar :-
      showToast(context,message)
      showSnackBarForLinearLayout(layout, message)
      showSnackBarForRelativeLayout(layout, message)
