# Getting Started with IntelliJ IDEA: Creating Your First Java Program

Up until now, we've used JShell to write our Java code. Now we'll start using IntelliJ IDEA, an Integrated Development Environment (IDE), to create and run our first program, "Hello World". If you haven't installed IntelliJ IDEA yet, please ensure it is installed correctly before proceeding.

## Setting Up Your Project

1. **Open IntelliJ IDEA**: Launch the IDE and click on "New Project".
2. **Choose Project Type**: Select Java as the project type.
3. **Specify the JDK**: Ensure the Java Development Kit (JDK) version 17 is selected. This should be the default if installed correctly.
4. **Name Your Project**: Name your project "HelloWorld" without spaces to avoid potential issues with filenames and folders in different operating systems. Use Upper Camel Case (Pascal Case) for better readability, capitalizing the first letter of each word.
5. **Set Project Location**: Set the project location to a default folder, which will be the parent folder for all your IntelliJ projects.
6. **Verify Settings**: Make sure the JDK version is 17 and that "add sample code" is unchecked.
7. **Create the Project**: Click "Create" to set up the project.

## Creating Your First Java Class

1. **Open Project Structure**: IntelliJ IDEA will create a project structure with a "src" folder where your code will reside.
2. **Create Java Class**: Right-click on the "src" folder, select "New", then "Java Class", and name it "FirstClass" with Pascal Case. IntelliJ will generate some basic code for the class in the editor window.

## Writing and Running Your Code

1. **Generate Main Method**: Move the cursor inside the class body, type `psvm`, and press the Tab key. This shortcut generates the main method.
2. **Write Print Statement**: Inside the main method, type `System.out.println("Hello World");`.
3. **Run the Program**: To run the program, click the green arrow on the right or right-click inside the main method and select "Run 'FirstClass.main()'".
4. **View Output**: The output will be displayed in the Run pane at the bottom of IntelliJ IDEA, showing "Hello World" and "Process finished with exit code 0", indicating the program ran successfully.

This guide has shown you how to set up and run your first Java program using IntelliJ IDEA. Next, we'll delve deeper into understanding the source code in the editor window and further explore IntelliJ's features.

