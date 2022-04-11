
# Rapport

Jag gjorde en sträng som är appens namn och lade sedan till den i XML-filen. Jag lade till en webview i Den ena XML-filen och länkade en extern och en inter sida som jag har gjort själv som visas i denna webview. Jag satte även på javascript och internet.



```
    <uses-permission android:name="android.permission.INTERNET" />        

        my_webview.loadUrl("https://www.his.se/");
        my_webview.loadUrl("file:///android_asset/index.html");
        my_webview = (WebView) findViewById(R.id.my_webview);

        WebSettings webSettings = my_webview.getSettings();
        webSettings.setJavaScriptEnabled(true);
```


![](his.png)

