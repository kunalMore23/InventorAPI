# Revit API Project

This repository consists of two projects, AddButton and AddPanel, implementing a Revit API initiative. The AddButton project introduces a button labeled "Greetings Universe" as a Revit add-in, while the AddPanel project establishes a customized ribbon panel named "Greetings Universe."

## Table of Contents
- [Getting Started](#getting-started)
- [AddButton Project](#AddButton-project)
- [AddPanel Project](#addpanel-project)
- [Screenshots](#screenshots)

## Getting Started

1. Clone the repository:

    ```bash
    [git clone https://github.com/chiragpandkar7/RevitAPI.git]
    ```

2. Open the solution file of the required project in Visual Studio.

3. Build the solution.

4. Run the Revit application and confirm that the "Hello World" button and ribbon are visible.

## AddButton Project

The AddButton project adds a straightforward "Hello World" button as a Revit add-in. When clicked, it displays a message.

To utilize the AddButton add-in:
1. Load the add-in into Revit.
2. Navigate to the "Add-Ins" tab -> External-Tools -> Demo-Hello World.
3. Click on the "Hello World" button.

## AddPanel Project

The AddPanel project establishes a custom ribbon named "Hello World" and adds a button to it.

To utilize the AddPanel ribbon:
1. Load the add-in into Revit.
2. Navigate to the "HAdd-Ins" tab on the ribbon.
3. There, you will find "NewRibbonPanel"; click on the Hello World image.
