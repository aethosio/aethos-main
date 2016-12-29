# AethOS Services

While most operating systems utilize libraries as the main form of code reuse, AethOS also utilizes services and micro services.

# Libraries

Libraries are packages of JavaScript source code that is shared directly by applications.  The source code for an application is mapped to an application container and then directly imported into the application script.

Client and server libraries for JavaScript are installed by [apm](https://github.com/aethosio/package-manager), the AethOS package manager.

# Plugins

Plugins are packages of compiled code in the form of a shared library (.so in Linux terms) and dynamically loaded by Zen Server.

Plugins can only be utilized by server applications.

# Services

Services are essentially headless applications, intended to be utilized by other applications thorugh a well defined (typically REST) API.

Services are started automatically and are executed as a separate process in its own container.

# Micro Services

Micro services are stateless services that run in a shared container.

These stateless services are generally used as lambda functions that respond to events.
