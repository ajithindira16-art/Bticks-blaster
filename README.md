public class GameView extends SurfaceView implements Runnable {
    // Ball x,y,vx,vy | Paddle x | Brick[][] array
    Thread gameThread; Paint paint;
    @Override public boolean onTouchEvent(MotionEvent event) {
        paddleX = event.getX(); return true;
    }
}# Bticks-blaster
This  gives  so  fun.
