# Music Genre Classifier

A Python-based application that classifies music genres by analyzing audio files, lyrics, and cover images. This multi-modal approach leverages audio signal processing, natural language processing, and image analysis to enhance genre classification accuracy.

## Project Structure

* `main.py`: Entry point of the application.
* `audio_processor.py`: Processes audio files to extract features.
* `lyrics_processor.py`: Analyzes lyrics using NLP techniques.
* `image_processor.py`: Processes album cover images.
* `genre_classifier.py`: Implements the genre classification logic.
* `download_nltk.py`: Downloads necessary NLTK resources.
* `sample_files/`: Contains sample audio, lyrics, and image files.
* `temp_audio.mp3`, `temp_lyrics.txt`, `temp_cover.jpg`: Temporary files used during processing.
* `.idea/`, `__pycache__/`: IDE and cache directories.([GitHub][1])

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Mohana-Sree/Music-Genre-Classifier.git
   cd Music-Genre-Classifier
   ```



2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```



4. **Download NLTK resources:**

   ```bash
   python download_nltk.py
   ```



## Usage

1. **Prepare your input files:**

   * **Audio file:** Ensure it's in `.mp3` format.
   * **Lyrics file:** Plain text file (`.txt`) containing the song lyrics.
   * **Cover image:** Image file (`.jpg`, `.png`, etc.) of the album cover.

   Place these files in the `sample_files/` directory or update the paths accordingly in `main.py`.

2. **Run the application:**

   ```bash
   python main.py
   ```



The application will process the inputs and output the predicted music genre.

## Sample Files

The `sample_files/` directory contains example files:

* `temp_audio.mp3`: Sample audio file.
* `temp_lyrics.txt`: Sample lyrics.
* `temp_cover.jpg`: Sample album cover image.([arXiv][2], [GitHub][3])

These can be used to test the application's functionality.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact [Mohana-Sree](https://github.com/Mohana-Sree).
