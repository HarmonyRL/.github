# HarmonyRL

Chord progressions for a melody. HarmonyRL writes chords under a melody, and can redraw only
the bars you choose while keeping the rest.

The models are transformer chord policies pretrained on human accompaniments from
[Hooktheory](https://www.hooktheory.com), then fine-tuned with reinforcement learning. They
come in 3 styles, from rich reharmonization to progressions close to the training data, and
are on [Hugging Face](https://huggingface.co/collections/CloudHolic/harmonyrl).

## Repositories

- [**HarmonyRL**](https://github.com/HarmonyRL/HarmonyRL): Python library that harmonizes lead
  sheets from MusicXML and MIDI files with the models.
