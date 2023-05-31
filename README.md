# System Resource Allocator (SRA)

## Description

SRA is a C++ and C# application designed to allow users to manually allocate system resources to specific tasks or applications. The idea is to give users more control over their system's resources, which can lead to performance improvements for specific tasks or applications.

The application consists of a C++ backend that interacts with the system and a C# frontend that provides a graphical user interface for the user.

## Features

- Displays current allocation of system resources
- Allows users to allocate specific amounts of resources to specific tasks or applications
- Updates in real time to reflect changes in system state

## Requirements

- Windows 10 or later
- .NET Framework 4.7.2 or later

## How to Use

1. Launch the application.
2. The main window displays the current allocation of system resources.
3. To allocate resources to a task, enter the process ID and the amount of resources to allocate in the text boxes.
4. Click the "Allocate" button. The application will attempt to allocate the specified resources to the task.

## Limitations

This is a basic version of the application and it has several limitations:

- The application currently only supports allocating memory. Future versions may support allocating other resources.
- The application does not check whether the requested allocation is possible or safe. It is up to the user to ensure that they do not allocate more resources than are available or safe to use.
- The application has only been tested on Windows 10. It may not work correctly on other operating systems.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
