# Mobile-Application-Development

# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.
# AIM:
To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

# EQUIPMENTS REQUIRED:
Latest Version Android Studio

# ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

# PROGRAM:
Program to print the text “Hello World”.

Activity_main.xml:

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-

auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">

<TextView
          
    android:layout_width="wrap_content"
          
    android:layout_height="wrap_content"
          
    android:textSize="40dp"
          
    android:text="Hello World!"
          
    app:layout_constraintBottom_toBottomOf="parent"
          
    app:layout_constraintEnd_toEndOf="parent"
          
    app:layout_constraintStart_toStartOf="parent"
          
    app:layout_constraintTop_toTopOf="parent"  />
    
    
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

Developed by: Dhivya Bharathi.K


Registeration Number : 212221220010


# OUTPUT

![Screenshot (211)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/636f2b5c-418e-4764-bf2a-172bdd00e5dd)
![Screenshot (212)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/1a9cdd9b-509d-446c-af17-0fbb1e0c6ae4)
![Screenshot (213)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/d63adee5-df2d-4d39-86e0-f042ebde5905)
![Screenshot (214)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/21915b19-48ee-4336-9f09-4859bfdc4aca)
![Screenshot (215)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/5ad7083d-6a95-4304-946d-e1fb6f37dd0f)
![Screenshot (216)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/4dfde4ea-325f-479f-bf1b-5218ae28c869)
![Screenshot (217)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/26f7da42-1a7d-4968-b64e-3b2df6ec8e78)
![Screenshot (218)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/f097a203-98b1-4992-9182-cba8d6264bcf)
![Screenshot (219)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/1684bdbc-8a37-47e9-b407-904702acd369)
![Screenshot (220)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/e994c234-9280-44f6-ac51-9b7eeac421b1)
![Screenshot (221)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/0344b3f2-1a52-4ff8-a128-8a550831be72)


![Screenshot (222)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/7b1a9b3d-3f97-47f1-84b9-e2b67ff8781a)


![Screenshot (223)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/0e45480c-b027-4e9a-a40d-7106fb2562b2)


![Screenshot (224)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/85152d00-8c69-4d3f-80d2-cfb04fe9a1ad)


![Screenshot (225)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/15ca8e36-71f6-479e-bcf1-9ffb9c9cec26)


![Screenshot (226)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/c22f9c4a-6b5b-4b12-9d14-a470438fd540)


![Screenshot (227)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/c9c8922e-c7d2-4bdd-8816-c781abf494b5)


# RESULT

Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
          
          
          
          
          
          
          
          
