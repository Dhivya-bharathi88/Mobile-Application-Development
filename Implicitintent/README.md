# Ex.No:3 Develop program to create a text field and a button “Navigate”. When you enter “www.google.com” and press navigate button it should open google page using Implicit Intents.


## AIM:

To create a navigate button using Implicit Intent to display the google page using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:



## PROGRAM:

Program to print the text “Implicitintent”.

## Activity_main.xml:

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"

xmlns:app="http://schemas.android.com/apk/res-auto"

xmlns:tools="http://schemas.android.com/tools"

android:layout_width="match_parent"

android:layout_height="match_parent"

tools:context=".MainActivity">

<EditText
          
    android:id="@+id/urlEditText"
          
    android:layout_width="292dp"
          
    android:layout_height="67dp"
          
    android:layout_marginStart="56dp"
          
    android:layout_marginTop="108dp"
          
    android:hint="Enter URL"
          
    app:layout_constraintStart_toStartOf="parent"
          
    app:layout_constraintTop_toTopOf="parent" />

<Button
        
    android:id="@+id/navigateButton"
        
    android:layout_width="wrap_content"
        
    android:layout_height="wrap_content"
        
    android:layout_gravity="center"
        
    android:text="Navigate"
        
    app:layout_constraintBottom_toBottomOf="parent"
        
    app:layout_constraintEnd_toEndOf="parent"
        
    app:layout_constraintStart_toStartOf="parent"
        
    app:layout_constraintTop_toBottomOf="@+id/urlEditText" />
    MainActivity.java:
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;

import android.net.Uri;

import android.os.Bundle;

import android.view.View;

import android.widget.Button;

import android.widget.EditText;

public class MainActivity extends AppCompatActivity { EditText editText; Button button;

@Override

protected void onCreate(Bundle savedInstanceState) {

    super.onCreate(savedInstanceState);
    
    setContentView(R.layout.activity_main);
    
    button = findViewById(R.id.navigateButton);
    
    editText = (EditText) findViewById(R.id.urlEditText);
    
    button.setOnClickListener(new View.OnClickListener() {
    
        @Override
        
        public void onClick(View view) {
        
            String url=editText.getText().toString();
            
            Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse(url));
            
            startActivity(intent);
            
        }
        
    });
}

}

Developed by: Dhivya Bharathi.K
Registeration Number : 212221220010

## OUTPUT
![Screenshot (28)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/ae886b97-5f32-4a06-8953-b3bd17ecd15d)


![Screenshot (29)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/00a3b2b9-bb5c-4b33-acde-21b27d259801)


![Screenshot (30)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/73968ded-f543-48f2-8191-a8bc056388d9)


![Screenshot (31)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/54c17698-e617-4054-b9f8-5299177be1e9)









## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the google page using Android Studio is developed and executed successfully.


