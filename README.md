# LH-Sound-Config
Configurations and files for LH Poznan sound

## Config goals and settings
In a semi random order information on decisions taken when creating the patch lists and base shows

### Wing Rack
This is a rack mixer set at the stage. It's primary purpose is in ear monitoring.

#### Channel setup
- Channels 1-14 are instruments. 
- Channels 18-23 are microphones.
- Channels 28-38 are multitrack playback.
- Channels 39-40 are Talkback channels.
- Aux 1 is a mix of vocals from FOH, which can be useful for instrument players, so they always have lead singer loudest in their ear/have a good vocal mix in their monitor.
- Aux 2 & 3 are FOH playback channels (Pro Presenter content and Music)
- Aux 6-8 are FOH mains outputs. They are not meant to be mixed into ones ears. They are present as channels to allow for the Wing Rack Main output to go to speaker outs. In this case the channels and mains are mixed on the Matrixes. To prevent stage mix going to speakers the Wing rack mains are muted on startup.

#### Bus Setup
- Buses 1-14 are in ear monitor mixes
    - Buses 1-5 are set to stereo.
    - Remaining buses are set to mono
- Bus 15 is a Track mix so people don't need to set an individual mix of the track input
- Bus 16 is a Reverb in case one would like that in their monitor.

#### IO Setup
- Wing Rack provides 24 Combo inputs and 8 XLR outputs.
- AES A is connected to FOH console
- AES C is connected to a S16 Stagebox for 16 XLR inputs and 8 XLR outputs.
- iPad will be plugged into the Wing Rack USB port for multitrack input.
- AES/EBU output is used for PA output.

#### Processing
FX slots 14, 15, 16 are used as processors for PA, Front Fill and Sub outputs.

### Wing FOH
This is he Front of house mixer. It is responsible for sound in the auditorium and streams.

#### Channel setup
- Channels 1-14 are instruments. 
- Channels 17-22 are microphones.
- Channels 28-38 are multitrack playback.
- Channels 39-40 are Talkback channels.

#### Bus Setup
- Bus 1 is a drums group.
- Bus 2 is a track group. It is routed to dante card for recording.
- Bus 3 is a vocal group. It is routed to stage console for musicians to use in in ear mixes.
- Main 1 is used for PA output.
- Main 2 is used for Front Fill output.
- Main 3 is used for Sub output.
- Main 4 is used for livestream output.

#### IO Setup
- The wing provides 8 combo inputs, 8 line jack inputs, 8 XLR Outputs and 8 jack outputs.
- The wing will have an internal Dante card, which facilitates Presentation playback and multitrack recording.
- AES A is used to connect to the Wing Rack at stage. This connection is used for all audio communication between FOH and Stage.
- There is a usb interface available if a multitrack player was to be connected to the device.

#### Processing
There is no Default Fx selection as this is to be used to the liking of the sound engineer.