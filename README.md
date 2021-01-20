![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)
# LocalTV
A super light template for creating your own TV station!

1. Fork this repo
2. Clone or download.
3. Change "Springfield" to the name of your community. Unless you live in Springfield.
4. Do what you want with the tagline.
5. Go to [api.video](api.video) and click "Sign up for free". 
6. Click "My live stream".
7. Choose a name for your stream. This **will** be visible to your viewers. Choose wisely (you can change this later).
8. You will be magically transported to a dashboard! Click on your livestream.
9. On the right panel under the embed code you will see a link that looks like the link in the iframe in index.html. Clicl "copy link" and replace the placeholder link with your custom link.
10. On the current screen you can also set a thumbnail that viewers will see whenever you are not actively streaming. Don't close this tab.

That's it for the UI! It's only this single index.html file. To try it out quicly you can just zip the index.html file and drop it into [tiiny.host](tiiny.host). Start sharing your TV station far and wide!

To Start a Stream
=================

1. Download [OBS](https://obsproject.com/)
2. Esablish a source. In the sources section, choose a video feed to share. You could choose to share your screen, or to share your camera (on a Mac: Video Capture Device, and then in the "Device" dropdown choose the camera). You should now see the video source in the main OBS window.
3. Connect OBS to api.video. Under Settings, choose Stream. You'll see a choice for service - choose custom.
4. The server should be “rtmp://broadcast.api.video/s" and the streamKey is available on the page of your live stream on api.video (the page you are currently on, unless you didn't listen and closed it). Click OK to accept the changes.
5. Press Start Streaming.
6. Be you excellent self! Cheer up your whole neighborhood and possibly the world!
