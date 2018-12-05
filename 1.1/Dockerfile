FROM microsoft/aspnetcore:1.1

RUN apt-get update \
    && apt-get install -y --no-install-recommends libgdiplus \
    && apt-get clean \
    && rm -r /var/lib/apt/lists /var/cache/apt/archives
