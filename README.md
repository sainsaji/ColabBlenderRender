# Cloud Blender Rendering Using Google Collab 🚀

Welcome to the Cloud Blender Rendering Using Google Collab! This script is designed to automate various tasks related to Blender, such as rendering, code execution, and more. This README provides an overview of the script's functionality and how to use it effectively.

## Prerequisites [If to be done manually, Not all Required] 🛠️

Before using the script, make sure you have completed the following steps:

1. Download Blender 3.5.1:
   ```bash
   wget https://download.blender.org/release/Blender3.5/blender-3.5.1-linux-x64.tar.xz
   ```

2. Run One-Time Prerequisites (for Google Colab):
   ```python
   # Install required packages
   !pip install google-colab ipywidgets tqdm pillow

   # Copy Blender archive to the Drive
   !cp /content/blender-3.5.1-linux-x64.tar.xz  /content/drive/MyDrive/Blender/blender-3.5.1-linux-x64.tar.xz
   ```

3. Install Blender and Set Up Environment:
   ```python
   # Extract Blender archive
   !tar xf /content/drive/MyDrive/Blender/blender-3.5.1-linux-x64.tar.xz

   # Set up environment
   !cp /content/drive/MyDrive/Blender/blender-3.5.1-linux-x64/blender /usr/local/bin/
   ```
4. Connect Google Drive

- This will be done while running "Run OneTime Prerequisite Button"
- Click "Run One Time Prerequirements" to perform this step.

5. One-Time Prerequisites

- Will Copy neccessary files to Google Drive and Extarct them, It will automatically create the folders for you.
- Click "Run One Time Prerequirements" to perform this step.
## Features and Usage 📝

### 1. Upload and Manage .blend Files

- Use the "Upload .blend file" button to upload Blender files.
- Click "Refresh Files" to update the list of available .blend files.

### 2. Configure Rendering Settings

- Select a .blend file from the dropdown.
- Adjust the number of samples, width, and height for rendering.

### 3. Execute Code and Render

- Write code to modify the selected .blend file for rendering.
- Click "Render" to execute the code and render the scene.
- Choose the rendering device (CUDA or CPU) using the dropdown.


## How to Use 📖

1. Click on "One time Prerequisites Button.
2. Click on "Run Requirements".
3. Click on "Install Blender".
4. Upload your .blend file using the "Upload .blend file" button.
5. Configure the rendering settings as needed.
6. Write code to modify the scene parameters in the code section.
7. Click "Render" to execute the code and render the scene.
8. You can select either CUDA or CPU for rendering.

## Notes 📝

- This script is designed to be used in Google Colab.
- Make sure to complete the prerequisites before running the script.
- The rendering process may take some time; be patient.

## Support and Contributions 🤝

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/your-username/your-repo-name).

---

Happy Blendering! 🎨🎉
