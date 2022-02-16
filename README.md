### ATTN: I no longer have the hardware to work on this project, so if anyone wants to take over being the maintainer let me know. 

# Logitech-G560-LED-Controller

Library for managing LEDs of the Logitech G560 speakers in Linux

* * *

## Requirements:

-   Python 3.6
-   pyusb
-   RPyC
-   GTK 3
-   libusb - Install with your distros package manager

* * *

## Instructions:

##### Do to libusb, this library requires root access.

-   RPC service needs to be ran to handle libusb.
  **Requires Root access**
    ```bash
    $ sudo python3 'g560_service.py'
    ```


-   I am working on building LED alerts, this can be accessed with:
    ```bash
    python3 'g560_alerts.py'
    ```


-   A GUI implementation can be accessed by running
    ```bash
     python3 'g560_gui.py'
    ```

* * *

## Project Goal:

> The goal of this project is to build out an interface for handling Logitech devices, including:
>
> -   A system notification interface
> -   GTK - graphical user interface
> -   Integrate in Gnome using shell extensions
> -   Support for other Logitech devices, such as: Mice, Keyboards, or other LED enabled devices.

* * *
