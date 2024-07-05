# Eye Bank Management System

This is a simple Eye Bank Management System implemented in Prolog. 
It allows users to manage cornea records with various functionalities such as adding, updating, displaying, testing, discarding, and distributing cornea.

## Features

- **Add Cornea**: Add a new cornea record to the system.
- **Display Cornea**: Display all cornea records in a tabular format.
- **Update Cornea**: Update existing cornea records.
- **Test Cornea**: Mark a cornea as tested.
- **Discard Cornea**: Remove a cornea from the system.
- **Distribute Cornea**: Mark a cornea as distributed.
- **Save Data**: Save cornea data to a file.
- **Load Data**: Load cornea data from a file.

## Commands

1. **add**: Add a new cornea.
2. **display**: Display all cornea.
3. **update**: Update a cornea.
4. **test**: Mark a cornea as tested.
5. **discard**: Discard a cornea.
6. **distribute**: Mark a cornea as distributed.
7. **exit**: Exit the Eye Bank Management System.

## Usage

To start the Eye Bank Management System, simply run the Prolog file. The system will load existing data from a file and display available commands.

```prolog
:- initialization(load_data), start.
