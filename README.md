# File_manager-Project

The code opens a file and then starts the program.

 The code also handles exceptions that might happen when opening the file.
 
 The open_file() function opens a window to show the user what is happening, but it does not actually start running until after it has opened the file.
 
 The code is a function that opens the file manager window.
 
 The next function is open_file which opens the file you want to open.
 
 The code starts by defining a function called copy_file().
 
 This function will take in two parameters: source1 and destination1.
 
 The first parameter is the file that we want to copy, and the second parameter is where we want to save it.
 
 The next step is to define a function called delete_file().
 
 This function will take in one parameter: del_file.
 
 If this file exists, then it will be deleted using os.remove() method; otherwise, mb.showinfo('confirmation', "File not found!")
 message would be shown on screen instead of deleting the file if it doesn't exist yet.
 
 Next comes rename_file(), which takes in one parameter: chosenFile (which represents the new name for our file).
 
 It then uses os.path module's dirname() method to get the directory path from chosenFile (the old name), and splitext() method to get extension from chosenFile (the new name).
 
 The code is a function that renames the file "myfile.txt" to "myfile.txt.old".
 
 The code is a function that deletes the file "myfile.txt".
 
 The code starts by asking the user to enter a new name for the chosen file.
 
 Then it creates a new folder called "newFolder" and moves the chosenFile into that folder.
 
 It then asks the user to enter a new name for this newly created folder, which is entered as "newFolder".
 
 The code then renames the chosenFile in that newly created folder.
 
 The function move_file() is used to move files around on your computer's hard drive.
 
 This function starts by opening up an input window where you can type in any file path you want, and then it prompts you with another window where you can choose from all of your folders on your computer's hard drive.
 
 If both windows are identical, meaning they contain exactly one directory each, then nothing happens because there was no change made to either of them (source or destination).
 
 Otherwise if one of these windows contains more than one directory but not both directories at once, meaning only one has been changed while the other hasn't been touched yet, then shutil will be used to make sure that changes happen properly before continuing on with what needs done next: moving files from source location into destination location using os.move().
 
 The code is an example of a file-moving function.
 
 The code opens the source and destination files for input, then moves the source file to the destination folder.
 
 The code starts by creating a Tk window.
 
 Next, it creates a label and two buttons in the window.
 
 The first button is labeled "File Manager" and has text that says "Files in folder are:".
 
 It then creates another label with the text "Folder List" and places it to the right of the File Manager button.
 
 Finally, it creates an empty listbox called sortlist which will be used to store all of our files as we sort them into folders.
 
 The code starts by creating a Tk window named root .
 
 Next, it creates a Label with text that says "File Manager", font size 16 (Helvetica), blue color (fg) on top of the screen at row 5 column 2 .
 
 Then, it adds this Label to its parent widget's grid layout so that when you click on File Manager , you can see what file manager operations are available for you to perform.
 
 Next, there is some code inside parentheses after Label(root, text="File Manager", font=("Helvetica", 16), fg="blue").grid(row = 5, column = 2) which tells Python how many rows and columns should be created for this particular widget before adding itself to its parent's grid
 The code is used to create a file manager that displays the files in a folder.
 
 The code creates a label and buttons to perform operations.
 
 The Label(root, text="File Manager", font=("Helvetica", 16), fg="blue").grid(row = 5, column = 2) creates the UI of our file manager.
