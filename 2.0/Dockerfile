FROM microsoft/aspnetcore:2.0

RUN apt-get update \
    && apt-get install -y --no-install-recommends libgdiplus \
    && apt-get clean \
    && rm -r /var/lib/apt/lists /var/cache/apt/archives
