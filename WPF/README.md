# GCHEMISTRY

GCHEMISTRY is a desktop WPF application for a sales manager who works with chemical reagents.

The project was made for a college course about Windows Forms and WPF development. It was built as a client-style project: my classmate acted as the client, gave the task, and checked the result during project testing.

## Purpose

The application is an automated workplace for a sales manager. It helps the user search products, check stock, and create sales faster than in an old and uncomfortable ERP interface.

The main goal was to create a simple, modern, and fast interface for everyday work.

## Features

- Login window with username and password
- Product search by name
- Product search by article number
- Product table with price, stock, barcode, and quality
- Quick sale window
- Full sale window with filters
- Stock quantity update after sale
- Input validation
- Keyboard shortcuts for faster work

## Keyboard Shortcuts

- `F1` - focus on search
- `F5` - open quick sale
- `F6` - open full sale

## Tech Stack

- C#
- WPF
- XAML
- .NET 6 (original project target; now out of support)

## Data Storage

This project is a study prototype.

User accounts and product data are stored inside the application code or memory. Created sales are stored in memory while the program is running.

## Screenshots

### Login

![Login screen](screenshots/login.png)

### Main Window

![Main window](screenshots/main-window.png)

### Product Search

![Product search](screenshots/product-search.png)

### Quick Sale

![Quick sale](screenshots/quick-sale.png)

### Full Sale

![Full sale](screenshots/full-sale.png)

## My Role

My work included:

- analyzed the task
- designed the interface
- created the WPF windows
- worked with XAML and C#
- implemented search, sales, validation, and hotkeys
- wrote the project report
- prepared the presentation
- presented and defended the project

AI tools assisted with coding. I reviewed the XAML and C#, tested the application, prepared the documentation and made the final decisions.

## Testing

The project was tested on June 29, 2026.

Tested scenarios:

- correct login
- incorrect login
- search by product name
- search by article number
- quick sale
- full sale
- stock update after sale
- incorrect input handling

No critical issues were found during the test.

## Documentation

The folder also contains a Russian project report written according to college/GOST-style requirements.

## Project Status

The application is finished as a college project prototype.

This repository currently contains the executable, report, screenshots and README. C# and XAML source files are not published here, so the application cannot be rebuilt from this repository.
