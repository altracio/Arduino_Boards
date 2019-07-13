# Altrac Arduino Boards

This repository contains support for the following Altrac Arduino-compatible development boards.

**IMPORTANT NOTE:** These board files have been updated for compatibility with Arduino version 1.8 and higher. Some boards (e.g. SAMD) may not compile correctly with earlier versions of Arduino. If you need compatibility with earlier versions of Arduino, you can choose previous releases of these boards from the Boards Manager.

#### SAMD (ARM Cortex-M0+) Boards

* Altrac AMB

### Installation Instructions

To add board support for our products, start Arduino and open the Preferences window (**File** > **Preferences**). Now copy and paste the following URL into the 'Additional Boards Manager URLs' input field:

	https://raw.githubusercontent.com/sparkfun/Arduino_Boards/master/IDE_Board_Manager/package_sparkfun_index.json

![Location of Additional Boards Manager URL input field](prefs-arrow.png)

If there is already an URL from another manufacturer in that field, click the button at the right end of the field. This will open an editing window allowing you to paste the above URL onto a new line.

### SAMD Installation Instructions

When installing SAMD boards, you will need to first install Arduino SAMD support, then Altrac's SAMD boards.

Open the Boards Manager window by selecting **Tools** > **Board**, scroll to the top of the board list, and select **Boards Manager**. Now type "samd" (without quotes) into the "filter your search" field at the top of the window. Two entries should show up, one for Arduino SAMD boards, and one for Altrac SAMD boards. We'll install both of these, starting with Arduino SAMD boards.

Click anywhere in the "Arduino SAMD Boards" box, and click "Install". This is a large installation and will take a while.

![Arduino SAMD Boards](manager-arrow.png)

Now click anywhere in the "Altrac SAMD Boards" box, and click "Install". This is a small installation and will happen much faster.

![Altrac SAMD Boards](manager-arrow2.png)

You're now ready to use Altrac SAMD boards. They will appear at the bottom of the board list.
