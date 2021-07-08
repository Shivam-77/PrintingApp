# PrintingApp
FirstAndroidApp
This is My First Android App using JAVA .
In this app, Hello!!, How are you?? will print .
I am happy to  share it in my github account.
Here is my java code....

package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
    Button b1;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        b1=(Button)findViewById(R.id.button2);
        b1.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Toast.makeText(MainActivity.this, "Hello!! , How are you??", Toast.LENGTH_SHORT).show();
            }
        });
    }
}
