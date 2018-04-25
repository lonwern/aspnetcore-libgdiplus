FROM microsoft/aspnetcore:2.0

RUN apt-get update \
    && apt-get -y install libgdiplus \
    && rm -rf /var/lib/apt/lists/*
