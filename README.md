# space-ninja

This application was submitted as an assigmnent in my high school computer science class.

The game loop is written in HTML5 and Javascript and is embedded in an Android Studio project.
The HTML5 game and image-assets can be found the assets folder https://github.com/Sr22/space-ninja/tree/master/app/src/main/assets


Assets are loaded in Android's main activity java file using the myWebView.loadURL() api call as shown below

       myWebView.loadUrl("file:///android_asset/index.html");

Note that setJavaScriptEnabled must be set to "true" as shown below 
        WebSettings webSettings = myWebView.getSettings();
        webSettings.setJavaScriptEnabled(true);

The main activity file is located here
        https://github.com/Sr22/space-ninja/blob/master/app/src/main/java/sr/hello1/MainActivity.java





