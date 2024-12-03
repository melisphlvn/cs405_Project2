# cs405_Project2
CS 405 Project 2: Texture + Illumination
Project Overview
This project is designed to implement texture and illumination techniques for rendering 3D model meshes. The project consists of three main tasks, with a fourth optional bonus task.

By completing all tasks, you will achieve full points. The tasks involve modifying the project2.js file to enable texture support, basic lighting, and additional features for rendering. Important: Submissions modifying files other than project2.js will not be graded.

Project Contents
After downloading the assignment content, the following files and folders will be available:

project2.html: The main HTML file to run the project.
project2.js: The JavaScript file to modify for completing tasks.
obj.js: A helper script for rendering 3D models.
resources/: A folder containing texture and model files, such as leaves.jpg.
When you open project2.html in a browser, you will see a screen where you can upload 3D model meshes and texture data to render them on your screen.

Tasks
Task 1: Modify setTexture Method (30 points)
Objective:
Enhance the setTexture method in project2.js to support textures of any dimensions.

Current Implementation Issue:
The method currently accepts textures with dimensions that are powers of two. You need to update the implementation to support textures of any size.

Testing:

Use leaves.jpg from the resources folder to verify your implementation.
Ensure all textures, regardless of size, render correctly on the 3D model.
Task 2: Implement Basic Lighting (40 points)
Objective:
Implement basic lighting features, including ambient light and diffuse light, for the scene.

Steps to Complete:

Modify the following methods in project2.js:
constructor
setMesh
draw
enableLighting
setAmbientLight
Update the fragment shader (meshFS) to correctly render the lighting effects.
Expected Results:

Without lighting: The model appears flat and unlit.
With lighting: The model exhibits realistic light effects, as shown in the example images provided.
Additional Requirements:

Add functionality to adjust the ambient light density using the slider labeled Ambient Light Density.
Implement arrow keys to change the light’s position dynamically in the scene.
Testing:

Verify the lighting changes dynamically as you adjust the slider or use arrow keys.
Confirm the ambient and diffuse lighting effects visually.
Instructions to Run the Project
Clone the repository:
bash
Kodu kopyala
git clone https://github.com/your-username/your-repository.git
Open the folder in your editor.
Open the project2.html file in your preferred browser.
Test your modifications by uploading models and textures using the provided UI.
Bonus Task
If applicable, details about the bonus task can be added here.

Contribution
Feel free to fork this repository and contribute! You can submit a pull request with improvements or report any issues.

License
This project is for educational purposes as part of CS 405 coursework.


