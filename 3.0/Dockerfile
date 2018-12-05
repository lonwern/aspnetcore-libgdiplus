FROM microsoft/dotnet:3.0-aspnetcore-runtime

RUN apt-get update \
    && apt-get install -y --no-install-recommends libgdiplus \
    && apt-get clean \
    && rm -r /var/lib/apt/lists /var/cache/apt/archives
