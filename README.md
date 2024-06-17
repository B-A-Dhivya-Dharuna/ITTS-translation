# Real-time Reading Assistance to the Visually Impaired and Dyslexic individuals using Image-to-Text-Speech (ITTS) translation
### by B A Dhivya Dharuna

## Project Overview

With advancements in technology, the conversion of text from images into speech and its translation has become increasingly prevalent. Our project aims to leverage advanced technological tools to assist individuals with visual impairments and dyslexia.

## Technology Stack

- Python
- OpenCV (Computer Vision 2 - cv2)
- Matplotlib
- Pytesseract
- pyttsx3
- python-docx
- SpellChecker
- GoogleTranslator
- gTTs
- os library

## Image Processing Workflow

1. **Opening the Image (OI)**
   - Utilize Quadtrees to open and process the image in the IDE.

2. **Image Pre-processing (IP)**
   - Inversion: Invert pixel colors.
   - Binarization: Convert to black and white pixels.
   - Dilation and Erosion: Expand and shrink shapes.
   - Threshold Adjustment: Remove unnecessary borders.
   - Noise Removal: Enhance image clarity by reducing pixel noise.
   - Conversion to Text: Use Pytesseract library to convert the processed image into text.

3. **Character Segmentation (CS)**
   - Analyze horizontal and vertical components and contours to segment characters.

4. **Character Recognition (CR)**
   - Match patterns with predefined templates or patterns stored in a database/library.

## Text-to-Speech Conversion

- **python-docx:** Create a Microsoft Word document to store the converted text for text-to-speech conversion.
- **pyttsx3:** Utilize system's default text-to-speech capabilities to convert text into speech with high-quality output.

## Language Translation

- **SpellChecker:** Perform spell checks on English texts.
- **GoogleTranslator:** Translate English texts into any desired language.
- **gTTs (Google Text-to-Speech):** Generate speech output in the desired language using the operating system's interface.

## Conclusion

Our project aims to enhance accessibility for individuals with visual impairments and dyslexia by leveraging advanced image processing and text-to-speech technologies. Future enhancements could include real-time image processing and support for additional languages.
