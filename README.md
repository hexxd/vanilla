# vanilla
Vanilla is a vocal harmonizer built entirely with native MaxMSP and MIDI, inspired by <a href="">this incredible performance of "Danny Boy" by Jacob Collier</a>.

It seemed a little backwards to me at the time (and in fairness still does) that Jacob Collier gets to have proprietary harmonizer made by the MIT Media Lab, but nobody else does. That's why vanilla is open source and completely free. 

The app is currently in alpha, so contributions are welcomed.
<br>
# Getting Started
### Configuration
1. For those who want to use MaxMSP, download the repository. If you don't own Max or are unfamiliar with it, you can also download the .app file <a href="https://www.dropbox.com/s/paugt8b0juc0lla/vanilla2.7.16.zip?dl=0" target="_blank">here</a>. There currently is no .exe version (if you own MaxMSP for Windows, become a contributor and compile one!).

2. Connect a USB MIDI keyboard, audio interface and microphone.

3. Make sure that the correct inputs and outputs are set in the application. If using Max, this can be set in the "Options > Audio Status" menu, or by pressing Command (⌘)-G in the application.
<br>

### Controls

#### Mixer Section

- The master volume output from the program is controlled by the fader on the right side.
- You can individually control levels for the "dry" voice (i.e. what you're actually singing into the microphone) and the "harm" voices, which are output by the program. Please note that these dials default to being all the way off (if you can't hear anything, that might be why).

#### Filter Section

- You can set how (if at all) you'd like the signal to be filtered here. There are nine filters to choose from, which can be selected by clicking the right dropdown.
- Center frequency, amplitude and Q for the filter can be adjusted using the dials.

#### Keyboard

- The keyboard will display what notes are being played via MIDI information.
- With that in mind, it's best not to click the keyboard. Doing so can cause notes to hang, and isn't very fun anyway.
<br>

### Common Bugs/Fixes

1. Make sure the driver is set to "Core Audio" in the audio status menu (see above).

2. Close any apps that use high amounts of processing power or RAM, such as Microsoft Word and Google Chrome.

3. Depending on the age and speed of your computer, it may be necessary to run the "scheduler in overdrive," a setting that can be accessed from the audio status menu.
