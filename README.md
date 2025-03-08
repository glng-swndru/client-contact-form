# client-contact-form

## Introduction
Contact forms are essential for seamless communication between users and service providers. This project demonstrates how to build a simple contact form web application using Next.js, Tailwind CSS, and Docker. The application provides a user-friendly interface for submitting messages and integrates with an API for handling form submissions.

## Project Overview
**client-contact-form** is a Next.js-based web application designed for submitting contact messages efficiently. The project leverages:

- **Next.js** for building a modern React-based frontend
- **Tailwind CSS** for styling and responsive design
- **API Routes** to handle form submissions
- **Docker** for containerized deployment

This application is optimized for performance, ease of deployment, and scalability.

## Key Features
- **User-friendly Contact Form**: Simple and intuitive interface for submitting messages.
- **API Integration**: Sends contact messages via API routes.
- **Dockerized Deployment**: Ensures a consistent environment across different platforms.
- **Environment Configuration**: Uses environment variables for flexible configurations.

## Prerequisites
Before proceeding, ensure you have the following installed:

- Node.js
- Docker

## Installation
Clone the repository:

```sh
git clone https://github.com/yourusername/client-contact-form.git
cd client-contact-form
```

Install dependencies:

```sh
npm install
```

Set up environment variables by creating a `.env.local` file and configuring the necessary variables:

```sh
API_URL=http://localhost:8080
```

Run the application locally:

```sh
npm run dev
```

## Docker Deployment
To deploy using Docker:

### Build the Docker image

```sh
docker compose build
```

### Run the container

```sh
docker compose up -d
```

### Verifying the Deployment
Ensure the container is running:

```sh
docker compose ps
```

Access the application in your browser at:

```
http://localhost:3000
```

## Related Project
This frontend application works with the backend API:
- [API Contact Form](https://github.com/glng-swndru/api-contact-form)

