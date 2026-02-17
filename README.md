# teleprompter
A simple web-based screen recorder that puts the script/text at the top of the screen near the webcam so that it looks like you are looking into the camera and not down or off to the side.

1. Open the web page. (You can do `python3 -m http.server 8000` or similar and then navigate to `http://localhost:8000` to ensure all the right security/accessiblity goodness vs. opening the file directly).
2. Upload a Word doc.
3. Start camera and choose your background.
4. Start/stop recording.

You'll get a .webm file which you can easily `ffmpeg -i` into your desired format.
