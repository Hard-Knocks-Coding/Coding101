# Hard Knocks -> Coding 101 Lesson 1

---
Tools used in the Lesson
- Visual Studios 2022 | https://learn.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2022
- Visual Studios Code | https://code.visualstudio.com/docs/setup/windows
- Dotnet 6 |  https://dotnet.microsoft.com/en-us/download/dotnet/6.0
---

---
## Used in this lesson
---
- Automatically close console when debugging Tools->Options->Debugging->Automatically Close The Console.
- SemiColons on each new line ;
- Comments //;

### Methods
`Void | Console.WriteLine(String value) `

    Outputs whats sent to it to the console
    ex
        Console.WriteLine("Hello");
    or
        Console.WriteLine(consoleData);

`String | Console.ReadLine()`

    Stops the console from executing , and waits for the enter key to be pressed
    the data from the console can be stored as a string
    ex
        Console.ReadLine();
    or 
        String consoleData = Console.ReadLine();


`Void | Console.Console.Clear()`

    Clears the console of its data, and sets the cursor to the top left.
    ex
        Console.Clear();


### Properties

`String | Console.Title`

    The title of the console
    ex
        String consoleTitle = Console.Title;
    or
        Console.Title = "Hello";



`ConsoleColor | Console.BackgroundColor`

    The background color of the console for any subsequent writes

    ex
        ConsoleColor backgroundColor = Console.BackgroundColor;
    or
        Console.BackgroundColor = ConsoleColor.White;   
    If you want the entire background to be a certain color you must Console.Clear();



`ConsoleColor | Console.ForegroundColor`

    The color of the text in the console for any subsequent writes.

    ex
        Console.ForegroundColor = ConsoleColor.Red;
    or
        ConsoleColor foregroundColor = Console.ForegroundColor;




### Assignment

- Create a console with the title "Banking App"
- Set the background color to white 
- Set the text color to red;
- Ensure all of the console is white
- Have the console say "Hello welcome to the banking app!"
- Make the console waits for the user to press enter to continue;

Answer

``` csharp

//-Create a console with the title "Banking App"
Console.Title = "Banking App";

//- Set the background color to white 
Console.BackgroundColor = ConsoleColor.White;

//- Set the text color to red;
Console.ForegroundColor = ConsoleColor.Red;

//-Ensure all of the console is white
Console.Clear();

//- Have the console say "Hello welcome to the banking app!"
Console.WriteLine("Hello Welcome to the banking App!");

//- Make the console waits for the user to press enter to continue;
Console.ReadLine();



```
