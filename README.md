# android.andrew
Modified,tutorial codes on android based on developer.android.com
This projetc is a modified version of the sample media demo at http://developer.android.com/shareables/training/PhotoIntentActivity.zip
by google.
In the original project upon orientation changing the imageview or videoview would just disappear.Most probable reason was the onSavedInstanceState(
) function couldn't put parcable into bundle and every time it went into oncreate method the current image and video path were set to null

This was apparently resolved by saving the imagePath and videoUri instead to the bundle.
I'd slowly add video-player and seperate imageviewer-activity
This is for beginners and tutorials.
