# Space Ninja

This application was submitted as an assigmnent for my high school computer science class.

The game loop is written in HTML5 and Javascript and is embedded in an Android Studio project.
The HTML5 game and image-assets can be found in the assets folder here: https://github.com/Sr22/space-ninja/tree/master/app/src/main/assets

Space Ninja is a one-player game in which the player controls the ninja, located at the bottom of the screen. The player controls the motion of the ninja by using the right and left arrow keys. The player also controls when and how many bullets the ninja shoots. The bullets are shot by clicking the space bar key. The purpose of the bullets is to fight off the enemies (represented by robot aliens) that fall randomly from the top of the screen to the bottom. When the ninja shoots the enemy, by clicking th space bar key, the enemy is destroyed and in result, disappears. Each time an enemy is shot, the player gains one point, the point count is located in the top left corner of the screen. If the enemy comes in contact with the ninja, it results in game over and the player as the option to restart the game by clicking the button located in the top left corner to the right of the point count. The goal of the game is to prevent the ninja from coming in contact with the enemy and gain as many points as possible. 

![alt tag](https://github.com/Sr22/space-ninja/edit/master/to/gameView.png)

Assets are loaded in Android's main activity java file using the myWebView.loadURL() api call as shown below

       myWebView.loadUrl("file:///android_asset/index.html");

Note that setJavaScriptEnabled must be set to "true" as shown below 

        WebSettings webSettings = myWebView.getSettings();
        webSettings.setJavaScriptEnabled(true);

The main activity file can be found here: https://github.com/Sr22/space-ninja/blob/master/app/src/main/java/sr/hello1/MainActivity.java





