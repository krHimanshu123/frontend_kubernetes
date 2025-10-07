# frontend_kubernetes

## Overview

A frontend application for interacting with Kubernetes clusters, providing a dashboard for resource monitoring, management, and deployment.

## Features

- Real-time Kubernetes cluster monitoring
- Resource management (deployments, pods, services)
- Authentication support
- Responsive UI

## Tech Stack

- React (JavaScript)
- Axios (API requests)
- Material-UI (UI components)
- Docker (containerization)
- Kubernetes API

## Project Structure

```
frontend_kubernetes/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── ResourceCard.js
│   ├── pages/
│   │   └── Dashboard.js
│   ├── services/
│   │   └── k8sService.js
│   ├── hooks/
│   │   └── useK8sData.js
│   ├── utils/
│   │   └── helpers.js
│   ├── styles/
│   │   └── App.css
│   ├── App.js
│   └── index.js
├── Dockerfile
├── package.json
├── .env
├── .gitignore
└── LICENSE
```

## Getting Started

```bash
git clone https://github.com/krHimanshu123/frontend_kubernetes.git
cd frontend_kubernetes
npm install
npm start
```

## Usage

Configure Kubernetes API endpoint in the `.env` file. Access the app at [http://localhost:3000](http://localhost:3000).

## License

MIT
