## 1. Research: Project Title

- Keywords:
  - clippath flutter
  - flutter clippath bezier 
  - flutter clippath svg
  - flutter clip path generator online
  - flutter clip path generator
  - flutter clippath container
  - flutter clippath triangle
  - flutter canvas clippath
  - svg to custom paint flutter
  - flutter clip path circle
  - flutter clip path shadow
  - flutter clip path tutorial

[comment]: # (I wanted to choose the video title from the above keyboards Like "Flutter custom ClipPath tutorial", but as I saw your latest videos in the channel for any widget, you selected a simple title name, for example for SizedBox widget you just gave a title name just as "Flutter SizedBox")
- Video Title: Flutter ClipPath 


## 2. Research: Competitors

**Flutter Videos/Articles**

- https://api.flutter.dev/flutter/widgets/ClipPath-class.html
- https://flutteragency.com/clippath-widget/
- https://medium.flutterdevs.com/cliprrect-clippath-in-flutter-4c41abe4e8
- https://blog.yipl.com.np/clipping-your-way-through-designs-flutter-a8a314ef656c
- https://www.educative.io/edpresso/how-to-use-the-clippath-widget-in-flutter
- https://medium.com/@taufansyahrudin9/using-clippath-in-flutter-bfdbd06824f5
- https://prasadsunny1.medium.com/custom-clipping-using-fluttershapemaker-com-and-clippath-in-flutter-953d3fdf54ce
- 32K - https://www.youtube.com/watch?v=yi5s-iGskY0
- 21K - https://www.youtube.com/watch?v=XMuEnyQleFs
- 11k - https://www.youtube.com/watch?v=xv3aXittcLg
- 4.4K - https://www.youtube.com/watch?v=qZ0lKMGprj0
- 23K - https://www.youtube.com/watch?v=LnUhNTUl3Mc&t=41s
- 7.4K - https://www.youtube.com/watch?v=8QdLBQhnHAQ
- 9.5K - https://www.youtube.com/watch?v=IDBTKQKLOYY

**Android/Swift/React Videos**

- 32K - https://www.youtube.com/watch?v=yi5s-iGskY0
- 21K - https://www.youtube.com/watch?v=XMuEnyQleFs
- 11k - https://www.youtube.com/watch?v=xv3aXittcLg
- 4.4K - https://www.youtube.com/watch?v=qZ0lKMGprj0
- 23K - https://www.youtube.com/watch?v=LnUhNTUl3Mc&t=41s
- 7.4K - https://www.youtube.com/watch?v=8QdLBQhnHAQ
- 9.5K - https://www.youtube.com/watch?v=IDBTKQKLOYY

**Great Features**
- A Widget that clips its child using a path and calling a callback on a delegate whenever the widget is to be painted. The callback returns a path and the widget prevents the child from painting outside the path. In this article, we will get into ClipPath Widget in detail.
- The ClipPath Widget has clipper property which takes a CustomClipper to define how it is going to clip its path. Inside the CustomClipper there’s getClip(Size size) method where you can define how you are going to clip the child.
- **lineTo:** Using this method one can cut the widget with a line from the given point . x and y are two destinations points where the line stops.
- **quadraticBeizerTo:** with the help of quadraticBeizer method, you can clip your widget with curves.we can draw a quadratic bezier curve using the control point and endpoint.
- We can create a customClipperPath using [shapeMaker](https://shapemaker.web.app/#/)

**Problems from Video**
- can you give shadow to the custom clip path?
- how to make a custom shadow that will fill the whole shape? I know I can use elevation from draw.Shadow with a Custom Painter but I want a uniform shadow over the whole container
- what was the use of moveTo in your code? I removed it and nothing changed
- please tell me how to know this measurement for creating the customClipperPath ?
- can you please explain 'cubic to' also it would be very helpful
- What's the difference between custom paint and custom clipper, because we can even develop this with custom paint, so why use custom clipper
- Why / When would you return true / false for the 'shouldReclip()' function?
- When the clipping is done, the container area remains the same, but in a phantom, how can I get rid of the invisible space permanently?

**Problems from Flutter StackOverflow**

- https://stackoverflow.com/questions/54071311/why-customclipper-is-not-working-suddenly
- https://stackoverflow.com/questions/70426109/clippath-is-not-showing-in-flutter-with-container-as-child
- https://stackoverflow.com/questions/64545002/adding-a-background-color-to-clippath-not-working
- https://stackoverflow.com/questions/66574967/can-not-position-clippath-properly-in-flutter
- https://stackoverflow.com/questions/70264629/flutter-how-to-position-a-card-with-clippath-in-stack


## 3. Video Structure

**Main Points / Purpose of Lesson**

1. ClipPath is widget that clips its child using a path, then we can create custom shapes and designs for a widget by using the CustomClipper class.
2. Main Points
  - ClipPath widget
  - what are the properties of ClipPath
  - what is clipper?
  - what is CustomClipper<Path>?
  - what is getClip()?
  - what is shouldReclip(), and when it should be return false/true?
  - what is Path?
  - what is lineTo?
  - what is quadraticBezierTo?
3. ClipPath widget is used to create and design custom shapes for it's child widget using CustomClipper class.

**The Structured Main Content**
1. Main Topics
  - ClipPath widget.
  - The Clipper property of ClipPath widget.
  - The customClipper<T> class with its two functions.
  - What is Path, linTo, and quadraticBezierTo.
  - what is shouldReclip(), and when it should be return false/true?
2. How to use ClipPath widget?
  - Wrap the widget which you want to clip it to create/draw a custom shape for it.
  - create and draw a custom clipper using CustomClipper<T> class.
