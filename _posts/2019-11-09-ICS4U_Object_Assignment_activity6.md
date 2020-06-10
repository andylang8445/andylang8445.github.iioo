---
title:  "[ICS4U]Activity 6 for Object Assignment Submission"
date:   2019-11-09 01:05:00
categories:
- School Class
- School_Grade12
- Assignment
- Object
- Computer Science
tags:
- School
- Course
- Computer Science
- Assignment
---
<h1>Objects in JavaFX Activity 6</h1>
JavaFX methods Documentation Page.

<hr>
<br>

<h1>ImageView</h1>
  <h3>Classes</h3>
  - java.lang.Object
  - javafx.scene.Node
  <h3>Interfaces that this class implements</h3>
  - Styleable
  - EventTarget
  <h3>Subclasses</h3>
  - N/A
  <h3>Is this abstract class</h3>
  - It's not an abstract class
  - Constructors
      - <b>ImageView():</b> Allocates a new ImageView object.
      - <b>ImageView(Image image):</b> Allocates a new ImageView object using the given image.
      - <b>ImageView(String url):</b> Allocates a new ImageView object with image loaded from the specified URL.
  <h3>Method overloading</h3>
  - No method overloading
  <h3>Method signature of an accessor (getter) and a mutator (setter)</h3>
  - <b>Mutator:</b> public final void setFitHeight(double value)
      - Sets the value of the property fitHeight.
  - <b>Accessor:</b> public final double getFitHeight()
      - Gets the value of the property fitHeight.
<br>

<h1>Color</h1>
  <h3>Classes</h3>
  - java.lang.Object
  - javafx.scene.paint.Paint
  <h3>Interfaces that this class implements</h3>
  - Interpolatable<Color>
  <h3>Subclasses</h3>
  - N/A
  <h3>Is this abstract class</h3>
  - It's not an abstract class
  - Constructors
     - <b>Color(double red, double green, double blue, double opacity):</b> Creates a new instance of color.
  <h3>Method overloading</h3>
  - <b>static Color rgb(int red, int green, int blue):</b> Creates an opaque sRGB color with the specified RGB values in the range 0-255.
  - <b>static Color rgb(int red, int green, int blue, double opacity):</b> Creates an sRGB color with the specified RGB values in the range 0-255, and a given opacity.
  <h3>Method signature of an accessor (getter) and a mutator (setter)</h3>
  - <b>Mutator:</b> N/A
      - Automatically setted when the color has been chosen
  - <b>Accessor:</b> public double getSaturation()
      - Gets the saturation component of this Color.
<br>


<h1>MouseEvent</h1>
  <h3>Classes</h3>
  - java.lang.Object
  - java.util.EventObject
  - javafx.event.Event
  - javafx.scene.input.InputEvent
  <h3>Interfaces that this class implements</h3>
  - public interface Serializable
  - public interface Cloneable
  <h3>Subclasses</h3>
  - javafx.scene.input.MouseDragEvent
  <h3>Is this abstract class</h3>
  - It's not an abstract class
  - Constructors
     - <b>MouseEvent(EventType<? extends MouseEvent> eventType, double x, double y, double screenX, double screenY, MouseButton button, int clickCount, boolean shiftDown, boolean controlDown, boolean altDown, boolean metaDown, boolean primaryButtonDown, boolean middleButtonDown, boolean secondaryButtonDown, boolean synthesized, boolean popupTrigger, boolean stillSincePress, PickResult pickResult):</b> Constructs new MouseEvent event with null source and target.
     - <b>MouseEvent(Object source, EventTarget target, EventType<? extends MouseEvent> eventType, double x, double y, double screenX, double screenY, MouseButton button, int clickCount, boolean shiftDown, boolean controlDown, boolean altDown, boolean metaDown, boolean primaryButtonDown, boolean middleButtonDown, boolean secondaryButtonDown, boolean synthesized, boolean popupTrigger, boolean stillSincePress, PickResult pickResult): </b>Constructs new MouseEvent event.
  <h3>Method overloading</h3>
  - N/A
  - <b>Mutator:</b> N/A
      - Automatically setted when the mouse event happens
  - <b>Accessor:</b> public EventType<? extends MouseEvent> getEventType()
      - Gets the event type of this event. Objects of the same Event class can have different event types. These event types further specify what kind of event occurred.
  <h3>Method signature of an accessor (getter) and a mutator (setter)</h3>
  - <b>Mutator:</b> public void setDragDetect(boolean dragDetect)
      - Augments drag detection behavior. The value says whether this event will be followed by DRAG_DETECTED event. It has effect only with MOUSE_PRESSED and MOUSE_DRAGGED events.
  - <b>Accessor:</b> public final double getScreenX()
      - Returns absolute horizontal position of the event.
