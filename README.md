## alfred-change-sound-output

Change your sound output using alfred!!

### Requirements:
- [jq](https://github.com/stedolan/jq) ( `brew install jq` )
- [SwitchAudioSource](https://github.com/deweller/switchaudio-osx) ( `brew install switchaudio-osx` )

### Build:

To build, just run the following command:

    ```bash
    make
    ```

which basically does:

    ```bash
    cd alfred-change-sound-output
    zip change_shound_output.alfredworkflow *
    open change_shound_output.alfredworkflow
    ```
