# Unit 3 Web Services Assignment

This repository contains the implementation and documentation for a simple HTTP-based web service using Node.js, along with a detailed report on web services architecture and the differences between RESTful and SOAP-based services.

## Contents

- `index.js` - Node.js server code implementing a basic RESTful web service.
- `22BCP350_CyberSecurity.pdf` - Detailed report covering:
  - Architecture of web services and the role of servers.
  - Differences between RESTful and SOAP-based services.
  - Step-by-step guide for implementing and deploying a Node.js web service locally.
  - Deployment with screenshots.
- `README.md` - This file, providing an overview of the project.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies:**
   Ensure Node.js is installed, then run:
   ```bash
   npm install
   ```

3. **Run the Service Locally:**
   ```bash
   node index.js
   ```
   Access the service at `http://localhost:3000/api/message`.

## Deployment Details

- The Node.js web service is deployed locally using the Express framework.
- The service responds to GET requests at `/api/message` with a simple JSON response.

## Testing

You can test the service using:

- **Browser:** Navigate to `http://localhost:3000/api/message`
- **cURL:**
   ```bash
   curl http://localhost:3000/api/message
   ```


## Author

- Jyot Pandya (22BCP350)
- Pandit Deendayal Energy University

---