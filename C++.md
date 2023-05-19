

# Running C++ Code in Termux

This guide explains how to compile and run C++ code using Termux on an Android device.

## Prerequisites

Before proceeding, make sure you have the following installed on your Android device:

- Termux: You can install it from the Google Play Store or the F-Droid repository.

## Instructions

1. Launch the Termux app on your Android device.

2. Update the package lists by running the following command:

   ```

   pkg update

   ```

3. Install the required packages for C++ compilation:

   ```

   pkg install clang

   ```

4. Write your C++ code using a text editor or the Termux editor. For example, create a file named `hello.cpp` and enter the following code:

   ```cpp

   #include <iostream>

   int main() {

       std::cout << "Hello, World!" << std::endl;

       return 0;

   }

   ```

5. Save the file and exit the text editor.

6. Compile the C++ code using the `clang` compiler:

   ```

   clang++ -o hello hello.cpp

   ```

   This command will generate an executable named `hello` based on the `hello.cpp` source file.

7. Run the compiled program:

   ```

   ./hello

   ```

   You should see the output `Hello, World!` printed in the terminal.

## Additional Notes

- You can use any text editor of your choice to write C++ code in Termux. Some popular options include `vim`, `nano`, and `emacs`.

- If your C++ code requires additional libraries, you may need to install them using the `pkg install` command before compiling.

- Make sure to navigate to the correct directory in Termux where your C++ code is located before compiling and running it.

- Remember to save your C++ files with the `.cpp` extension to ensure they are recognized as C++ source code.

That's it! You can now compile and run your C++ code in Termux on your Android device.
