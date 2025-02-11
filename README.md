# noelTexturesPy
Dash app to generate textures maps from MRI using Advanced Normalization Tools ([ANTsPy](https://antspy.readthedocs.io/en/latest/))
<hr>

## Prerequisites
- [Docker](https://www.docker.com/get-started)

OS specific installation instructions: https://github.com/NOEL-MNI/noelTexturesPy/wiki/Installation

![Usage noelTexturesPy GIF](images/textures.gif)



## Run the app
```bash
docker pull noelmni/pynoel-gui-app:latest
docker run --rm -p 9999:9999 noelmni/pynoel-gui-app:latest
```

Access the GUI at http://localhost:9999

## Required inputs
Please ensure the file(s) are renamed accordingly before uploading it to `noelTexturesPy`.
```
- T1-weighted image must include the string “t1” or “T1” in its filename, and/or
- T2-weighted (or FLAIR) image must include either “t2”, “T2”, “flair”, or “FLAIR”
```

<hr>

![](/images/noelTexturesPyDemo.png?raw=true)
