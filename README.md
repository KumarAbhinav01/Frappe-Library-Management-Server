# Library Management System

This is a Library Management System project built using Django and React.

## Project Overview

This project aims to provide a web-based Library Management System where users can manage books, members, issue and return books, and more.


## Getting Started

### Prerequisites

- Node.js
- Python
- Docker (optional, for containerization)

### Installation

1. Clone the repository:

 ```bash
 git clone https://github.com/your-username/library-management.git
   cd library-management```

2. Create a virtual environment for the project and activate it:

```bash
python -m venv venv
source venv/bin/activate      # On macOS/Linux
venv\Scripts\activate.bat     # On Windows
```
4. Run the development server:
```bash
npm start
```

## Note: After starting this please move to the client side folder and launch the project, to view the full-stack library management system.

# Dockerization (optional)

1. Build the Docker image:
```bash
docker build -t library-app .
```

2. Run the Docker container:

```bash
docker run -it -p 3000:3000 library-app
```

# Project Configuration

The Django project settings can be found in library_app/settings.py.

Please review and update settings as needed for your environment.

## Contributing

Contributions are welcome! If you find a bug or have an enhancement suggestion, please open an issue or create a pull request.

## License

License
This project is licensed under the MIT License - see the LICENSE file for details.

