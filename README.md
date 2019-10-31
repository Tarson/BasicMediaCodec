# BasicMediaCodec

This application is used for striming video from Android device
by udp channel to target computer to UDP port 40002.
Based on Camera2 API and Surface conception of Android Marshmallow.
You can play it in VLC player on computer with key:
C:\Program Files\VideoLAN\VLC\vlc udp://@:40002   --demux h264 --video-filter=transform --transform-type=90
but note that VLC should be 2.2.6 Umbrella
newer version Vetinary removed udp protocol from API.
