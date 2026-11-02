# TraceBack

A Java desktop application that helps people recover lost belongings by matching lost and found item reports.

## The Problem

Losing personal belongings and trying to find them through scattered lost-and-found reports can be frustrating and time-consuming. I want to create an application that helps people reconnect with their lost belongings by organizing lost and found reports and automatically identifying potential matches based on item descriptions, colors, categories, and locations.

## How It Works

TraceBack allows users to submit lost and found item reports through a graphical interface. The application compares the details of lost and found items to identify potential matches and displays the results for users to review.

The MVP will include:

- Submitting lost-item reports.
- Submitting found-item reports.
- Viewing submitted lost and found reports.
- Automatically comparing item details to identify potential matches.
- Displaying potential matches through the graphical interface.
- Saving and loading reports using CSV files.

## Tech Stack

- **Language:** Java
- **GUI:** Java Swing (`javax.swing`)
- **GUI Layouts:** Java AWT (`java.awt`)
- **Data Management:** Java Collections (`java.util.ArrayList`)
- **File Handling:** Java File I/O (`java.io`)
- **Date Management:** Java Time (`java.time`)
- **Data Storage:** CSV files
- **Development Environment:** Visual Studio Code
- **Version Control:** Git and GitHub

No external APIs or third-party libraries are required for the MVP.

## Setup

### Requirements

- Java Development Kit (JDK)
- Visual Studio Code
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/sinchanahiremath1/TraceBack.git
```

Navigate to the project directory:

```bash
cd TraceBack
```

Open the project in Visual Studio Code and ensure the Java Development Kit is installed.

The application is currently in development. Run instructions will be added once the Java source code and main application class are implemented.

## Usage

Users will be able to:

1. Launch the TraceBack desktop application.
2. Choose to report a lost item, report a found item, or view existing reports.
3. Enter the relevant item details.
4. View potential matches identified by the matching algorithm.
5. Review matching reports.
6. Access previously saved reports.

## Roadmap

The following features are planned for future versions:

- [ ] Assign compatibility scores to potential matches.
- [ ] Filter and sort reports by category, color, location, and date.
- [ ] Allow users to update an item's status to recovered or returned.
- [ ] Add keyword-based searching within item descriptions.
- [ ] Include timestamps for submitted reports.

## Author

Sinchana Hiremath

GitHub: [sinchanahiremath1](https://github.com/sinchanahiremath1)

## Project Status

Currently in the planning and initial development stage.
