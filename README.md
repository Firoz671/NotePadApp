# NotepadApp

NotepadApp is a simple text editor application implemented in Java using Swing. It provides basic functionality such as creating new files, opening existing files, saving files, and performing text editing operations like cut, copy, and paste.

## Features

- Create a new file: Clears the text area.
- Open an existing file: Reads the contents of the selected file and displays them in the text area.
- Save the current file: Saves the contents of the text area to the current file.
- Save As: Allows saving the contents of the text area to a new file.
- Exit: Closes the application.
- Cut, Copy, Paste: Perform text editing operations on the contents of the text area.

## Usage

1. **New**: Click on "File" in the menu bar and select "New" to create a new file. The text area will be cleared.
2. **Open**: Click on "File" in the menu bar and select "Open" to choose an existing file to open. The contents of the file will be displayed in the text area.
3. **Save**: Click on "File" in the menu bar and select "Save" to save the contents of the text area to the current file. If the file has not been previously saved, a file chooser dialog will appear to choose the save location.
4. **Save As**: Click on "File" in the menu bar and select "Save As" to save the contents of the text area to a new file. A file chooser dialog will appear to choose the save location.
5. **Exit**: Click on "File" in the menu bar and select "Exit" to close the application.
6. **Cut, Copy, Paste**: Select the desired text in the text area and right-click to access the context menu or use the keyboard shortcuts (Ctrl+X for Cut, Ctrl+C for Copy, Ctrl+V for Paste).

## Implementation Details

The application is implemented as a subclass of `JFrame` and contains a `JTextArea` component for displaying and editing the text. The main menu bar consists of two menus: "File" and "Edit". The "File" menu contains options for file-related operations, while the "Edit" menu contains options for text editing operations.

The file-related operations (New, Open, Save, Save As, Exit) are implemented using `ActionListener` interfaces, which handle the corresponding actions when the menu items are clicked.

The `JFileChooser` class is used to provide file selection dialogs for opening and saving files.

## Building and Running

To compile and run the NotepadApp, you need to have Java Development Kit (JDK) installed on your system.

1. Save the code in a file called `NotepadApp.java`.
2. Open a command prompt or terminal and navigate to the directory where the `NotepadApp.java` file is saved.
3. Compile the code by running the following command:

   ```shell
   javac NotepadApp.java
   ```

4. After a successful compilation, run the application with the following command:

   ```shell
   java NotepadApp
   ```

5. The NotepadApp window will open, and you can start using the text editor features.

## License

This code is provided without any license or warranty. You can use it for educational and personal purposes.
