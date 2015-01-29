# Dimension-Z-AudioEffect-Reaktor

### About: ###
* Dimension-Z is a loose emulation of Roland "motionless" line of chorus effect
* Dim-Z also has delay and feedback for early-Lexicon like effects

### Status: ###
* now longer actively developed but rather just put here as an archive
* tested on a Mac with Reaktor v5.9

### Known Issues: ###
1) High feedback settings can sometime spiral out of control the output volume. Eventually I will add some overload protection but for now, be warned to turn up feedback SLOWLY until you find the right setting.

2) Drastically adjusting pitch or delay controls will produce unwanted sounds until the new setting is allowed to stabilize. This is particularly true when changing preset that use vastly different settings. Eventually I will implement something like a cross fade to hide this.

3) The entire effect needs time to fill it’s buffers before the effect will produce desired results. This usually only means a few ms. It’s advised to have a lead in before using the effect to avoid this. This problem cannot ever be fully remedied, although there are some compromises I intend on trying out.

4) I do not own any of the Roland equipment emulated by some of this effect’s presets. Therefore some of them might not be that accurate. I am working from documentation I have found on each device, most of which concerns the Dimension-D chorus. It’s safe to assume that those presets are the most accurate. 
