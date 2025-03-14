# Operating Systems Scripts

This repository contains a collection of **bash scripts** designed to automate various tasks. These scripts are useful for file management, searching, and photo conversion. Below is an overview of the scripts and their functionalities.

---

## Scripts

### 1. **Remove Duplicates from FTP Files**
- **Description**: This script removes duplicate files from FTP directories.
- **Usage**: 
  ```bash
  ./remove_duplicates_ftp.sh
  ```
- **Notes**: Ensure you have the necessary permissions to access and modify the FTP directory.

---

### 2. **Search through Files by Several Filters**
- **Description**: This script allows you to search through files based on several filters, such as file type, size, and modification date.
- **Usage**: 
  ```bash
  ./search_files_filters.sh
  ```

---

### 3. **Search through Files by Several Filters with Zenity**
- **Description**: This script provides a **user interface** using **Zenity** to search through files based on several filters. It is more user-friendly than the command-line version.
- **Usage**: 
  ```bash
  ./search_files_zenity.sh
  ```
- **Dependencies**: Zenity must be installed on your system.
- **Install Zenity** (if not already installed):
  ```bash
  sudo apt-get install zenity
  ```

---

### 4. **Photo Converter**
- **Description**: This script converts photos between different formats:
  - JPG to PNG
  - PNG to JPG
  - HEIC to JPG
  - HEIC to PNG
  - WEBP to JPG
- **Usage**: 
  ```bash
  ./photo_converter.sh
  ```
- **Example**: 
  ```bash
  ./photo_converter.sh --input image.heic --output image.jpg --format jpg
  ```
- **Dependencies**: ImageMagick must be installed on your system.
- **Install ImageMagick** (if not already installed):
  ```bash
  sudo apt-get install imagemagick
  ```

---

## Getting Started

### Prerequisites

- A Linux-based operating system.
- Bash shell.
- Required dependencies (e.g., Zenity, ImageMagick).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/m-sadkowski/Operating-Systems-scripts.git
   cd Operating-Systems-scripts
   ```

2. Adjust permissions for the scripts:
   ```bash
   chmod +x remove_duplicates_ftp.sh
   chmod +x search_files_filters.sh
   chmod +x search_files_zenity.sh
   chmod +x photo_converter.sh
   ```

3. Run the desired script:
   ```bash
   ./script_name.sh
   ```

---

## Notes

- **Permissions**: Ensure you have the necessary permissions to execute the scripts and access the files/directories they interact with.
- **Dependencies**: Some scripts require additional tools like Zenity or ImageMagick. Install them as needed.
- **Customization**: Modify the scripts as needed to suit your specific use case.

---

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Built as a collection of utility scripts for operating systems tasks.
- Inspired by the need for automation in file management and photo conversion.

---

## Contact

For questions or feedback, please reach out to [m-sadkowski](https://github.com/m-sadkowski).

---

Enjoy automating your tasks with these scripts! 🚀