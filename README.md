# 3SC Android Task

### Getting Started
 - Fork this task repository
 - Clone your repository
 - Install Android Studio 2.3 or newer
 - Push your commits to the forked repository

### Task

You will be building a simple playlist manager

Below is a basic specification on what is required for this task

- The application should provide a simple UI interface displaying a list of playlists created by the user.
- The application should make use of new APIs such as `RecyclerView`
- The user should be able to create new playlists (stored locally).
- The user may add and remove tracks from each playlist (stored locally).
- Provide details on how you can improve the app in the future (see bottom of this document)

Each playlist should store the following properties:

 - Name
 - Creation Date/Time
 - Genre
 - Tracks []

Each track should store the following:

 - Artist
 - Title
 - Preview URL

When populating a playlist, the application should allow the user to search track names using the [Spotify Web API](https://developer.spotify.com/web-api/). When selected, the track properties should be populated from the response data, before being saved to the playlist.

Example search: https://api.spotify.com/v1/search?&type=track&q=never%20gonna%20give%20you%20up

Data persistence is required (e.g. local storage) how you store the data is up to you

**NOTE:**
 - You may use any additional third-party Android dependencies.
 - You may use any resources at your disposal for guidance, please add any URLs to the NOTES.md file.

### Feedback

In the **NOTES.md** file, please provide feedback on your experience with the task. For example, any problems you encountered or solved.

You must provide self feedback on the work you have done on how you can improve and iterate on for future
