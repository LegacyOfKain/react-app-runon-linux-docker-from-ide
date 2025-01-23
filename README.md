## Docker Commands

This project includes Docker support for development and building. Here are the special Docker commands you can use:

### Running the Development Environment

To start the development environment using Docker, run:

```bash
npm run docker:dev
```

or if you're using Yarn:

```bash
yarn docker:dev
```

This command will start the Docker containers and run the development server on port 5173.

### Building the Project

To build the project using Docker, use one of the following commands based on your operating system:

For Unix-based systems (Linux, macOS):

```bash
npm run docker:build:linux
```

or with Yarn:

```bash
yarn docker:build:linux
```

For Windows:

```bash
npm run docker:build:win
```

or with Yarn:

```bash
yarn docker:build:win
```

These commands will:
1. Start the Docker containers
2. Build the project inside the Docker environment
3. Copy the built files from the Docker container to your local `./dist` directory
4. Stop and remove the Docker containers

After running these commands, you'll find the built project in the `./dist` directory, ready for deployment.

Note: Make sure you have Docker and Docker Compose installed on your system before running these commands.