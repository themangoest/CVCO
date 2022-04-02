# CVCO

Power supply: 29mA

knob1: Root frequency
knob2: Inversion
knob3: Chord / Wave
CV1: Inversion
CV2: Chord
V / oct (10bit, 5Vp-p), Root frequency is controlled.
The output is 4Vp-p.

# "Inversion" A
turn is to change the pitch of the constituent notes.
For example, in the case of C code, the basic form is CEG. When this is turned around, it becomes EGC and GCE.
Knob2 is divided into 16 parts, and 1 to 8 on the left half select the 7th inversion type from the basic type. The right half 9 to 16 can also be selected from the basic type to the 7th inversion type, and the root note is output at the same time. By outputting the root note, it leaves a feeling of pitch that is easily lost due to turning.

# "Chord"
Select 8 types of chords. From the left of Knob3, it is Maj, Maj7, Maj add9, sus2, min add9, min7, min, octave.
The point is that sus2 is between maj and min. sus2 is neither major nor minor, but it is a chord with a unique tension. Turn the knob to make the timing of switching from major to minor natural.

# "Wave"
Knob2 turns all the way to the right, you can change the waveform by turning Knob3. You can choose from eight types, and each waveform is a wavetable that is included in the mozzi library from the beginning.
With a little modification, you can play it on your favorite wavetable.

Inspired by Hagiwo and Chords
