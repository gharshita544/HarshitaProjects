package com.example.sony.benchmarkprj;

import android.animation.ObjectAnimator;
import android.app.Activity;
import android.content.Intent;
import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.util.Log;
import android.view.Menu;
import android.view.View;
import android.widget.AdapterView;
import android.widget.GridView;
import android.widget.ImageView;

import java.util.ArrayList;
import java.util.List;


/**
 * Created by SONY on 10/17/2015.
 */
public class MyGridTest extends AppCompatActivity {
    GridView gridview;
  /*  public int[] mThumbIds = {
            R.drawable.calculator, R.drawable.lol,
            R.drawable.benchmark };*/
    //List<String> titles= new ArrayList<String>() ;

    @Override
    public void onCreate(Bundle SavedInstatnceState) {
        super.onCreate(SavedInstatnceState);
        setContentView(R.layout.grid_test);
       /* titles.add("Calculator");
        titles.add("Felight Jokes");
        titles.add("Benchmark");*/

        gridview = (GridView) findViewById(R.id.gridview);
        gridview.setAdapter(new ImageAdapter(this));





       /*ImageAdapter img = new ImageAdapter();
        img.getView();*/
        gridview.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            @Override
            public void onItemClick(AdapterView<?> parent, View v,
                                    int position, long id) {
                Log.i("Siri", "" + position);
                // Sending image id to FullScreenActivity
                switch (position) {

                    case 0:
                        Intent i = new Intent(MyGridTest.this, CalculatorActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        ObjectAnimator objectAnimator = ObjectAnimator.ofFloat(CalculatorActivity.class,"rotation",0,360,0,360);
                        objectAnimator.setDuration(5000);
                        objectAnimator.start();
                        startActivity(i);
                        break;
                    case 1:
                        Intent i1 = new Intent(MyGridTest.this, FelightJokes.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i1);
                        break;
                    case 2:
                        Intent i2 = new Intent(MyGridTest.this, NavigateActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i2);
                        break;
                    case 3:
                        Intent i3 = new Intent(MyGridTest.this, NewsActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i3);
                        break;
                    case 4:
                        Intent i4 = new Intent(MyGridTest.this, SplashScreenActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i4);
                        break;
                    case 5:
                        Intent i5 = new Intent(MyGridTest.this, AddressActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i5);
                        break;
                    case 6:
                        Intent i6 = new Intent(MyGridTest.this, MenuActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i6);
                        break;
                    case 7:
                        Intent i7 = new Intent(MyGridTest.this, SMSSenderActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i7);
                        break;
                    case 8:
                        Intent i8 = new Intent(MyGridTest.this, cameraActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i8);
                        break;
                    case 9:
                        Intent i9 = new Intent(MyGridTest.this, MusicActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i9);
                        break;
                    case 10:
                        Intent i10 = new Intent(MyGridTest.this, GreetUser.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i10);
                        break;
                    case 11:
                        Intent i11 = new Intent(MyGridTest.this, VedioPlayer.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i11);
                        break;
                    case 12:
                        Intent i12 = new Intent(MyGridTest.this, SensorListActivity.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i12);
                        break;
                    case 13:
                        Intent i13 = new Intent(MyGridTest.this, MapsActivity1.class);
                        // passing array index
                        // i.putExtra("id", position);
                        startActivity(i13);
                        break;
                }
            }
        });

    }



}
