## How to run a C program in Termux

To run a C program in Termux, follow these steps:

1. **Install Termux**: Termux is an Android terminal emulator and Linux environment app available on the Google Play Store. Install it on your Android device.

2. **Open Termux**: Launch the Termux app on your Android device to open the terminal emulator.

3. **Install necessary packages**: Termux provides a package management system to install required packages. Execute the following command in the Termux terminal to install the necessary packages for compiling and running C programs:

    ```bash
    pkg install clang
    ```

4. **Write your C program**: Use any text editor available in Termux, such as nano or vim, to write your C program. For example, you can create a file called `program.c` using the nano editor:

    ```bash
    nano program.c
    ```

    This will open the nano editor. Enter your C program code in this file.

5. **Save the C program**: After writing your C program, save it by pressing `Ctrl + O` and then press `Enter`. To exit the nano editor, press `Ctrl + X`.

6. **Compile the C program**: In the Termux terminal, use the `clang` compiler to compile your C program. Execute the following command:

    ```bash
    clang program.c -o program
    ```

    This command compiles your `program.c` file and generates an executable file named `program`.

7. **Run the C program**: Once the compilation is successful, you can run the C program by executing the following command:

    ```bash
    ./program
    ```

    This command runs the compiled program named `program`.

That's it! You have successfully compiled and run a C program in Termux. Make sure to navigate to the correct directory where your C program is located before executing the compilation and run commands.
