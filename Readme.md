
# An esoteric text-based midi controller

* Inspired by Orca (https://github.com/hundredrabbits/Orca) and the simplicity and beauty of the way in which my toddler understood pitch as a simple line on a piece of paper.

# Current status

* It needs a DAW or Synth connected via midi.
* It is still a work in progress. Not fully functional and right now I am not focus on the project. 

So feel free to test it and improve it by submitting a pull request :) 

# Run

In Phej dir:

```
npm install -g http-server
http-server
```

# Create Electron native app

1. You need to upload the project to an online http server (ej. http://domain.com/phej_folder).

1. Execute:

```
npm install -g nativefier
nativefier --hide-window-frame --width 700 --width 600 http://domain.com/phej_folder
```

# Extend

Add your own plugins to the dir `js/plugins` following the same structure that is displayed in `js/plugins/test.js`.

# Create your own programs in Phej

You can download your programs directly from `Phej` clicking in the download button.
If you save them in the `programs` folder you will be also able to load them directly in the browser.

For example, if your program is stored in `001.phej` you can load it by typing:

```
http://<server:port>/#@<program_file_name>
```

Some programs are included by default: `http://localhost:8080/#@001`

 phej://wiki.xmunch.com/phej/#@001


