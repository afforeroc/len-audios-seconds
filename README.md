# Total lenght of all mp3 audios in seconds
Bash script to calculate total length of all mp3 audios in seconds using `ffmpeg` and `bc`.

## System requeriments
* Ubuntu 20.04 LTS

### 1. Install neccessary software
Install `ffmpeg` and `bc` software.
```
$ sudo apt-get install ffmpeg bc
```

### 2. Run the script
Delete the `deleteme` file. Put the script outside the folder that contains audio files. Run the script adding as argument the mentioned folder.
```
$ sh len_audios.sh audios/
```

### 3. Output
e.g.
```
Reading all audio files from 'audios/' folder ...
audios/01 Our Love Is Here To Stay.mp3 => 259.134694
audios/02 Desafinado.mp3 => 218.514286
audios/03 Someday My Prince Will Come.mp3 => 258.324898
audios/04 Twenty Four Hours A Day.mp3 => 167.627755
audios/05 My Baby Just Cares For Me.mp3 => 197.773061
audios/06 How Intensitive.mp3 => 280.372245
audios/07 Dizzy Atmosphere.mp3 => 193.906939
audios/08 Body & Soul.mp3 => 290.089796
audios/09 Crazy He Calls Me.mp3 => 219.036735
audios/10 Lullaby Of Birdland.mp3 => 256.026122
audios/11 Hallelujah.mp3 => 196.911020
audios/12 I Can't Believe You're In Love With Me.mp3 => 308.271020
2845.988571
```

## Reference links
* [Stack Overflow - Calculate length of all mp3 files in one folder](https://stackoverflow.com/questions/45535938/bash-calculate-length-of-all-mp3-files-in-one-folder)
* [Stack Overflow - How to get the list of files in a directory in a shell script?](https://stackoverflow.com/questions/2437452/how-to-get-the-list-of-files-in-a-directory-in-a-shell-script)

## Documentation links
* [FFmpeg](https://ffmpeg.org/)
* [GNU - bc](https://www.gnu.org/software/bc/)
