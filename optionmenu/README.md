# Ex.No:10 To create a option menu to display menu items.


## AIM:

To create a option menu to display menu items using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as optionmenu and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout using UI components in activity_main.xml.

Step 6: Display the calculator operation in MainActivity file.

Step 7: Save and run the application.


## PROGRAM:

Program to print the text “optionmenu”.

## Activity_main.xml:

<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"

xmlns:tools="http://schemas.android.com/tools"
          
android:layout_width="match_parent"
          
android:layout_height="match_parent"
          
android:orientation="vertical"
          
android:padding="16dp"
          
tools:context=".MainActivity">

<TextView
          
    android:id="@+id/messageTextView"
          
    android:layout_width="match_parent"
          
    android:layout_height="wrap_content"
          
    android:text="Select an option from the menu"
          
    android:textSize="25dp" />
  
## MainActivity.java:
  
package com.example.optionmenu;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

import android.view.Menu;

import android.view.MenuItem;

import android.widget.TextView;

import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

private TextView messageTextView;

@Override
  
protected void onCreate(Bundle savedInstanceState) {

    super.onCreate(savedInstanceState);
  
    setContentView(R.layout.activity_main);

    messageTextView = findViewById(R.id.messageTextView);
  
}

@Override
  
public boolean onCreateOptionsMenu(Menu menu) {

    getMenuInflater().inflate(R.menu.options_menu, menu);
  
    return true;
  
}

@Override
  
public boolean onOptionsItemSelected(MenuItem item) {
  
    int itemId = item.getItemId();
  

    switch (itemId) {
  
        case R.id.menu_item_1:
  
            messageTextView.setText("Option 1 selected");
  
            return true;
  
        case R.id.menu_item_2:
  
            messageTextView.setText("Option 2 selected");
  
            return true;
  
        case R.id.menu_item_3:
  
            messageTextView.setText("Option 3 selected");
  
            return true;
  
        default:
  
            return super.onOptionsItemSelected(item);
  
    }
  
}
  
}

Option_View.xml:
  
<item
      
    android:id="@+id/menu_item_1"
      
    android:title="Option 1"
      
    android:textSize="25dp"/>
  
<item
      
    android:id="@+id/menu_item_2"
      
    android:title="Option 2"
      
    android:textSize="25dp"/>
  
<item
      
    android:id="@+id/menu_item_3"
      
    android:title="Option 3"
      
    android:textSize="25dp"/>
  
Developed by: DHIVYA BHARATHI.K

Registeration Number : 212221220010

## OUTPUT
![Screenshot (261)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/8e908688-4c73-410c-ae91-6aed6c99de00)
          
          
![Screenshot (262)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/74fe9f76-642c-4e02-8c93-aceae487459e)
          
          
![Screenshot (264)](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/e47aa851-1d28-4406-b684-a503756dc463)
          
          
![ex10 1](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/3cc8bab5-0684-4869-8375-0aa683af86a0)
          
          
![ex10 2](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/5aa01490-9283-43e8-a08b-4746b32a5579)
          
          
![ex10 3](https://github.com/Dhivya-bharathi88/Mobile-Application-Development/assets/128019999/5e1bfddb-4b8c-4be0-969f-afa658f2cef3)





## RESULT
Thus a Simple Android Application to create a option menu to display menu items using Android Studio is developed and executed successfully.


