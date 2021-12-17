# This is an example implementation of React SAP auth0 implementation

## Reference doc can be found

https://auth0.com/docs/quickstart/spa/react#add-login-to-your-application

## implementation steps:
1. create a dev account with auth0
2. set up an application
- set the application type to SPA
- set token endpoint authentication method to NONE
- allowed callback urls & allowed logout urls & allowed web origins to http://localhost:3000 if working on localhost
3. create a react app
4. install auth0 react SDK: npm install @auth0/auth0-react
5. configure the Auth0PRovider component and wrap the app component & replace the domain and client ID
6. add Login, Logout and Profile component from useAuth0 custom hook {loginWithRedirect, logout, user, isAuthenticated, isLoading}
7. configure additional features in auth0
