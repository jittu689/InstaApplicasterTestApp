# InstaTestApp

Referred Instagram Development API document to work on this test application. I used my personal Instagram account to register and get the access token. So the posts and profile details that you see are mine. 

1) Used ‘https://api.instagram.com/v1/media/search' API to get the list of posts from my Instagram account. I hardcoded the location and access token in the app to have it working. Otherwise to get the current location and search for the posts in that location, we can use LocationManager class and LocationListener. 

2) To get the comments and commented user details, I used https://api.instagram.com/v1/media/{mediaId}/comments API. How many ever times I tried giving all the correct details, this endpoint always returns empty response. So, I could just show the count of comments and not the detailed information. 

Below are the 3rd party libraries I used:
1) Retrofit - For network calls
2) Butterknife - For View injection
3) Picasso - For loading the images
4) GSON - For parsing

Code can be downloaded and opened in Android Studio to test. 