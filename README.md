# Data Analyzer MFC App
![GitHub Repo stars](https://img.shields.io/github/stars/EmonRezaBD/Data-Analyzer) ![GitHub repo size](https://img.shields.io/github/repo-size/EmonRezaBD/Data-Analyzer?color=red) 
Initial UI            |  Final UI
:-------------------------:|:-------------------------:
![Fig. 1](https://github.com/EmonRezaBD/Data-Analyzer/blob/main/InitialView.PNG)  |  ![Fig. 2](https://github.com/EmonRezaBD/Data-Analyzer/blob/main/FinalView.PNG)

## :blue_book: App Description
This app is developed to get a good grasp on MFC C++ framework. All the basic features and their fully functional implementation can be found here. This repo can be helpful for the beginners of MFC C++.
Features of this app-
* Load file : A button to load a CSV file 
* Tab control: For creating different tabs for specific purpose
* Tree control: For showing the headers of the CSV as a tree view
* List control: Showing all the data columns wise as present in CSV file
* Context menu: For selecting specific 02 columns
* Chart control: To create and display the chart created from the selected 02 columns through context menu
* Export data: To export data of selected 02 columns through context menu in a new CSV file
* Export pdf: To export data and write in PDF file in any format ex. table, plain text, etc.

## :file_folder: Table of Contents 
* <code>[ChartCtrl](ChartCtrl)</code> : Chart Control Library is used to generate 2D graphs in MFC. This library is designed for MFC C++.
* <code>[Debug](Debug) </code> : Debugging object files
* <code>[libharu_x86-windows](libharu_x86-windows)</code> : Libharu library is used for building PDF from scratch in MFC
* <code>[libpng_x86-windows](libpng_x86-windows) </code> : For PDF building in MFC. Both of the folder is needed
* <code> [res](res)</code> : Used resource files in this app. contains all the buttons, tabs etc.
  
## :gear: How to Build and Run the App
* This app is builded using Visual Studio 2019
* Download the repo and open using Visual Studio 2019, then run the software
* For testing, one CSV file is given in this repo named <code>[DemoProjectData.csv](DemoProjectData.csv)</code>
* Main file : DemoProjectDlg.cpp
* Chart creating file : FirstDialog.cpp

Thank you for reading and reach out to me for any help regarding MFC. Happy coding :smile_cat:
