# Android and iOS in-app review test

I have made a simple app in order to test and try out the in app review function for Andorid and iOS.

# iOS
- Relatively easy to setup, just add the `StoreReview.requestReview()` to an app feature where you think it's sutiable. A modal will pop up to prompt for a review
![](AppleAppReview.gif)
  
# Android
- Also simple to setup but needs a playstore url on the app.json in addition in on order for the code to work. Here, there is no prompt or UI at all. 
It will immediately go to Google Play Store leaving the app which doesn't make it an in app review at all. Expo doesn't recommend
calling `StoreReview.requestReview()` in a button so this won't be a good workaround.
