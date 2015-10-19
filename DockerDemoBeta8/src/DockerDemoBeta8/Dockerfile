FROM microsoft/aspnet:latest
COPY DockerDemoBeta8/src/DockerDemoBeta8 /app
WORKDIR /app
RUN ["dnu", "restore"]

EXPOSE 5004
ENTRYPOINT ["dnx", ".", "kestrel"]