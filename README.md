```markdown
# Image Viewer

## Overview
The Image Viewer project is a lightweight application designed to display images in various formats. It has a user-friendly interface allowing users to view their image collection easily. The project supports multiple image formats and provides basic image navigation functionalities.

## Features
- Supports various image formats: JPG, PNG, JPEG, GIF.
- Simple and intuitive interface to view images.
- Display images in a specified window size.
- Detect and respond to mouse events for future enhancements.

## Installation Instructions
To install and run the Image Viewer project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone [repository_url]
   ```
   Replace `[repository_url]` with the URL of the repository.

2. **Navigate to the Project Directory:**
   ```bash
   cd Image-Viewer
   ```

3. **Install Dependencies:**
   Ensure you have Python and the necessary libraries installed. You may need to install the `clutter` library. Use the appropriate package manager for your system. For most Linux distributions, `clutter` can be installed via:
   ```bash
   sudo apt-get install python-clutter
   ```

4. **Run the Application:**
   Execute the script to start the image viewer:
   ```bash
   python imageviewer.py
   ```

## Usage Examples
Once you have the application running, you can use it to view images contained in your directory.

### Basic Example
Open a terminal and run:
```bash
python imageviewer.py
```
The application will open a window of size 800x600 and display any supported image files in the current directory.

### Viewing Images
Navigate to the directory containing your image files, and run the script from there. The application will automatically detect and display the supported image files.

## Code Summary
The primary code file for this project is `imageviewer.py`.

- **Imports:**
  - `clutter`: Used for the graphical user interface and event handling.
  - `sys`, `os`, `glob`: Standard libraries for system operations and file handling.

- **Configuration:**
  - `x`, `y`: Variables defining the window size.
  - `formats`: A list of supported image formats.
  - `files`: An empty list to store image file paths.

- **Main Class (`playbutt`):**
  - `mouse(self, stage, event)`: A method to handle mouse events and print x/y coordinates.

## Contributing Guidelines
We welcome contributions to enhance the functionality and features of the Image Viewer. To contribute, please follow these steps:

1. **Fork the Repository:**
   Click on the 'Fork' button on the project repository page to create a copy of the repository in your GitHub account.

2. **Clone the Forked Repository:**
   ```bash
   git clone [your_forked_repo_url]
   ```

3. **Create a New Branch:**
   ```bash
   git checkout -b [branch_name]
   ```
   Replace `[branch_name]` with a descriptive name for your branch.

4. **Make Changes:**
   Implement the enhancements or bug fixes.

5. **Commit and Push:**
   ```bash
   git add .
   git commit -m "Description of the changes"
   git push origin [branch_name]
   ```

6. **Create a Pull Request:**
   Navigate to the original repository and click on 'New Pull Request'. Provide a detailed description of the changes you made.

## License
This project is licensed under the GPL license. For more information, please refer to the [GNU General Public License](http://www.gnu.org/licenses/licenses.html).
```

Feel free to modify the sections as per the additional details of your project.