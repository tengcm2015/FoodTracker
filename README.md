# FoodTracker
iOS dev tutorial from apple

# Notes
## AppDelegete

The AppDelegate.swift source file has two primary functions:

It defines your AppDelegate class. The app delegate creates the window where your app’s content is drawn and provides a place to respond to state transitions within the app.
It creates the entry point to your app and a run loop that delivers input events to your app. This work is done by the UIApplicationMain attribute (@UIApplicationMain), which appears toward the top of the file.
Using the UIApplicationMain attribute is equivalent to calling the UIApplicationMain function and passing your AppDelegate class’s name as the name of the delegate class. In response, the system creates an application object. The application object is responsible for managing the life cycle of the app. The system also creates an instance of your AppDelegate class, and assigns it to the application object. Finally, the system launches your app.

## Storyboard

A storyboard is a visual representation of the app’s user interface, showing screens of content and the transitions between them. 

## Scene

At this point, the storyboard in your app contains one scene, which represents a screen of content in your app. The arrow that points to the left side of the scene on the canvas is the storyboard entry point, which means that this scene is loaded first when the app starts. 

## Views

The elements that appear in the user interface are known as views. Views display content to the user. Views have a variety of useful built-in behaviors, including displaying themselves onscreen and reacting to user input.

All view objects in iOS are of type UIView or one of its subclasses. (e.g. UITextField)
