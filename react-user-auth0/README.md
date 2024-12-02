# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Auth0 allows you to add authentication to your React application quickly and to gain access to user profile information. This guide demonstrates how to integrate Auth0 with any new or existing React application using the Auth0 React SDK.

# Configure Auth0

When you signed up for Auth0 [`https://auth0.com`], a new application was created for you, or you could have created a new one. You will need some details about that application to communicate with Auth0. Application Settings section in the Auth0 dashboard.

You will need the following:

- Domain
- Client ID

## Install the Auth0 React SDK

Run the following command within your project directory to install the Auth0 React SDK:
`npm install @auth0/auth0-react`
