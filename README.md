# Docker Twitch Chat Downloader
A Docker image for PetterKraabol/Twitch-Chat-Downloader.

## Usage
```
docker run -it -v "$HOME/.config/Twitch-Chat-Downloader/:/config/" -v "$(pwd):/mnt/" chrisgavin/twitch-chat-downloader 125936523
```
