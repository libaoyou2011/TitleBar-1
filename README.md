ScnTitleBar
======================
Customizable Xamarin.Forms title bar for Android, iOS and Windows Phone: place up to 5 buttons inside it and position/paint the bar as you want.

View template in general
===========================================
[back button] [2nd left button] [1st left button] [title] [1st right button] [2nd right button]

Description of control
===========================================
ScnTitleBar constuctor includes three parameters:
- owner page;
- kind of view buttons;
- control alignment (only for renderer not for location on page).
You can situate control in any place on page. For better render control set property

Set bar like you want. Setting up view nessasery buttons, icons for color
Setting up view necessary buttons, icons, back color, title text and style.
Back button have returning logic in box.

How to use this control in Xamarin.Forms app
===========================================
Look sample to know how right include control menu in your application.

If you want to have responsive buttons on tap then need add initialize renderers for each platform.

In iOS project just use
```cs
Xamarin.Forms.Forms.Init ();
BoxViewGestureRenderer.Init();
```
In Android project just use
```cs
Xamarin.Forms.Forms.Init (this, bundle);
BoxViewGestureRenderer.Init();
```
In WinPhone project just use (not finished yet)
```cs
Xamarin.Forms.Forms.Init ();
BoxViewGestureRenderer.Init();
```