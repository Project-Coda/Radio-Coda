# Radio Coda

This repository documents the infrastructure of the Radio Coda project.

Radio Coda consists of 4 main components:
1. Azuracast
2. Radio Coda Discord Bot
3. Radio Coda Stream
4. Radio Coda Stream Utilities

# Diagram

Coming Soon

# Azuracast

Azuracast is a free, open-source, radio station streaming service.
It is responsible for providing the audio stream and Now Playing information to
Radio Coda.

# Radio Coda Discord Bot

The Radio Coda Discord Bot is responsible for providing the audio streams from
Azuracast to the Discord server. as well as providing the Now Playing information in
the status of the bot.

# Radio Coda Stream

The Radio Coda Stream container is responsible for taking the audio stream from
Azuracast and combining it with a video stream to stream to YouTube as well as
displaying Now Playing Information.

# Radio Coda Stream Utilities

The Radio Coda Stream Utilities container is responsible for providing the
Now Playing information to the Radio Coda Stream container as well as the
YouTube Chat.