
<?xml version="1.0" encoding="utf-8"?>

<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
            xmlns:tools="http://schemas.android.com/tools"
            android:layout_width="match_parent"
            android:layout_height="match_parent"

            tools:context=".MainActivity">


<ImageView
        android:id="@+id/thiccauraskin"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:scaleType="centerCrop"
                android:src="@drawable/thiccauraskin" />


                '

<TextView
        android:id="@+id/HappyBirthday_textview"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Come Boogie Down "
                android:textSize="75sp" />

<TextView
    android:id="@+id/from_textview"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="At My House This Weekend"
            android:layout_alignParentBottom="true"
            android:layout_alignParentRight="true"
            android:textSize="75sp" />
</RelativeLayout>