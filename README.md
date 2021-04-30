# SplashScreen_Covid19
This repo will show you how to make splash screen for covid19 app.


[SplashLayout link](https://github.com/mbganesh/SplashScreen_Covid19/blob/main/activity_splash.xml)

[SplashActivity link](https://github.com/mbganesh/SplashScreen_Covid19/blob/main/SplashActivity.java)

[Dependancy link](https://github.com/mbganesh/SplashScreen_Covid19/blob/main/dependancy)

` LottieAnimationView animationView = findViewById(R.id.lottie_covidId);
        animationView.playAnimation();


        new Handler().postDelayed(new Runnable() {
            @Override
            public void run() {
                startActivity(new Intent(getApplicationContext() , MainActivity.class));
                SplashActivity.this.finish();
            }
        }, 2000);`
        
