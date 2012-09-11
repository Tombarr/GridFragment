GridFragment for Android
================
Target API: 7+ (Eclair) with Android Support Library and/ or ActionBarSherlock  
Developer: [Thomas Barrasso](mailto:contact@tombarrasso.com)  

General/ About
-------

This is a clone of Android's [ListFragment](http://developer.android.com/reference/android/app/ListFragment.html)
class but to support the [GridView](http://developer.android.com/reference/android/widget/GridView.html) widget.
It was developed for the PlanGrid client for Android powered devices, but is generalized for use with any application.

The behavior of this class is identical to that of ListFragment, simply extend the class and have a widget of type
GridView somewhere in your layout with an ID of `@android:id/list`. Also, a widget with an ID of `@android:id/empty`
can be displayed for when the GridView is empty and loading, then hidden when it has items.