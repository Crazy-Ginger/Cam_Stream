# Camera_Stream
A bash bash script that streams a given camera to twitch

1 argument: stream key passed (afer running the command)

Defaults to `/dev/video0` as input device (change accordingly)

Uses [v4l2](https://github.com/torvalds/linux/tree/master/drivers/media/v4l2-core) for camera support and [ffmpeg](https://www.ffmpeg.org/) to stream the video

(I've removed most audio options, add them back accordingly)

This script is taken from [Arch Wiki](https://wiki.archlinux.org/index.php/Streaming_to_twitch.tv#Shell_script_method) and modified for my use
