# O-RAN Styles toolbar
MS Word toolbar to ease the use of  O-RAN drafting styles.


# Installation

For the O-RAN styles to work, the contributors need to install **oran_styles_toolbar - v1.2.dotm** file to the Microsoft Word startup folder. In a typical Windows 10 installation, it can be found under:

	C:\Users\<USERNAME>\AppData\Roaming\Microsoft\Word\STARTUP

You can check the current STARTUP folder's location via:
File-Options->Advanced->General->File Locations->[File types: Startup]

The **ORAN_styles.dotm** contains the style definitions and must be embedded to any O-RAN document that wants to use the styles. In Windows, such files are typically stored under:

	C:\Users\<USERNAME>\AppData\Roaming\Microsoft\Templates

Attaching the style file is done as follows:
File->Options->Add-ins->Manage->Select "Templates" from pull-down menu->Go->Attach->[Navigate and Select file]->Check "Automatically update document styles"->OK 
