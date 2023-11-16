# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.
## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:
Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.
Step 2: Then type the Application name as HelloWorld and click Next. 
Step 3: Then select the Minimum SDK as shown below and click Next.
Step 4: Then select the Empty Activity and click Next. Finally click Finish.
Step 5: Design layout in activity_main.xml.
Step 6: Display message give in MainActivity file.
Step 7: Save and run the application.

## PROGRAM:
Program to print the text “Hello World”.Developed by: kanimozhi.s Register number: 
212221220024
# Activity_main.xml:
~~~
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">

<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="40dp"
    android:text="Hello World!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
~~~
# MainActivity.java:
~~~
package com.example.myapplication;
import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle; import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStart() {
    super.onStart();
    Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
    toast.show();
}
@Override
protected void onRestart() {
    super.onRestart();
    Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onPause() {
    super.onPause();
    Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
    toast.show();![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/fcd214fc-b2e8-429d-83db-86b8f6d38913)
    
}
protected void onResume() {
    super.onResume();
    Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStop() {
    super.onStop();
    Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onDestroy() {
    super.onDestroy();
    Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
    toast.show();
}
~~~
## OUTPUT
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/2cee1ed2-06ff-4bfb-b19d-7bc6f63c068a)
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/16854fbf-0d16-4f27-bcaa-6d91b6645772)
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/daa65bc3-60f8-48f0-ba96-0132db9c4dfd)
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/9834dd21-07d4-4bc0-9aab-b31c1664efa4)
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/f034100a-07c1-46ad-a09c-e3d4630458c2)
![image](https://github.com/Kani-004/Mobile-Application-Development/assets/129577149/cf282c9c-c4a0-4df3-8c22-6247c7727af6)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.

