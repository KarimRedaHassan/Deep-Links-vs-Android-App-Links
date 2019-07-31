# Deep-Links-vs-Android-App-Links
This Tutorial will discuss the difference between Deep Links and Android App Links showing the benefits of using one or both of them. 

### This Tutorial discusses the following:
1. The meaning of Deep Links.
2. The meaning of Android App Links.
3. What are the benefits of using Deep Links.
4. What are the benefits of using Android App Links.
5. Highlight The Major Differences Between Deep Links and Android App Links

### This is a part of Android App Links Series.

# What is Deep Links
It actually means that if you want your app to be accessible from a URL link, may be when a user hit a URL link in a chat app (like whatsapp, messenger, .. etc), then you should implement Deep Links. You could also not just open your app But also send some specific data with the URL to open a specific location in your app with a specific content. For Example, when someone shares his facebook profile link in the messenger, when you hit this URL link, the facebook app will open the profile screen of this user. So in other words, you have extent the functionality of your app to allow sharing a direct link of user profile, may be a user blog or even a certain specific post.

When the user clicks the URL, The Android System will open a dialog box showing all the Apps that could resolve this URL and You will find your app shine between them.

Deep Links also could be used to navigate between different destinations within your app using the Android Jetpack Navigation Component by defining a deep link for the desired destinations within your app and simply call NavController to navigate to this destination by providing the deep link URL.

Deep Link could be considered the primary version of the Android App Links.

# What is Android App Links
As per The Official Android Documentation "Android App Links are HTTP URLs that bring users directly to specific content in your Android app. Android App Links can drive more traffic to your app, help you discover which app content is used most, and make it easier for users to share and find content in an installed app."

https://developer.android.com/studio/write/app-link-indexing

What does this actually means? 

It actually means the same as the Deep Links but with more extra features. Instead of opening disambiguation dialog (as Google Named it) to showing all apps that can resolve this URL, The Android System will directly opens your app without showing any dialog. This is the next level of Deep Links, as you have to verify the ownership of the website domain that is included in the URL through Google Digital Asset Links.

Also Android App Links make your App Content Searchable by Google. "Google can crawl through your app content and present your Android app as a destination to users through Google Search results, when that content corresponds to a web page that you own" Android Documentation.

https://developer.android.com/training/app-indexing/index.html

What this actually means is that when the user search for a certain URL through the Google Search App. If this your is related to your own website that you have verify its ownership. Google will show your app in the search and when the user click the website URL, Google will redirects the User to your app instead of opening the web page. This will happens if the user have your app installed. If not, Google will open the web page.

# Here are the actual benefits from using the Deep Links:
1. Making more than one entry point for your application.
This means you could open your app from places rather than the launch icon

2. Extending the functionality of your app by allowing sharing a specific content over the social media even if you don't have a website :)

3. Improving the User Experience by facilitating a direct access to the content that the user need without the need of opening your app from the launcher icon then browsing to the desired content.

4. Increase the user's engagement with your app as you could allow him to browse the app as if he opens it from the launcher icon.
This means when he press the Up button in the ActionBar/ToolBar, he will go to the normal previous screen as if he opened the app from the normal entry point (launcher icon). You could also prevent this action by allowing the Up button to leave your app and return to the previous app which redirected the user to your app.

5. Facilitate Navigation through the Android Jetpack Navigation Component by giving each destination a calling URL.

5. Allow jumping between different Navigation Graphs easily.

# Here are the actual benefits from using the Android App Links:
1. First, You will benefit from All the points mentioned in the Deep Links' Benefits Section

2. You will ensure a direct opening of your App without the disambiguation dialog.

3. Make sure that your URL will be opened only by your App. (User could change it from the Device Settings)

4. In case of the User doesn't have your app installed, Android System will redirect him to your website.

5. Users could directly open specific content in your app by clicking a URL from Google in a mobile browser, in the Google Search app, in screen search on Android, or even through Google Assistant.

6.You Also Could Benefit from Android Instant App Support allowing users to run your Android app without installing it. (This required more work, But Android App Links works perfectly with this feature).


# What's Next ?

Allow-Other-Apps-to-Start-Your-Activity

https://github.com/KarimRedaHassan/Allow-Other-Apps-to-Start-Your-Activity

# Android App Links Series

Understand-The-URL
- https://github.com/KarimRedaHassan/Understand-The-URL

Deep-Links-vs-Android-App-Links
- https://github.com/KarimRedaHassan/Deep-Links-vs-Android-App-Links

Allow-Other-Apps-to-Start-Your-Activity
- https://github.com/KarimRedaHassan/Allow-Other-Apps-to-Start-Your-Activity

Create-Deep-Links-to-Your-App-Content
- https://github.com/KarimRedaHassan/Create-Deep-Links-to-Your-App-Content

# Additional Resources

https://developer.android.com/studio/write/app-link-indexing

https://developer.android.com/training/app-indexing/index.html

https://developer.android.com/training/app-links/deep-linking

# Also See

#### A Full List Of All My Tutorials

https://github.com/KarimRedaHassan?tab=repositories
