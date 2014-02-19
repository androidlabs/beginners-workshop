Lab 2.01
====

Lab 2.01

![Splash Icon](img/splash_icon.png)

```java
package cow.boo;
  
import android.os.Bundle;
import android.app.Activity;
import android.view.Menu;
 
public class SplashActivity extends Activity {
 
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_splash);
    }
     
}
```

<div style="background:#ccffcc 8px 8px no-repeat; border:1px solid #003300; color:#003300; margin:10px 0 5px; padding:5px 5px 5px 30px;">
To help you avoid frequent garbage collections, the Android SDK ships with a very useful tool called allocation tracker. This tool is part of DDMS, which you must have already used for debugging purposes. To start using the allocation tracker, you must first launch the standalone version of DDMS, which can be found in the tools directory of the SDK. The version of DDMS included in the Eclipse plugin does not offer you ability to use the allocation tracker yet. More info on the allocation tracker can be found in this article
</div>

Bla