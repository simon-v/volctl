# volctl - a primitive volume control

Nothing like reinventing the wheel. Especially, if every other wheel has six-sides. Well, this one has seven.

Supported sound backends are ALSA and Pulseaudio; `volctl` automatically chooses the one that seems to be active at the moment.

__Basic usage:__

See the current volume: `volctl`

Mute or unmute the sound card: `volctl mute` and `volctl unmute`, or `volctl toggle` respectively.

Adjust the sound levels: `volctl VALUE`, or `volctl +VALUE` or `volctl -VALUE`.
