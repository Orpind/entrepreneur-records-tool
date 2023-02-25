# Entrepreneur Records Tool

This is a tool for keeping records of individual entrepreneurs. It was built using [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/), [Material UI](https://mui.com/), [NX](https://nx.dev/), [NestJS](https://nestjs.com/), [Vite](https://vitejs.dev/), [Docker](https://www.docker.com/), and [Kubernetes](https://kubernetes.io/).

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` to install all the necessary dependencies.
3. Run `npm start` to start the development server.
4. Open `http://localhost:3000` in your browser to view the application.

## Development

This project uses NX to manage the monorepo structure. To run the available commands, use the `nx` CLI. For example, to run tests for all packages, run `nx test`.

The frontend is built using Vite, and the backend is built using NestJS. Both use TypeScript.

## Deployment

This application can be deployed using Docker and Kubernetes. Follow these steps to deploy the application:

1. Build the Docker image by running `docker build -t entrepreneur-records-tool ..`
2. Push the Docker image to a container registry of your choice.
3. Modify the `deployment.yaml` file to include the appropriate image name and tag.
4. Apply the Kubernetes deployment and service configuration by running `kubectl apply -f deployment.yaml`.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Create a pull request to merge your changes back into the main repository.

## License

This project is licensed under the [MIT License](LICENSE).
