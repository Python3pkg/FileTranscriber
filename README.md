FileTranscriber
===============

A small utility that simulates user typing to aid plaintext file transcription
in limited environments

Usage:
    transcribe <file> [--interval=<time>]
    transcribe (--help | --version)

Options:
    -i --interval=<time>  Interval between keystrokes (in seconds). Typing too
                          quickly may break applications processing the
                          keystrokes. [default: 0.1]
    -p --pause=<time>     How long the script should wait before starting (in
                          seconds). Increase this if you need more time to enter
                          the typing field. [default: 5]

What it does
------------

Sometimes you find yourself unable to copy text data into a field or application
but you *could* type it all in by hand... what a hassle.

Let this do tedious work and avoid typos.

When you launch this script, you give it the location of a file and (optionally)
an interval between keystrokes to control the rate of typing. It will then ask
you to press "Enter" when you are ready for it to begin typing. It will pause
for a bit (default is 5 s) time to allow you to make sure your typing field has
focus. After the pause, it will begin typing. To cancel at any time, click any
mouse button.

