#Space Ninja
This game was created for my high school computer science class

The game is located in the following path: Sr22/space-ninja/app/src/main/assets/index.html

This game loop was made using JavaScript and HTML5.

The game is shown using WebView

   WebView myWebView = (WebView) findViewById(R.id.webview);
        myWebView.setWebChromeClient(new WebChromeClient());
        
Note Javascript needs to be set to true.

   WebSettings webSettings = myWebView.getSettings();
        webSettings.setJavaScriptEnabled(true);

Space Ninja is a one player game. The player controls the movement of the ninja (located at the bottom of the screen) and the shooting of the bullets. The ninja can be moved using the left and right keys. Bullets can be shot using the space bar key. The purpose of the shooting is to destroy the enemies, indicated by robot aliens. The enemies fall randomly from the top of the screen to the bottom of the screen. When an enemy is shot, it is destroyed and disappears. Each time an enemy is shot, the player gains a point. The point count is located at the top left of the screen. If the enemy comes in contact with the ninja it results in game over and the player has the option to restart the game, located next to the point count in the top left corner. The goal of the game is to gain as many points as possible by shooting enemies without coming in contact with an enemy. 

