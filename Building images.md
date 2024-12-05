## Commands
- COPY: basically asks the image to copy anything within the directory of the Dockerfile. Written as COPY [source] [working directory of the image]
- WORKDIR: declares the working directory on the image
- ADD (optional): only if you need to add a file from a URL
- RUN: can use this to install dependencies, etc. Also lets you add a group of users
- ENV: setting environment variables.
- EXPOSE: which port the container will be listening on
- USER: used for setting the user with
- CMD: default command to start the container like npm start for example. RUN is a runtime instruction, CMD isn't. Format: ["", ""] where a new shell process isn't started and this is the exec form.
- ENTRYPOINT: eg: ["npm", "start"] - same as CMD but not really overwritable. CMD is more for adhoc commands.

- 

- Run the image through the shell and run whoami to see which user you're currently on
