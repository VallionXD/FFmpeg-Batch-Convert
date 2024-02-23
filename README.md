# FFmpeg Batch Convert | Simple batch converting for ffmpeg.
> This guide also includes how to install ffmpeg & add to path!

See the section below to install ffmpeg.

### [FFmpeg]: *Download Links*
**FFmpeg Installation**: [hyperlink]()

**FFmpeg Batch Convert Installation**: [hyperlink]()

***NOTE***: This program as of *2024-02-22* only supports converting `.mkv` to `.mp3`!

### Requirements:
+ Python 3.10+ **(MUST BE ADDED TO PATH)**
+ Windows 10 or above. *(I dunno linux stuff -_-)*
+ 7Zip *(Extracting ffmpeg from archive)*
+ A working brain 😒 *(very rare)*

Last requirement is needed, if you don't meet it's requirements.. ***GET OUT OF HERE.***

## FFmpeg Intsallation | Documentation / Guide.
> Section on how to install and add ffmpeg to path.

The first step of this guide is very simple, download the ffmpeg files. The source of the build is from `gyan.dev/ffmpeg/builds`.

+ Full (Recommended): https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z
+ Essentials: https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-essentials.7z

After it is finished downloading, create a new file directory where you will put the insaller and the ffmpeg in.

When you complete that step, open the downloaded ffmpeg `.7z` file, open up the `bin` folder, and extract all of the executable files into your new folder. After this step your folder tree should look like below:

```text
FFmpeg
|-- ffmpeg.exe
|-- ffplay.exe
|-- ffprobe.exe
```

+ `ffmpeg.exe`: The main executable for ffmpeg, used for all of the file conversions.
+ `ffplay.exe`: FFmpeg's own multimedia playing program, useful for evaluating the converted files.
+ `ffprobe.exe`: Used to inspect mutlimedia files and extracting metadata.

 The next step is to download the python installer files, and put them in the same folder as the rest of the ffmpeg files. The download link for those is below.

Download: [Link will be here soon..]()

And once it's done, open the downloaded `.zip` files into the same folder as the ffmpeg files. Then your folder tree should look like below:

FFmpeg
|-- ffmpeg.exe
|-- ffplay.exe
|-- ffprobe.exe
|-- Install.py

Then all you need to do is run the `Installer.py` file as administrator, and after it finishes you are good to go, to the next section. Which is below!

## FFmpeg Batch Convert Installation | Documentation / Guide.
> Section on how to install ffmpeg batch convert.

***NOTE***: The `mkv` files you are trying to convert, and the FFmpeg Batch Convert files must be in the same folder. As of *2024-02-22* this applies to all versions.
