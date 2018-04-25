FROM microsoft/aspnetcore:1.1

RUN apt-get update \
    && apt-get -y install libgdiplus \
    && rm -rf /var/lib/apt/lists/*
