# Mars Photos

This app is part of the [Android Basics in Kotlin] course from Google, see [Unit 4] [Pathway 2] and the [Get data from the internet] Codelab and the [Load and display images from the Internet] Codelab.

Using this stater code you will create MarsPhotos is a demo app that shows actual images of Mars' surface. These images are real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server as a REST web service.

The solution app will demonstrate the use of
[Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and 
[Coil](https://coil-kt.github.io/coil/) to load images by URL.

The app also leverages 
[ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding 
adapters.

----

[Android Basics in Kotlin]: https://developer.android.com/courses/android-basics-kotlin/course
[Unit 4]: https://developer.android.com/courses/android-basics-kotlin/unit-4
[Pathway 2]: https://developer.android.com/courses/pathways/android-basics-kotlin-unit-4-pathway-2
[Get data from the internet]: https://developer.android.com/codelabs/basic-android-kotlin-training-getting-data-internet
[Load and display images from the Internet]: https://developer.android.com/codelabs/basic-android-kotlin-training-internet-images

----

Environment

- Kotlin 1.6.10
- Android Studio Bumblebee 2021.1.1
- Gradle Plugin 7.1.2

----

updated: 2022-03-07