# Demo Swift Hello World

<img src="README.png" alt="Hello World" style="width: 100%;"/>

This demonstration shows:

  * The [Swift 3](http://swift.org) programming language with
    [Apple](http://apple.com)
    [iOS 10 ](http://www.apple.com/ios/) and
    [Xcode 8](https://developer.apple.com/xcode/)

  * How to create a view that shows "Hello World" on the screen.

Your can get the project by cloning this repo.

Or if you prefer to learn how to create the project yourself, then this README explains how to do it.


## How to create the project

1. Launch Xcode. 

1. Choose "File" → "New" → "Project". 

1. You see the dialog "Choose a template for your new project".

  * Choose the "iOS" radio button.

  * Choose the "Single View Application" icon.

  * Click the button "Next".

1. You see the dialog "Choose options for your new project".

  * For "Product Name", type "Demo Swift Hello World".

  * For "Organization Name", type your own, typical a company name, team name, or similiar. For example, "My Example Company Name".

  * For "Organization Identifier", type your own, typically a reverse-domain-name. For example, "com.example".

  * Click the button "Next".

1. You see the file chooser.

  * Choose where to save your project.

  * Click the button "Create".

1. If Xcode prompts you to choose a development team, then do it.


## How to create the label

1. Open the view.

  * In the left Xcode column, click the icon "Main.storyboard".

  * In the next Xcode column, click the icon "View Controller Scene", then "View Controller", then "View".

  * In the central Xcode column, you see the "View Controller" layout area.

1. Add a label.

  * In the lower-right Xcode area, scroll until you see the "Label" item.

  * Drag-and-drop the "Label" item to the middle of the View Controller layout area.

  * Edit the label text to say "Hello World".

## How to center the label

1. Center the label by adding constraints.

  * Control-click-press the label and drag right, which triggers a popup menu; choose "Center Vertically in Container"

  * Control-click-press the label and drag down, which triggers a popup menu; choose "Center Horizontally in Container"

1. Refresh the view by resetting the constraints.

  * In the central Xcode column, in the lower right area, click the icon that is a triangle between two vertical lines, which triggers a popup menu; choose "Reset to Suggested Contraints".

  * The text field resets to its constraints, which make it the correct size, and center it in the view.


## Tracking

* Package: demo_swift_hello_world
* Version: 2.0.0
* Created: 2016-04-09
* Updated: 2016-09-18
* License: BSD, GPL, MIT
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
