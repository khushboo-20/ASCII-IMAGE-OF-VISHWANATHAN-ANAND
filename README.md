 ASCII Art Generator

 Project Purpose

This project converts a digital image into **ASCII art**, which is a text-based visual representation created using standard keyboard characters. The main objective is to demonstrate how image processing concepts—such as resizing, grayscale conversion, and pixel intensity mapping—can be applied in Python to produce creative, terminal-friendly artwork.

The project is suitable for academic submissions, learning image processing basics, and showcasing how raw pixel data can be translated into meaningful visual output using characters.

 How the Code Works

The program follows a clear pipeline to transform an image into ASCII art:

 1. Image Input

* An image is loaded (either uploaded in Google Colab or read locally).
* The **Pillow (PIL)** library is used to handle image operations.

 2. Image Resizing

* The image is resized to a fixed width.
* Height is adjusted proportionally to maintain the aspect ratio so the ASCII output does not appear distorted.

 3. Grayscale Conversion

* The resized image is converted to grayscale.
* Each pixel is reduced to a single intensity value ranging from 0 (black) to 255 (white).

 4. ASCII Character Mapping

* A predefined set of ASCII characters ordered by visual density is used, for example:

  ```
  @%#*+=-:. 
  ```
* Darker pixels are mapped to denser characters (such as `@` or `#`), while lighter pixels are mapped to lighter characters (such as `.` or space).

 5. ASCII Art Generation

* Each pixel is converted into its corresponding ASCII character.
* Characters are arranged row by row based on the image width.
* Line breaks are added to form the complete ASCII image.

 6. Output Display

* The final ASCII art is printed directly in the output cell or terminal.


 How to Run the Program

 Using Google Colab 

1. Open **Google Colab**
2. Upload the provided `.ipynb` file
3. Run the notebook cells sequentially
4. Upload the image when prompted
5. View the generated ASCII art in the output



 Technologies Used

* Python
* Pillow (PIL)
* Google Colab (optional)

 Conclusion

This project demonstrates how images can be transformed into ASCII art using Python. It combines basic image processing techniques with creative visualization, making it a practical and engaging example of applying programming concepts to real-world data.
