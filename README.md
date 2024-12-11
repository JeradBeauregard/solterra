# solterra

# Solterra

Welcome to Solterra, a virtual pet website that combines the magic of fantasy and ethereal elements with modern 3D web technology. This README provides an overview of the project and guides you through getting started as a developer or contributor.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Setup and Installation](#setup-and-installation)
5. [Development](#development)
6. [Contributing](#contributing)
7. [License](#license)

---

## Overview
Solterra is a browser-based virtual pet experience that lets users adopt, care for, and interact with unique digital pets in a 3D environment. With a focus on fostering joy and nurturing, Solterra aims to create an engaging platform where players can bond with their pets, explore their inventories, and access in-game shops through seamless, interactive overlays.

## Features
- **Adoptable Fantasy Pets**: Choose from a range of magical, ethereal creatures.
- **3D Environment**: Each pet's page includes an interactive 3D model with simple animations.
- **Custom Overlays**: Access profile, inventory, and store menus via dynamic overlays.
- **Immersive Design**: A vibrant UI inspired by fantasy themes and intuitive navigation.

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript, WebGL/Three.js
- **Backend**: ASP.NET Core
- **Database**: SQL Server
- **Version Control**: Git

## Setup and Installation

### Prerequisites
- Node.js and npm (for frontend dependencies)
- .NET SDK (for backend development)
- SQL Server (for the database)
- Git (for version control)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/solterra.git
   cd solterra
   ```

2. **Install Frontend Dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Setup Backend**:
   - Navigate to the backend folder and restore dependencies:
     ```bash
     cd ../server
     dotnet restore
     ```
   - Configure the `appsettings.json` file with your SQL Server connection string.

4. **Database Migration**:
   Run the migrations to set up the database schema:
   ```bash
   dotnet ef database update
   ```

5. **Run the Application**:
   - Start the backend server:
     ```bash
     dotnet run
     ```
   - Start the frontend development server:
     ```bash
     cd ../client
     npm start
     ```

6. **Access the App**:
   Open your browser and navigate to `http://localhost:3000`.

## Development

### Folder Structure
```
solterra/
├── client/           # Frontend source code
├── server/           # Backend source code
├── database/         # Database migration scripts
├── docs/             # Documentation files
└── assets/           # Static assets (images, 3D models, etc.)
```

### Code Standards
- **Frontend**: Follow the Airbnb JavaScript style guide.
- **Backend**: Use C# coding conventions.
- **Commits**: Write clear and descriptive commit messages.

### Testing
- Unit tests: Run with `dotnet test` for backend and `npm test` for frontend.
- Integration tests: Set up testing scripts as described in `docs/testing.md`.

## Contributing
We welcome contributions from the community! Here's how you can help:
1. Fork the repository and create a new branch for your feature or bugfix.
2. Commit your changes and open a pull request with a detailed description.
3. Follow the [Contributor Guidelines](docs/CONTRIBUTING.md).

## License
Solterra is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in Solterra! We’re excited to have you join us in bringing this magical experience to life.

