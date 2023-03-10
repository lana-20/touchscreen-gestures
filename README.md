# <img src="https://user-images.githubusercontent.com/70295997/212565923-db53bece-1d70-44fd-ad7b-75f247f34450.png" width=40> Touchscreen Gestures

<img src="https://user-images.githubusercontent.com/70295997/213343882-96357417-dfc2-4616-a593-f64127db7767.png" width=400>


Smartphones have relied heavily on gestures since the advent of multi-touch displays. When viewing photos, we no longer consider why we pinch and zoom, or why we pull down to refresh Twitter. As we interact with the content on our screens, we expect certain things to happen. There are more gestures than just the basic ones. The mobile ecosystem is filled with a variety of interactions, some of which are obvious, and some of which are hidden.

Gestures are the new clicks. Gesture-driven devices changed the way we think about interaction. Providing a tactile response through touch feedback in the user interface improves user experience. To enhance the app's perceived speed, it is important to incorporate touch feedback on all touchable elements. The success of mobile applications depends on how well the gestures are implemented in the user experience. 

<img src="https://user-images.githubusercontent.com/70295997/212523014-3cf87fe0-6ffb-4d5b-9c74-a4abf720f8a4.png" width=800>

To ensure accurate and user-friendly interactions, [touch-based GUI controls](https://github.com/lana-20/mobile-app-ui-components#readme) must be large enough to accommodate fingertip actions without small targets that may lead to frustration. What is the appropriate size for these controls?

Customers use fingers to interact with app UI. Per [MIT Touch Lab study](http://touchlab.mit.edu/publications/2003_009.pdf), the average human finger pad is 10-14mm (38-53px) and the average fingertip is 8-10mm (30-38px).

Touch targets include the area that responds to user input. Touch targets extend beyond the visual bounds of an element: An element like an icon may appear to be 24x24dp (4.5x4.5mm) but the padding surrounding it comprises the full 48x48dp (9x9mm) touch target.

Apple, for example, recommends a minimum target size of 44x44px (11.6x11.6mm) for iPhones.
Google recommends a minimum target size of 48x48dp (9x9mm).

Touch targets can be larger than 9mm (34px) if: the UI element is frequently touched; the result of a touch error is severe or really frustrating; the UI element is located toward edge of the screen or difficult to hit; or when the UI element is part of a sequential task ??? like using the dial pad.

![image](https://user-images.githubusercontent.com/70295997/212525051-7c615248-c716-49b9-9266-f3cbcab92cff.png)

<img width="478" alt="image" src="https://user-images.githubusercontent.com/70295997/213852678-91b549af-e5e2-43bd-b8c3-c3088b7c4dcb.png">

The below image explains how the element (range slider) location can be calculated.

![image](https://user-images.githubusercontent.com/70295997/212524140-3edce64e-00d1-4292-94f8-42c3f61e4eac.png)
![image](https://user-images.githubusercontent.com/70295997/212524185-2a783fad-b08c-43ac-aed8-a877ce6021e0.png)

----

[Touch Targets on Touchscreens](https://www.nngroup.com/articles/touch-target-size/)

[Touch Gesture Reference Guide](https://github.com/lana-20/touchscreen-gestures/blob/main/TouchGestureGuide.pdf)

[Touch Target Sizes](https://www.lukew.com/ff/entry.asp?1085)

[Google Touch target size](https://support.google.com/accessibility/android/answer/7101858?hl=en)

[Apple Touchscreen Gestures](https://developer.apple.com/design/human-interface-guidelines/inputs/touchscreen-gestures/)

[40+ Android gestures](https://www.androidauthority.com/android-gestures-3077957/)

[Android Gestures](https://developer.android.com/develop/ui/views/touch-and-input/gestures)

[Android Accessibility Scanner for manual testing](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor)

[How to Automate Gesture Testing with Appium](https://applitools.com/blog/how-to-automate-gesture-testing-appium/)

[Improve Mobile Test Automation With Appium](https://www.perfecto.io/webinars/uncovering-unknowns-appium-and-beyond)

[Swiping your way through Appium](https://youtu.be/oAJ7jwMNFVU)
