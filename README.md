# drone-chord-synth
desktop synth that generates chords with effects and sequencers

# Drone Chord Synth: Quick Manual

A short guide to each section of the synth, in the order they appear on the page. Tap a section title to collapse or
expand it.

## Chord indicator and Start button

The large display at the top shows the chord now sounding: its name, full name, notes and Roman numeral in the current
key and mode.

- **Start drone** begins the sound and **Stop** silences it, including any running progression or sequence.
- Choosing any chord also starts the drone. Your browser may need one tap before it allows sound.

## Key

A one-octave keyboard. Press a key to set the root for everything else.

- Black keys show both names, such as **C♯** and **D♭**.

## Mode

Choose **Ionian**, **Dorian**, **Phrygian**, **Lydian**, **Mixolydian**, **Aeolian** or **Locrian**. The chord row and
the progressions follow the mode.

## Chords in this key and mode

Choose **Fifths**, **Triads**, **Sevenths** or **Ninths**, then press one of the seven chords built on the scale.

- Each button shows its Roman numeral above its name.
- **Ionian** gives **I**, **IV** and **V** as major, and **Aeolian** gives **i**, **iv** and **v** as minor.

## Chord builder

Plays any chord quality on the selected key. The groups are:

- **Triads**: (major, minor, diminished)
- **Sus**, **augmented**, and **fifth**
- **Sevenths**: (maj7, m7, dominant 7, half-diminished, diminished 7, 7sus4)
- **Ninths**: (maj9, m9, dominant 9, m9♭5, dim9)

## Circle of fifths

- Press the **outer ring** for a major key (Ionian) or the **inner ring** for its relative minor (Aeolian).
- The current key and its neighbours are highlighted, and the centre shows the key signature.
- **Random key** jumps to a random key and plays its tonic chord.

## Common progressions

Pick a progression to load it in your key. It switches to a suitable mode, and its chords appear as buttons you can
press individually. Play progression steps through them automatically.

- **Seconds per chord** sets how long each chord lasts.
- **Invert** plays and lists the chords in reverse order.
- **Random order** plays each chord once in a shuffled order, then reshuffles.

## Step sequencer

Builds an 8-step chord pattern.

- Pick a chord above.
- Select a step and press **Set step** to current chord. The selection moves on to the next step.
- **Rest** makes a step silent.
- **Hold** keeps the previous chord sounding.
- **Fill from progression** loads the current progression across all 8 steps.
- **Clear all** empties them.
- Press **Play sequence** to loop the pattern.
  - The **Tempo slider** runs from 0 to 255 BPM with one step per beat.
  - At 0 the sequence pauses.

## Voice filter

Every note has its own filter. Choose:

- **Lowpass**, **Highpass**, **Bandpass**, or **Notch**
- Set the **cutoff** and **resonance**.

## LFO 1 and LFO 2

Two independent low-frequency oscillators that move the sound over time. Each has:

- A **shape**
- A **rate** from 0 to 20 Hz
- Three **depths**:
  - **Filter** (cutoff sweep)
  - **Pitch** (vibrato)
  - **Volume** (tremolo)

- All depths at 0 means no movement.
- A slow rate of **0.1 Hz** or less gives gradual drifting, and about **4 Hz** gives obvious tremolo or vibrato.

## Sound

- **Waveform**: sine, triangle, sawtooth or square
- **Octave**: the register of the chord
- **Voices per note** and **Detune**: thicken each note by stacking slightly detuned copies
- **Noise** and **Noise tightness**: a noise layer tuned to each chord tone. Higher tightness gives a narrower, more
tonal noise
- **Echo** and **Echo feedback**: the echo level and how long its repeats last
- **Glide**: how slowly one chord fades into the next
- **Reverb mix**, **size** and **damping**: the amount, length and darkness of the reverb
- **Volume**: the master level
- **Sub root**: adds the root note an octave lower

## Tips

- Start with a **slow glide** and a **lowpass filter** for a smooth drone, then add **LFO 1 filter depth** at a very
low rate.
- Raise **noise tightness** and **noise level** for a breathy, tonal texture.
- Use **Fill from progression** and **Hold steps** to make slow, evolving chord pads.
