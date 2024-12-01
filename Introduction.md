# Introduction
- Creates an environment to package an app, for example, and all its dependencies which includes versions of libraries etc
- Containerisation - makes use of containers to package an app
- Virtual machines - resource intensive since they take up memory, hardware space etc and needs an OS
- Containers are lightweight, use OS of the host, starts quickly and need less hardware resources
- Docker engine runs containers. Containers are processes. Containers share the 'kernel' of the host which means there are specific APIs that communicate with the host OS.

- Docker image - cutdown version of an OS, has a runtime env, third party libraries, env variables, application files. We tell containers to take an image and run it as a process. Can push these images to docker registry.
