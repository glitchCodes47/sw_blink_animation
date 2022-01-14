# sw_blink_animation

Animation anim1 =new AlphaAnimation(0.0f,1.0f); 

anim1.setDuration(1000);

anim1.setStartOffset(100);

anim1.setRepeatMode(Animation.REVERSE);

anim1.setRepeatCount(Animation.INFINITE);

textview2.startAnimation(anim1);
