# arkAVR
 
A Hardware to program any kind of AVR µController.

# Table of contents
* [Supported microcontrollers](#supported-microcontrollers)
* **[How to install](#how-to-install)**
  - [Boards Manager Installation](#boards-manager-installation)
  - [Manual Installation](#manual-installation)

## Supported microcontrollers
* The whole AVR Family

## How to install
#### Boards Manager Installation
This installation method requires Arduino IDE version 1.6.4 or greater.
* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**:
    ```
    https://arkAVR.github.io/arkAVR_index.json
    ```
* Separate the URLs using a comma ( **,** ) if you have more than one URL
* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **arkAVR** entry and click on it.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.

#### Manual Installation
Click on the "Download ZIP" button. Extract the ZIP file, and move the extracted folder to the location "**~/Documents/Arduino/hardware**". Create the "hardware" folder if it doesn't exist.
Open Arduino IDE, and a new category in the programmers menu called "arkAVR" will show up.
