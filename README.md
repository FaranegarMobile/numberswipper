# numberswipper

<a href="https://imgflip.com/gif/2bwzfc"><img src="https://i.imgflip.com/2bwzfc.gif" title="made at imgflip.com"/></a>

The numberswipper is of those applicable library which you can easily increase and decrease a number by just swipping left and right!

How to add:

1) First, add the jitpack maven to your project level build.gradle.

```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
    }
	}
```
2) Second, add the dependency to your app level build.gradle.

```gradle
dependencies {
	        implementation 'com.github.FaranegarMobile:numberswipper:v1.0'
	}
```

Enjoy it! Or Extend it based on your needs...

Attrs:

```xml
<attr name="snp_min" format="integer"/>
<attr name="snp_max" format="integer"/>
<attr name="snp_value" format="integer"/>
<attr name="snp_arrowColor" format="color"/>
<attr name="snp_backgroundColor" format="color"/>
<attr name="snp_numberColor" format="color"/>
<attr name="snp_intermediate" format="boolean"/>
```

Sample:

```xml

<com.faranegar.number_stepper.CustomSwipeNumberPicker
        android:id="@+id/number_picker"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:textColor="@android:color/white"
        android:textSize="@dimen/font_size"
        app:snp_arrowColor="@android:color/white"
        app:snp_backgroundColor="@color/backgroud_box"
        app:snp_max="1000000"
        app:snp_min="100"
        app:snp_numberColor="@color/black" />
```
