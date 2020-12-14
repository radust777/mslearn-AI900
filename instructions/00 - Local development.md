## Local Development 

If you are working on your local computer, you can follow these steps to configure your environment to work with the labs. 

### Edge 
1. Install [Edge (Chromium)](https://www.microsoft.com/edge) 

### C++ Redistributable 
1. Download and install the [Visual C++ Redistributable (x64)](https://aka.ms/vs/16/release/vc_redist.x64.exe) 

### Python and required packages 
1. Install Python 3.6.1 because the Speech package is not compatible with Python 3.8.  
   - **Important**: Select the options to add Python to the PATH variable and to register as the default Python environment 
2. After installation, open Command Prompt and enter the following command to install the necessary packages: 

> pip install ipython jupyter matplotlib pillow requests azure-cognitiveservices-vision-computervision azure-cognitiveservices-vision-customvision azure-cognitiveservices-vision-face azure-cognitiveservices-language-textanalytics azure.cognitiveservices.speech azure_ai_formrecognizer 

### Visual Studio Code 
1. Download and open [Visual Studio Code](https://code.visualstudio.com/Download). After installation, start Visual Studio Code and on the Extensions tab (CTRL+SHIFT+X), search for and install the **Python** extension from Microsoft

2. In Visual STudio Code, go to *Terminal*, go to *New Terminal*, type **git clone https://github.com/MicrosoftLearning/mslearn-ai900** and press *enter*. Cloning the project allows you to save your work on your local computer. 

