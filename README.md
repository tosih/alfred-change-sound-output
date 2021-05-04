# alfred-change-sound-output

Change your sound output using alfred!!

### Requirements:
- [jq](https://github.com/stedolan/jq)
- [SwitchAudioSource](https://github.com/deweller/switchaudio-osx)

To install dependencies:

    brew install jq switchaudio-osx

### Build:

To build, just run the following command:

    make

which basically does:

    cd alfred-change-sound-output
    zip change_shound_output.alfredworkflow *
    open change_shound_output.alfredworkflow
