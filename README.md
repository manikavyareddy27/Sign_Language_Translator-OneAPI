<h2 align=center>Intel oneAPI Sign Language Gesture Translator using MediaPipe</h2>

<p align="center">
  <img src=https://user-images.githubusercontent.com/106463633/230747827-b3db1985-59c8-4792-9af7-f8eca83a496f.png alt="Image Description">
</p>

   <p align=center> In this project, we will develop a Sign Gesture Language Translator using MediaPipe and the Intel OneAPI Platform. The translator will be able to recognize sign gestures captured from a video stream and convert them into corresponding text or spoken language.</p>
   
<p align="center">
  <img src=https://github.com/Er-AI-GK/oneAPI-Sign-Language-Translator/assets/106463633/17e5acfc-a037-446c-b990-98634c6c2fca alt="Image Description">
</p>


<h2 align=center> Prerequisites</h2>

Before getting started, make sure you have the following prerequisites installed:

- Intel OneAPI Base Toolkit
- Jupyter Lab ( Intel oneAPI 2023 ) Kernal
- MediaPipe
- TensorFlow
- Keras
- openCV

<h2 align=center>Installation</h2>

1. Install Intel oneAPI Kernal : 
 ```bash
   Cheatsheet.txt (Refer)
   ```
2. Install MediaPipe: Run the following command in your terminal to install MediaPipe using pip:

   ```bash
   !pip install mediapipe
   ```

3. Install Intel OneAPI Base Toolkit: Visit the Intel Developer Zone website (https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit.html) and follow the instructions to download and install the Intel OneAPI Base Toolkit for your operating system.

<h2 align=center>Usage</h2>

1. Clone the repository: Clone the project repository from GitHub using the following command:

   ```bash
   !git clone https://github.com/Er-AI-GK/oneAPI-Sign-Language-Gesture-Translator.git
   ```

2. Set up the environment: Open a terminal and navigate to the project directory. Activate the Intel OneAPI environment by running the following command:

   ```bash
   source <path-to-intel-oneapi>/setvars.sh
   ```

3. Run the translator: Execute the following command in the terminal to start the Sign Gesture Language Translator:

   ```bash
   SLT Main.ipynb
   ```

   The translator will launch and begin capturing video from your default camera.

4. Translate sign gestures: Make different sign gestures in front of the camera, and the translator will recognize them and display the corresponding text or spoken language output.

<p align="center">
  <img src=https://github.com/Er-AI-GK/oneAPI-Sign-Language-Gesture-Translator/assets/106463633/3f11693b-a712-4254-b95c-1da3efd40fcc alt="Image Description">
</p>

<h2 align=center>How I built it</h2>

1. First I Import libraries in Intel oneAPI kernal
2. Collect the dataset
3. Preprocess Function of the datasets
4. Create & Save Model
5. Finally, I deploy my model

<h2 align=center>Role of oneAPI DNN</h2>
In this project we used large amount of dataset so normally it's take long time process.

I choosed OneAPI DNN it's have optimized library and Python OneAPI kernal. So, it's give acceleration my project and gives high accuracy output. 

<p align="center">
  <img src=https://openbenchmarking.org/logos/pts_onednn.png alt="Image Description">
</p>
<h2 align=center>oneAPI Deep Neural Network Library (oneDNN)</h2>
oneAPI Deep Neural Network Library (oneDNN) is an open-source cross-platform
performance library of basic building blocks for deep learning applications.
oneDNN is part of [oneAPI](https://oneapi.io).
The library is optimized for Intel(R) Architecture Processors, Intel Graphics,
and Arm\* 64-bit Architecture (AArch64)-based processors. oneDNN has
experimental support for the following architectures: NVIDIA\* GPU,
AMD\* GPU, OpenPOWER\* Power ISA (PPC64), IBMz\* (s390x), and RISC-V.

oneDNN is intended for deep learning applications and framework
developers interested in improving application performance
on Intel CPUs and GPUs. Deep learning practitioners should use one of the
[applications enabled with oneDNN](#applications-enabled-with-onednn).

<h2 align=center>Contributing</h2>

If you want to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Implement your changes and make sure the code passes all tests.
4. Commit your changes and push them to your forked repository.
5. Submit a pull request to the main repository.

<h2 align=center>License</h2>
This project is licensed under the MIT License. See the `LICENSE` file for more information.

<h2 align=center>Acknowledgments</h2>
We would like to thank the developers of MediaPipe and the Intel OneAPI Platform for their excellent tools and resources that made this project possible.

<h2 align=center>References</h2>
- Intel OneAPI Platform documentation: https://devcloud.intel.com/oneapi/get_started/
- MediaPipe documentation: https://google.github.io/mediapipe/

 <h2 align=center>Intel DevMesh Profile</h2>
https://devmesh.intel.com/users/gopalakrishnan-d

 <h2 align=center>Intel DevMesh Projects</h2>
 
- Intel oneAPI : Sign Language Gesture Translator => https://devmesh.intel.com/projects/oneapi-sign-language-translator 

- Intel oneAPI : Emotion Recogniton using NLP => https://devmesh.intel.com/projects/intel-oneapi-based-emotion-recognition-using-nlp-audio-text

## Get Start Your Intel oneAPI project 
==> https://devcloud.intel.com/oneapi/
==> www.oneapi.io/open-source/
