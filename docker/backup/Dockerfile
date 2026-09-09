FROM ubuntu:24.04

WORKDIR /app

COPY backup .

RUN chmod +x backup

#It uses backup script as a fixed entrypoint we can interact with by using commands.
ENTRYPOINT ["./backup"]

#If no command argument is given then script is going to use "list" command as default.
CMD ["list"]


