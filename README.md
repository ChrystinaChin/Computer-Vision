# Computer-Vision
This repository contains two main components: an implementation of **Neural Style Transfer** (using deep learning to apply artistic styles to images) and a interactive **Character Frequency Analyzer** script.
---

## 1. Neural Style Transfer

### Overview
Neural Style Transfer (NST) is a computer vision technique that blends two images: a **Content Image** (e.g., a photograph) and a **Style Reference Image** (e.g., a famous painting), combining them so the output image looks like the content photo painted in the style of the reference image.

* **Content Image**: <br> <img height="220" alt="content" src="https://github.com/user-attachments/assets/731ea6a8-0274-40e9-9dfc-6fe079841a56" />
* **Style Image**: *(Vincent van Gogh's The Starry Night)* <br> <img height="220" alt="style" src="https://github.com/user-attachments/assets/9d7d67be-1594-4d57-9a19-33ebbfc0365e" />
* **Output Image**: *(Combined stylized artwork)* <br> <img height="220" alt="final" src="https://github.com/user-attachments/assets/683f6deb-2006-4e39-91b0-15010d2ef65b" />

### Results
The project takes a content image and transfers the texture, color palette, and brushstroke style of the style reference image onto it while preserving the structural details of the content.


---

## 2. Character Frequency Analyzer

### Features
A CLI Python utility that analyzes text input or file contents to compute character frequencies and display visual ASCII histograms.

- **Option (a)**: Calculates character frequencies directly from a user-input string.
- **Option (b)**: Reads a `.txt` file and computes character frequencies across the entire file.
- **Option (c)**: Displays a visual asterisk (`*`) histogram corresponding to character occurrences.
