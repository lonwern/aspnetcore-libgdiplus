FROM microsoft/dotnet:2.1-aspnetcore-runtime

RUN apt-get update \
    && apt-get -y install libgdiplus \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
