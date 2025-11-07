# my coding digital notebook

## Table of Contents
- [Flutter Notes](#flutter-notes)
  - [What is Flutter?](#what-is-flutter)
  - [Key Terms and Definitions](#key-terms-and-definitions)
  - [Layout and Desin Widgets](#layout-and-design-widgets)
  - [Definitions with Structures](#flutter-definitions)
- [Code Definitions](#code-definitions)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## Flutter Definitions
| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
| Main function| A function that runs when your app starts. It tells Flutter what app to show.| void main() => runApp(MyApp());| Turning on a TV to display a show.| main() starts and runs your app.|
| MaterialApp| Sets up your whole app’s look and navigation.| MaterialApp(...)| The foundation and style guide of a house.  | Sets theme, home screen, routes.|
| Scaffold| Gives basic layout: background, nav bar, floating button, etc.| Scaffold(...)| A blank canvas with a frame.| Adds AppBar, body, floating button.|
| Column| Displays content top to bottom.| Column(...)| A vertical list of items on a shelf.| Stack text and images vertically.|
| Row| Displays widgets side-by-side.| Row(...)| A line of books on a shelf.| Place buttons or icons in a line.|u
| Container| A box that can hold other widgets, style, padding, size.| Container(...)| A decorative gift box.| Add margin, padding, color.|
| Text| Displays text on screen.| Text('Hello')| A label on a product.| Show titles, labels, descriptions.|
| Image.network| Loads and shows an image from the internet.| Image.network('https://...')| Viewing a photo from a website.| Load an image from a URL|
| ElevatedButton| A clickable button with elevation.| ElevatedButton(onPressed: ..., child: ...)| A doorbell you press to get action.| Navigate to another screen.|
| onPressed| The code that runs when a button is tapped.| onPressed: () => doSomething()| Clicking a switch to turn on a light.| Button triggers a function.|
| StatelessWidget| A widget that never changes.| class HomeScreen extends StatelessWidget| A poster that never changes.| Static home page or about screen.|
| StatefulWidget| A widget that can change over time.| class MyWidget extends StatefulWidget| A digital clock that updates time.| Interactive form or counter.|
| Navigator.pushNamed| Navigate to another screen using route names.| Navigator.pushNamed(context, '/about')| Turning to a different chapter in a book.| Tap button → go to About screen.|
| Padding| Adds space around a widget.| Padding(padding: EdgeInsets.all(8.0), child: ...)| Cushion inside a box.| Add spacing around a Text widget.|
| Center| Centers content on screen or in a container.| Center(child: ...)| A painting placed in the center of a wall.| Center logo or title.|
| Wrap| Automatically wraps widgets to next line if needed.| Wrap(children: [...])| Word wrapping in a text editor.| Display tags or chips responsively.|
| @override| Marks that you're overriding a method from parent class.| @override| Changing the recipe of a traditional dish.| Override build() in widget class.|
| build() function| Describes what UI to show in a widget.| Widget build(BuildContext context) {...}| Blueprint showing what to construct.| Creates the visual part of the widget.|
| build| The method used in widgets to return UI layout.| build| An architect's design plan.| Defines widget layout.|
| BuildContext context| Helps the widget know where it is in the widget tree.| BuildContext context| GPS in a car—it tells location.| Used for navigation or theme access|
| super.key| Passes the key value to the parent constructor.| super.key| Giving a master key to someone for entry.| Passed in constructors for widgets|
| const| Declares a value that never changes.| const| A permanent signboard.| Optimizes performance for static widgets.|

## Code Definitions
| Term        | Definition | Base Structure / Syntax | Real Life Example | App Example |
|-------------|------------|--------------------------|-------------------|-------------|
| Variable| A named container used to store a value that may change. | `var x = 5;` | A labeled jar you can refill. | Storing user input like `age` or `name`. |
| Constant| A fixed value that cannot change once set. | `const PI = 3.14;` | A sign carved in stone. | Storing a fixed API key or math constant. |
| Data type| The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | Different types of boxes for different items. | Choosing `bool` for login state, `String` for name. |
| String| A sequence of characters used to represent words or text. | `"Hello World"` | A message on a note. | Displaying welcome messages. |
| Integer| Whole number values. | `int age = 16;` | Counting apples. | Showing how many likes a post has. |
| Double| Number values with decimals. | `double age = 16.2;` | Measuring height or temperature. | Showing rating like 4.5 stars. |
| Boolean| A value that can be true or false. | `bool isLoggedIn = false;` | A light switch (on/off). | Tracking if a user is signed in. |
| List| A collection of values in a specific order. | `List<String> names = [];` | A shopping list. | Displaying a list of contacts. |
| Null| A special value that means “nothing.” | `String? name = null;` | An empty jar with no label. | When user hasn’t filled in their profile yet. |
| Function| A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | A coffee machine making coffee. | Running logic when a button is clicked. |
| Parameter| The information passed into a function to change how it works. | `greet(String name)` | Choosing coffee strength when ordering. | Passing username to personalize greeting. |
| Return| The result a function gives back. | `return total;` | Getting change from a cashier. | Returning calculated price in a cart. |
| Scope| Where a variable or function can be used. | *(Concept — not specific code)* | Toolbox that’s only available in one room. | Local variables inside a function. |
| Class| Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | A recipe for making cakes. | Defining a `User` class in an app. |
| Object| A specific version of a class. | `Dog myDog = Dog();` | A cake made from the recipe. | Creating a `User` with name and email. |
| Property| A variable that belongs to a class/object. | `String name;` | Features of a car: color, model. | `user.email` in your app. |
| Method| A function that belongs to a class. | `void bark() {}` | A car starting when you turn the key. | `user.logout()` function. |
| Constructor| A special function used to set up a class when it’s created. | `Dog(this.name);` | Assembling furniture when it arrives. | `User(this.name, this.email)` sets initial values. |
| Abstraction| Hiding the inner workings of code so users only interact with what they need. | *(Concept — not specific code)* | Driving a car without knowing how the engine works. | Using Flutter widgets without seeing source code. |
| Override| Changing how a built-in or inherited function behaves. | `@override` | Rewriting the rules of a game. | Customizing the `toString()` method in a class. |
| Void| A function that does not return a value. | `void printMessage() {}` | Turning on a light — no output, just action. | Showing a toast message with no return. |
## Flutter Notes


|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
| Overloaded method/function or constructure | Uses the same name, but has different parameters | Pizza(), Pizza(String toppings | 2 constructures, firs is a default cheese pizza, 2nd has 1 topping |  |
| dot notation | Methods are called on objects using a dot after the object name | object.method(value); |  |  |
| Concatenate | To combine Strings with other Strings and/or variables| String greeting = "Hello" + "My name is ". ";|||

### String Notes
  Strings have indices (plural for index,) wich start at 0. "Hello" has indices 0(H), 1(e), 2(1), 3(11), 4(0).

### What is Flutter?
- Definition:A framework made by google for building apps that work on web android and ios with one codebase
- Why is it useful?

---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |Basic building block of a flutter app. everythinh is a widget|Text, Button, Column, Row, etc.|
| MaterialApp      |the root of the app. Sets up routes and themes    |MaterialApp(home: MyHomePage())|
| Scaffold         |Provides basic virtual layout-like a header, body, floating button|Commonly used to structure a screen|
| StatelessWidget  |a widget that doesnt change                       |Good for static UI, like labels or icons|
| StatefulWidget   |a widget that can change over time                |Good for counters, forms, animations|
| Navigator        |manage screen transitions                         |Navigator.push(context, MaterialPageRoute(...))|
| AppBar           |top navigation bar                                |Contains title, actions, back button|
| Column           |verticle layout                                   |Column(children: [...])|
| Row              |horizontal leyout                                 |Row(children: [...])|
| Container        |wraps content with padding, margin, or color      |Similar to a div in HTML|
| Image.network    |displays images from a URL                        |Image.network('https://example.com/image.png')|

---

### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?





## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice
🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print
💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

- Variables
- Loops
- Conditionals
✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

- [x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning
➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.
📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |
🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>
📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.
🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
