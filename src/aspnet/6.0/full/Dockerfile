FROM mcr.microsoft.com/dotnet/aspnet:6.0
# install System.Drawing native dependencies
RUN apt-get update \
  && apt-get install -y --allow-unauthenticated \
  libc6-dev \
  libgdiplus \
  libx11-dev \
  gss-ntlmssp \
  && rm -rf /var/lib/apt/lists/*