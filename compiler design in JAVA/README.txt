COMPILER DESIGN IN JAVA
Once you have the repository, import the project in eclipse.

-> File 
  -> Import
    -> General 
      -> Existing Projects into Workspace...
Using PYCompyler 🏁
To use PYCompyler there are two alternatives, you can write your own program (View the syntax) (Ver la sintaxis) or use an example one. I recommend you the second option, if it´s your first time. There are a few example programs in the folder called "program4Test".

Once you've chosen an option, you only have to run the main class, that is located in the "py" package, passing the name of the input and the output file as a parameters. Here is a example with the program "big.input.txt", that calculates the Fibonacci sequence.

-> Run as 
  -> Run configurations
    -> Java Application  
      -> Arguments 
        -> programs4Test/big.input.txt output.txt
Now you'll see the instrospector window, that shows a general view of the AST (Abstract Syntax Tree) built by the compiler. You can take a look if you want but it´s not necesary.

Close the introspector window and check the output file. You should see the instructions of the program you passed written in a language like assembler.

MAPL 🔧
At this point we need to use some tool that is able to interpret the instructions. That tool is MAPL.

Execute "MAPL.cmd".

Location -> PYCompiler\MAPL.cmd
By default, MAPL load the "output.txt" file but you can chose other in "File -> Open..."

Using MAPL is very simple. At the left of the window we have the instructions of the program loaded and the buttons to run, debugg, reload... In the middle the static memory and finally in the rigth, the stack memory. Also there is an small terminal at bottom left.

To end with the example, run the program by clicking in the green arrow and look what happends. You should see the Fibonacci sequence calculated in the terminal. 💻

Development 🚧 ⚙️
Now you will learn how the project is composed:

Lexical paterns
GLC (context-free grammar)
Abstract grammar
Code templates
UML
Built With 🛠️
Java