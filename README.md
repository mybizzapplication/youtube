## Android Programming Task

In order to be considered for the Android position, you must complete the following steps. 

*Note: This task should take no longer than one hour at the most.*


### Prerequisites

- Knowledge of Android and Android Studio.
- Knowledge of Java.
- You will need to have [Java](http://www.java.com/en/download/), [Android Studio](http://developer.android.com/sdk/installing/studio.html), and the [Android SDK](http://d.android.com/sdk/index.html) installed.

## Task

1. Fork this repository.
2. Create a *source* folder to contain your code. 
3. In the *source* directory, please create an Android app that accomplishes the following:
	- Get a list of youtube videos grouped into playlists 
http://www.razor-tech.co.il/hiring/youtube-api.json
	- Create a list view that shows each of the 
playlists as 
list items.
	- When a playlist item is tapped, the app should drill down and show each item of the 
selected playlist with it's corresponding thumbnail image.
	- When a video item is tapped, the youtube video should begin playing 
immediately. We would prefer that you do not use a web view for this (use a youtube 
library instead). Advice: Start with web view (or intent) and then move to a customize component.
	- The user should be able to navigate back to the list view after viewing the 
youtube video - and continue from where he left off!!
4. Commit and Push your code to your new repository
5. Send us a pull request, we will review your code and get back to you

## Judging

- Code quality: testability, encapsulation, design patterns (MVP), comments, readable code, clean code, etc.
- UI/UX: This is the place for you to show your creativity.

## Advice and Bonus

- You are encourage to use libraries to help you produce better code.
	- volley/retrofit for rest api.
	- ui list views
	- Just check [Android Arsenal](https://android-arsenal.com/)
- You should use [RecyclerView](http://developer.android.com/training/material/lists-cards.html) for the list.
- MVP is the recommended pattern (but the future is [MVVM](https://developer.android.com/tools/data-binding/guide.html))
- Bonus: inject your dependencies (not required to use an injection library) and add a mock flavor with some lists of your own.

*Note: Cheating or copying code will lead to disqualifying*