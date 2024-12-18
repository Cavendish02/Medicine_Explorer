# Medicine Explorer

Medicine Explorer is a Python-based desktop application that allows users to scan, decode, and retrieve detailed information about medicines using barcodes. It features a user-friendly interface and integrates with an Excel dataset for displaying comprehensive medicine details such as composition, usage, dosage, side effects, and interactions.

---

## Features

- **Real-Time Barcode Scanning:** Leverages your device's camera to scan barcodes and fetch related medicine details instantly.
- **Image Upload:** Allows users to upload images containing barcodes for decoding.
- **Detailed Medicine Information:** Displays medicine data, including:
  - Name
  - Composition
  - Usage recommendations
  - Dosage
  - Side effects
  - Interactions
- **Excel Dataset Integration:** Reads and retrieves medicine data from a local Excel file.
- **User-Friendly Interface:** Built with Tkinter for seamless interaction and functionality.

---

## Technologies Used

- **Python**: Core programming language.
- **Tkinter**: For the graphical user interface.
- **OpenCV**: For camera feed access and processing.
- **Pillow**: For image processing.
- **Pyzbar**: For decoding barcodes.
- **Pandas**: For dataset manipulation and queries.

---

## Installation

### Prerequisites
- Python 3.x installed on your system.
- Ensure the required libraries are installed (see `requirements.txt`).

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/medicine-explorer.git
   cd medicine-explorer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Update the dataset path in the script if necessary.
   ```python
   excel_file_path = "path/to/your/medicine_dataset.xlsx"
   ```
4. Run the application:
   ```bash
   python app.py
   ```

---

## Usage

1. **Start Scanning:** Use the "Start Scanning" button to activate the camera and scan barcodes in real time.
2. **Upload Image:** Use the "Upload Image" button to select an image file containing a barcode.
3. **View Details:** The decoded barcode will fetch data from the dataset and display it in the app.
4. **Rescan:** Reset the application for a new scan.
5. **Close:** Exit the application.

---

## File Structure

```
medicine-explorer/
├── app.py               # Main application script
├── requirements.txt     # Python dependencies
└── README.md            # Project description and usage instructions
```

---

## Future Enhancements

- Expand dataset for broader medicine coverage.
- Add QR code scanning capabilities.
- Integrate with an online API for real-time medicine data retrieval.
- Improve UI design and usability.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the terms of the license.

---

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve this project.
