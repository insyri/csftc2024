# Welcome to CSFTC 2024!
- To start interacting with others, please see the [Discussions](https://github.com/insyri/csftc2024/discussions) board
- If you have any questions, feel free to reach out to me via my student email— refer to the [shared folder](https://drive.google.com/drive/u/0/folders/1JfHMkxaTco7L3CY67nRwVAqq-ECT2HEr) with the syllabus.

## Starting with Kotlin

1. Set up your own directory under the `submissions` folder. Using the explorer on your right, right click `submission` and create a new folder, name it your first name. In this example, we'll assume your name is `elizabeth`.

2. Create your own Kotlin file within the `./submissions` folder, under your name. Make sure it ends with `.kt`. We'll assume you've called it `hello.kt`.

    Your new file will be at `./submissions/elizabeth/hello.kt`.
    
3. Using the terminal, that bar on the bottom of your screen (or press <kbd>Ctrl</kbd> + <kbd>\`</kbd> if you don't see it), enter the following command to **c**hange your **d**irectory into this one:
    
    If my name were `elizabeth`, I would do:
    ```bash
    cd ./submissions/elizabeth
    ```

4. Once you're done coding, compile the application using the Kotlin compiler:
    ```bash
    kotlinc hello.kt -include-runtime -d hello.jar
    ```
    The `-d` option indicates the output path for generated class files, which may be either a directory or a **.jar** file. The `-include-runtime` option makes the resulting **.jar** file self-contained and runnable by including the Kotlin runtime library in it.

5. Run the application:
    ```bash
    java -jar hello.jar
    ```

If you make changes to your code and want to run your application again, repeat steps 4 and 5.

Tip: Use the up and down arrow keys within the terminal to select previous commands, that way you don't have to type it again!
