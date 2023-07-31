# Exercise1

# How to install typescript on windows

To install TypeScript on Windows, you can use Node.js package manager, npm (Node Package Manager), which comes bundled with Node.js. Here's a step-by-step guide to installing TypeScript on your Windows machine:

1. Install Node.js:
   If you don't have Node.js installed, you can download and install it from the official website: https://nodejs.org/

2. Verify Node.js and npm installation:
   Open a command prompt (cmd) or PowerShell and type the following commands to verify that Node.js and npm are correctly installed:

   ```
   node -v
   npm -v
   ```

   If both commands return version numbers, you have successfully installed Node.js and npm.

3. Install TypeScript:
   Once Node.js and npm are installed, you can install TypeScript globally by executing the following command in the command prompt or PowerShell:

   ```
   npm install -g typescript
   ```

   The `-g` flag means you are installing TypeScript globally, making it accessible from any directory on your system.

4. Verify TypeScript installation:
   To ensure that TypeScript has been installed correctly, type the following command:

   ```
   tsc -v
   ```

   If the installation was successful, it will display the version number of TypeScript.

That's it! TypeScript is now installed on your Windows machine. 

# How to Compile TypeScript Files

Introduction:
"Welcome back to our TypeScript insght with kamran! here, we'll learn how to compile TypeScript files into JavaScript using the `tsc` command. Let's get started!"

[Step 1: Initialize a TypeScript Project]

1. Open Visual Studio Code.
2. Create a new folder for your TypeScript project.
3. Open folder in code.
4. open command prompt in code.
5. make your you use Command prompt not Powershell
6. To initialize a TypeScript project, type the following command on command prom:
   ```
   tsc --init
   ```
   This command generates a `tsconfig.json` file that contains the configuration settings for the TypeScript compiler.

7. The `tsconfig.json` file will be created in the project directory. Open it in your code editor.

[Step 2: Configure the TypeScript Compiler]

1. Inside the `tsconfig.json` file, you'll find various compiler options.
2. Uncomment or modify the options as per your project requirements.
   For example, you can set the target JavaScript version, specify the output directory, enable strict type-checking, and more.
   Save the `tsconfig.json` file once you've made the necessary changes.

[Step 3: Write a Simple TypeScript Program]

1. Create a new file in your code editor and save it with a `.ts` extension. For example, `index.ts`.
2. Write your TypeScript code in the file. For this example, let's write a simple program:
   ```typescript
   let message: string = "Hello, TypeScript!";
   console.log(message);
   ```
   
   This program declares a variable `message` of type `string` and logs it to the console.
Note: Please save your code with Ctrl+S command before compiling.

[Step 4: Compile the TypeScript File]

1. Switch back to the command prompt window.
2. Navigate to the project directory if you're not already there.
3. To compile the TypeScript file, simply type the following command:
   ```
   tsc
   ```
   The `tsc` command without any arguments compiles all the TypeScript files in the current directory based on the `tsconfig.json` configuration.

4. If there are no errors in your TypeScript code, the compiler will generate a corresponding JavaScript file in the specified output directory (if configured) or the same directory as the TypeScript file.

[Step 5: Run the Compiled JavaScript]

1. To run the compiled JavaScript file, type the following command:
   ```
   node index.js
   ```
   This command executes the JavaScript code using Node.js.
   You should see the output "Hello, TypeScript!" displayed in the console.
