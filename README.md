# Appointment Manager API

## Description

The Appointment Manager API is a robust system built using the Nest.js framework, designed to manage appointments for VIPs. It's hosted live at [Appointment Manager API](https://appointment-manager-42ic.onrender.com).

## Installation

To get started, install the necessary dependencies using npm:

```bash
$ npm install
```

## Running the App

You can run the application in various modes:

- **Development Mode**:

```bash
$ npm run start
```

- **Watch Mode (for development)**:

```bash
$ npm run start:dev
```

- **Production Mode**:

```bash
$ npm run start:prod
```

## Testing

You can run different types of tests:

- **Unit Tests**:

```bash
$ npm run test
```

- **End-to-End Tests**:

```bash
$ npm run test:e2e
```

- **Test Coverage**:

```bash
$ npm run test:cov
```

## Features

The Appointment Manager API built with Nest.js includes the following features:

- **VIP Management**: Create, update, and delete VIP profiles.

- **Appointment Scheduling**: Schedule appointments for VIPs with various details, including date, time, and priority.

- **Status Tracking**: Track appointment status (pending, approved, rejected, completed).

- **Push Notifications**: Receive real time notifications as appointment status changes

- **User Authentication**: Secure endpoints and manage user roles and permissions.

- **Visitor Information**: Record visitor details for each appointment.

- **Search and Filtering**: Search and filter appointments based on various criteria.

## Environment Variables

Before running the API, ensure you have set up the following environment variables in your `.env` file:

```env
JWT_TOKEN=xxxxx
MAIL_ADDRESS=xxxxxx
MAIL_PASSWORD=xxxxxxx
MONGO_DB_NAME=xxxx
MONGO_DB_URL=xxxxx
PORT=5000
PRIVATEVAPIDKEY=xxxxx
PUBLICVAPIDKEY=xxxxxx
SITE_LINK=http://localhost:5000
```

Replace the placeholders with your actual database URL and secret key.

## Documentation

For detailed documentation on how to use the Appointment Manager API and its endpoints, refer to the [API Documentation](https://appointment-manager-42ic.onrender.com/docs).

## Contributing

Contributions to the Appointment Manager API are welcome! If you'd like to contribute:

1. Fork the project on GitHub.

2. Create a new branch for your changes.

3. Make your improvements or additions.

4. Thoroughly test your changes.

5. Create a pull request with a clear description of your changes.

Your contributions are highly appreciated and will help improve the functionality and reliability of the API.
