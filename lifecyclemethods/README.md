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

<androidx.constraintlayout.widget.ConstraintLayout

xmlns:android="http://schemas.android.com/apk/res/android" 

xmlns:app="http://schemas.android.com/apk/res-auto"

xmlns:tools="http://schemas.android.com/tools"

android:layout_width="match_parent" android:layout_height="match_parent" 

tools:context=".MainActivity">

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

MainActivity.java:

<androidx.constraintlayout.widget.ConstraintLayout

xmlns:android="http://schemas.android.com/apk/res/android" 

xmlns:app="http://schemas.android.com/apk/res-auto"

xmlns:tools="http://schemas.android.com/tools" 

android:layout_width="match_parent" android:layout_height="match_parent"

tools:context=".MainActivity">

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

MainActivity.java:

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
    
    toast.show();
    
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

}

Developed by: Dhivya Bharathi.K

Registeration Number : 212221220010

## OUTPUT
![Screenshot (211)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/7ef57453-f38b-480b-9a26-547bd71c178f)

![Screenshot (212)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/c928e02d-42dd-4aa1-a449-35b471a08a10)

![Screenshot (213)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/7a94be1d-aa77-4a74-ab99-f5fa7fc4d2e8)

![Screenshot (214)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/cf72c7dd-bc79-49b5-9e84-5eee9e96b179)

![Screenshot (215)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/3ab34a00-e972-4089-a9f3-3bd51cfc3901)

![Screenshot (216)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/7e78fdbc-2c71-4525-8b40-6ab07e2b58c2)

![Screenshot (217)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/34da0940-7265-4b05-8b81-09c01727d3e1)

![Screenshot (218)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/47509bb7-dd08-4e7f-acec-90321df4f4aa)

![Screenshot (219)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/64fd8d0d-5168-4c5d-a765-bacbc6d9f2e0)

![Screenshot (220)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/3ff24806-67b6-4bbd-9fdd-5fdee216d339)

![Screenshot (221)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/d0046865-edc5-4cb7-a904-e7782903d83e)



![Screenshot (222)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/f2995956-d8d6-47c6-93eb-07f6f75b040b)


![Screenshot (223)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/b492a2ec-1ea6-47de-9248-b547ad9dc7d6)


![Screenshot (224)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/caa54164-437d-421f-9cae-b5326d61e2a0)


![Screenshot (225)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/751c0b3f-768c-4c45-b0e7-5228d49c56cb)


![Screenshot (226)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/f07290a3-a148-4f26-916a-78dc3acd7aa7)


![Screenshot (227)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/774b4467-4307-4fcf-bf01-7f292be5a6f4)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
