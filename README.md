# Blue Book

## Team Members
- Kevin Diep
- Zongying Mo

## Dependencies
- XCode 11.5
- Swift 4
- pod ‘Firebase/Auth’
- pod ‘Firebase/Core’
- pod ‘Firebase/Firestore’
- pod ‘Firebase/Storage’
- pod ‘FirebaseUI/Storage’
- pod ‘FirebaseFirestoreSwift’
- pod “BSImagePicker”, “\~> 2.8”

## Special Instructions
- Use an iPhone 11 Pro Max simulator, ​[vertical only].
- You have to open the file BlueBook.xcworkspace (as opposed to the file
BlueBook.xcodeprog).
- Before running the app, run "pod install" inside the BlueBook folder where 
the podfile is located.
- New users will have a default “sharedObjects” group that stores objects 
shared by other users.
- The sharing and swipe delete functionalities are disabled in the 
“sharedObjects” group. So shared objects cannot be shared to others.
- If the author of an object shared it with other users and deleted it 
afterwards, others won’t be able to access it.
- When editing/creating/sharing objects, click save before going back otherwise 
changes will not be saved.
- When editing objects, users can add more pictures but can’t delete previous 
pictures.
- Objects must have at least one picture.
- May hit Firebase quota for the app and won’t load anything in this case.

### Test accounts:
- Jane Doe, email: ​123456@utexas.edu password: 123456
- John Doe, email: 654321​@utexas.edu password: 654321

| Feature | Description | Percentage |
| ------- | ----------- | ---------- |
| Login/Sign Up | Allows user to sign up and login | Zongying (100%) | 
| Creating new groups | Creates a new group of favorites | Kevin (100%) | 
| Delete groups | Tap on the bar button “edit” to switch to edit mode to delete groups | Zongying (50%), Kevin (50%) | 
| Settings | Allows user to log out or switch between light and dark mode | Kevin (100%) | 
| List objects | Click on a group to show the list of favorite objects in this group | Zongying (100%) | 
| UI | Colors, buttons, background, and navigation bar | Zongying (70%), Kevin (30%) | 
| Voice recognition | Allows user to speak instead of type the content of the object | Zongying (100%) | 
| Image Picker | Allows user to pick images for their favorite object from their library | Zongying (100%) | 
| Edit Object | Make modifications to a favorite object | Kevin (100%) | 
| Sharing | Allows user to share their favorite object with other users | Zongying (100%) | 
| Adding Object | Allows a user to add a new favorite object | Zongying (75%), Kevin (25%) | 
| Delete Object | Allows a user to swipe delete a favorite object | Zongying (75%), Kevin (25%) | 

