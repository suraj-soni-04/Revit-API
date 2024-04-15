# Revit API using C#

This repository contains examples and utilities for using the Revit API with C#. The Revit API provides a powerful way to interact with Autodesk Revit, allowing developers to automate tasks, create custom tools, and extend the functionality of Revit.

## Getting Started

### Prerequisites

To work with the code in this repository, you'll need:

- [Autodesk Revit](https://www.autodesk.com/products/revit/overview) installed on your machine.
- A compatible version of Visual Studio for compiling and running the C# code.

### Installing

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/revit-api-csharp.git
    ```

2. Open the solution file (`RevitAPISamples.sln`) in Visual Studio.

3. Build the solution to ensure all dependencies are resolved.

## Contents

- **Examples:** Contains various examples demonstrating how to perform common tasks using the Revit API.
- **Utilities:** Helpful utilities and helper classes for working with the Revit API.
- **Documentation:** Additional documentation and resources for understanding and working with the Revit API.

## Contributing

Contributions to this repository are welcome! If you have improvements, bug fixes, or new examples to add, feel free to open a pull request. Please follow the existing coding style and ensure that any new code is properly documented.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Autodesk Developer Network (ADN) for providing comprehensive documentation and support for the Revit API.
- Contributors to this repository for their valuable contributions and feedback.

## Resources

- [Autodesk Revit API Documentation](https://www.autodesk.com/developer-network/platform-technologies/revit)
- [Revit API Forum](https://forums.autodesk.com/t5/revit-api-forum/bd-p/160)
- [Revit API GitHub Repository](https://github.com/ADN-DevTech)

## Implementation 
### 1. AddButton
   
   The AddButton project features a straightforward "Hello World" button as a Revit add-in. When clicked, it displays a corresponding message.
   To utilize the AddButton add-in:
  
  Load the add-in into Revit.
  Navigate to the "Add-Ins" tab -> External-Tools -> Demo-Hello World.
  Click on the "Hello World" button.
  
  ![Screenshot (130)](https://github.com/suraj-soni-04/Revit-API/assets/154866411/05d9f5d4-f576-471d-9c30-0cec8531b8a5)


### 2. AddPanel

  The AddPanel project establishes a custom ribbon named "Hello World" and integrates a button into it.
  To utilize the AddPanel ribbon:

  Load the add-in into Revit.
  Navigate to the "Add-Ins" tab on the ribbon.
  Under "NewRibbonPanel," click on the Hello World image.

  ![Screenshot (131)](https://github.com/suraj-soni-04/Revit-API/assets/154866411/97778242-fe70-4df3-beef-b5e0cb542609)
