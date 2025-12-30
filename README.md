# musicTranspositionWithCode

Using Python and the Librosa library to alter music's range, keys, etc.
Includes 3 music/sound files.


Welcome to the **Automatic Music Transposition Utilizing the Librosa Library Augmentations** project!  
my notebook provides an interactive environment for experimenting with various audio transformations—including transposition (key shifting), time stretching, and waveform analysis—leveraging the powerful [librosa](https://librosa.org/) Python library. You can upload your own sound clips or any popular songs loke blank space, visualize audio, and listen to augmented results in real time.



##  Features

- **Audio Loading & Playback:**  
  Easily upload and play back your own clips in the notebook with simple commands.

- **Waveform Visualization:**  
  See your audio visualized as a waveform to better understand changes after augmentation.

- **Pitch Shifting (Transposition):**  
  Shift the pitch of your audio up or down by any desired number of semitones, simulating transposition to a new key.

- **Time Stretching:**  
  Alter the speed (tempo) of your clip without affecting pitch, or combine this with pitch shifting for advanced effects.

- **Simple Interactive Interface:**  
  Designed for use in [Google Colab](https://colab.research.google.com/), making it easy for anyone to upload and experiment with their sounds.

---

##  Getting Started

**Requirements:**

- Python 3.6+
- [Librosa](https://pypi.org/project/librosa/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [IPython.display](https://ipython.readthedocs.io/en/stable/api/generated/IPython.display.html)
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)

**Run in Colab:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TheClassicTechno/musicTranspositionWithCode/blob/main/Automatic_Music_Transposition_Utilizing_the_Librosa_Library_Augmentations.ipynb)

---

##  How to Use

1. **Upload Your Audio File**  
   Place your audio file (e.g., `.wav`, `.mp3`, `.m4a`) in the Colab workspace (using the upload button or code).

2. **Set the Filename:**  
   In the notebook, edit the `filename` variable to match your uploaded file name.

   ```python
   filename = "your_audio_file.m4a"
   ```

3. **Run the Notebook Cells:**  
   Execute each cell from top to bottom.  
   - The notebook will load and display the waveform of your audio.
   - Apply effects like time-stretching or pitch-shifting as shown in the sample code cells.

4. **Listen and Visualize:**  
   The altered audio can be played directly in the notebook, and waveforms/plots are generated automatically.

---

## License

This project is distributed under the MIT License.  
See [LICENSE](LICENSE) for details.

