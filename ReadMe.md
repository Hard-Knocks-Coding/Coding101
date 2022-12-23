# Console.cs 

---
## Used in this lesson
---

### Methods
`public static Int32 Read()`


         Int32 ret = Console.Read()

`public static Void WriteLine(String value) `


         Console.WriteLine(value)


`public static Void Write(String value) `


         Console.Write(value)


`public static Void Beep()`


         Console.Beep()


`public static Void Beep(Int32 frequency,Int32 duration) `


         Console.Beep(frequency,duration)


### Properties

`public static String Title`


         String ret = Console.Title()

`public static ConsoleColor BackgroundColor`


         ConsoleColor ret = Console.BackgroundColor()

`public static ConsoleColor ForegroundColor`


         ConsoleColor ret = Console.ForegroundColor()


---
## Others
---


### Methods

`public static Void Beep()`


         Console.Beep()


`public static Void Beep(Int32 frequency,Int32 duration) `


         Console.Beep(frequency,duration)


`public static Void Clear()`


         Console.Clear()


`public static ValueTuple`2 GetCursorPosition()`


         ValueTuple`2 ret = Console.GetCursorPosition()


`public static Void MoveBufferArea(Int32 sourceLeft,Int32 sourceTop,Int32 sourceWidth,Int32 sourceHeight,Int32 targetLeft,Int32 targetTop) `


         Console.MoveBufferArea(sourceLeft,sourceTop,sourceWidth,sourceHeight,targetLeft,targetTop)


`public static Void MoveBufferArea(Int32 sourceLeft,Int32 sourceTop,Int32 sourceWidth,Int32 sourceHeight,Int32 targetLeft,Int32 targetTop,Char sourceChar,ConsoleColor sourceForeColor,ConsoleColor sourceBackColor) `


         Console.MoveBufferArea(sourceLeft,sourceTop,sourceWidth,sourceHeight,targetLeft,targetTop,sourceChar,sourceForeColor,sourceBackColor)


`public static Stream OpenStandardError()`


         Stream ret = Console.OpenStandardError()


`public static Stream OpenStandardError(Int32 bufferSize) `


         Stream ret = Console.OpenStandardError(bufferSize)


`public static Stream OpenStandardInput()`


         Stream ret = Console.OpenStandardInput()


`public static Stream OpenStandardInput(Int32 bufferSize) `


         Stream ret = Console.OpenStandardInput(bufferSize)


`public static Stream OpenStandardOutput()`


         Stream ret = Console.OpenStandardOutput()


`public static Stream OpenStandardOutput(Int32 bufferSize) `


         Stream ret = Console.OpenStandardOutput(bufferSize)


`public static Int32 Read()`


         Int32 ret = Console.Read()


`public static ConsoleKeyInfo ReadKey()`


         ConsoleKeyInfo ret = Console.ReadKey()


`public static ConsoleKeyInfo ReadKey(Boolean intercept) `


         ConsoleKeyInfo ret = Console.ReadKey(intercept)


`public static String ReadLine()`


         String ret = Console.ReadLine()


`public static Void ResetColor()`


         Console.ResetColor()


`public static Void SetBufferSize(Int32 width,Int32 height) `


         Console.SetBufferSize(width,height)


`public static Void SetCursorPosition(Int32 left,Int32 top) `


         Console.SetCursorPosition(left,top)


`public static Void SetError(TextWriter newError) `


         Console.SetError(newError)


`public static Void SetIn(TextReader newIn) `


         Console.SetIn(newIn)


`public static Void SetOut(TextWriter newOut) `


         Console.SetOut(newOut)


`public static Void SetWindowPosition(Int32 left,Int32 top) `


         Console.SetWindowPosition(left,top)


`public static Void SetWindowSize(Int32 width,Int32 height) `


         Console.SetWindowSize(width,height)


`public static Void Write(String format,Object arg0) `


         Console.Write(format,arg0)


`public static Void Write(String format,Object arg0,Object arg1) `


         Console.Write(format,arg0,arg1)


`public static Void Write(String format,Object arg0,Object arg1,Object arg2) `


         Console.Write(format,arg0,arg1,arg2)


`public static Void Write(String format,Object[] arg) `


         Console.Write(format,arg)


`public static Void Write(Boolean value) `


         Console.Write(value)


`public static Void Write(Char value) `


         Console.Write(value)


`public static Void Write(Char[] buffer) `


         Console.Write(buffer)


`public static Void Write(Char[] buffer,Int32 index,Int32 count) `


         Console.Write(buffer,index,count)


`public static Void Write(Double value) `


         Console.Write(value)


`public static Void Write(Decimal value) `


         Console.Write(value)


`public static Void Write(Single value) `


         Console.Write(value)


`public static Void Write(Int32 value) `


         Console.Write(value)


`public static Void Write(UInt32 value) `


         Console.Write(value)


`public static Void Write(Int64 value) `


         Console.Write(value)


`public static Void Write(UInt64 value) `


         Console.Write(value)


`public static Void Write(Object value) `


         Console.Write(value)


`public static Void Write(String value) `


         Console.Write(value)


`public static Void WriteLine()`


         Console.WriteLine()


`public static Void WriteLine(Boolean value) `


         Console.WriteLine(value)


`public static Void WriteLine(Char value) `


         Console.WriteLine(value)


`public static Void WriteLine(Char[] buffer) `


         Console.WriteLine(buffer)


`public static Void WriteLine(Char[] buffer,Int32 index,Int32 count) `


         Console.WriteLine(buffer,index,count)


`public static Void WriteLine(Decimal value) `


         Console.WriteLine(value)


`public static Void WriteLine(Double value) `


         Console.WriteLine(value)


`public static Void WriteLine(Single value) `


         Console.WriteLine(value)


`public static Void WriteLine(Int32 value) `


         Console.WriteLine(value)


`public static Void WriteLine(UInt32 value) `


         Console.WriteLine(value)


`public static Void WriteLine(Int64 value) `


         Console.WriteLine(value)


`public static Void WriteLine(UInt64 value) `


         Console.WriteLine(value)


`public static Void WriteLine(Object value) `


         Console.WriteLine(value)


`public static Void WriteLine(String value) `


         Console.WriteLine(value)


`public static Void WriteLine(String format,Object arg0) `


         Console.WriteLine(format,arg0)


`public static Void WriteLine(String format,Object arg0,Object arg1) `


         Console.WriteLine(format,arg0,arg1)


`public static Void WriteLine(String format,Object arg0,Object arg1,Object arg2) `


         Console.WriteLine(format,arg0,arg1,arg2)


`public static Void WriteLine(String format,Object[] arg) `


         Console.WriteLine(format,arg)



# Properties

`public static ConsoleColor BackgroundColor`


         ConsoleColor ret = Console.BackgroundColor()


`public static Int32 BufferHeight`


         Int32 ret = Console.BufferHeight()


`public static Int32 BufferWidth`


         Int32 ret = Console.BufferWidth()


`public static Boolean CapsLock`


         Boolean ret = Console.CapsLock()


`public static Int32 CursorLeft`


         Int32 ret = Console.CursorLeft()


`public static Int32 CursorSize`


         Int32 ret = Console.CursorSize()


`public static Int32 CursorTop`


         Int32 ret = Console.CursorTop()


`public static Boolean CursorVisible`


         Boolean ret = Console.CursorVisible()


`public static TextWriter Error`


         TextWriter ret = Console.Error()


`public static ConsoleColor ForegroundColor`


         ConsoleColor ret = Console.ForegroundColor()


`public static TextReader In`


         TextReader ret = Console.In()


`public static Encoding InputEncoding`


         Encoding ret = Console.InputEncoding()


`public static Boolean IsErrorRedirected`


         Boolean ret = Console.IsErrorRedirected()


`public static Boolean IsInputRedirected`


         Boolean ret = Console.IsInputRedirected()


`public static Boolean IsOutputRedirected`


         Boolean ret = Console.IsOutputRedirected()


`public static Boolean KeyAvailable`


         Boolean ret = Console.KeyAvailable()


`public static Int32 LargestWindowHeight`


         Int32 ret = Console.LargestWindowHeight()


`public static Int32 LargestWindowWidth`


         Int32 ret = Console.LargestWindowWidth()


`public static Boolean NumberLock`


         Boolean ret = Console.NumberLock()


`public static TextWriter Out`


         TextWriter ret = Console.Out()


`public static Encoding OutputEncoding`


         Encoding ret = Console.OutputEncoding()


`public static String Title`


         String ret = Console.Title()


`public static Boolean TreatControlCAsInput`


         Boolean ret = Console.TreatControlCAsInput()


`public static Int32 WindowHeight`


         Int32 ret = Console.WindowHeight()


`public static Int32 WindowLeft`


         Int32 ret = Console.WindowLeft()


`public static Int32 WindowTop`


         Int32 ret = Console.WindowTop()


`public static Int32 WindowWidth`


         Int32 ret = Console.WindowWidth()


