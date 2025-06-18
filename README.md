# Steganography: Hiding Text, Audio, and Video in Images

This project demonstrates steganography techniques to hide secret text, audio, or video files within an image. It ensures secure and imperceptible data embedding using Python-based methods.

## 📁 Project Structure
.
├── imgstegno.py # Script to hide/retrieve text in images


## 🧠 Methodology

- **Text Steganography**: Uses LSB (Least Significant Bit) encoding to embed characters into image pixels  
- **Audio/Video Steganography**: Frames/audio samples are embedded as pixel values using encoding algorithms  
- **Decoding**: Reverse extraction of hidden content without data loss  

## ⚙️ How to Run

1. Clone this repository  
2. Install required libraries: `pip install -r requirements.txt`  
3. Run the desired script:  
   - `imgstegno.py`  
4. Follow on-screen prompts to select input and output files  

## 🔐 Features

- Supports multiple file types (text, audio, video)  
- Lossless retrieval of hidden data  
- Minimal perceptual change in stego-images  

## 📚 References

- Concept of LSB encoding in image processing  
- OpenCV and NumPy for image handling  
- Python standard libraries for file I/O  

---

Contributions are welcome — feel free to fork and improve!
