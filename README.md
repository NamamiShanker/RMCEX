# RMCEX

A personal tool I use for cleaning C++ debug logs and executables

## How to insall

1. Clone this repository copy
2. Give executable permissions to rmcex `chmod +x rmcex`
3. Copy the file to `~/bin` folder. Make one if not made previously
4. Add `~/bin` to path. Steps below.
    1. Open your bashrc file. `sudo nano ~/.bashrc`
    2. Insert the below code at the end of
        ```export PATH=$PATH:~/bin```
    3. Save the bashrc file.

## How to use

1. Navigate to your directory containing C++ executables.
2. Enter `rmcex`
3. The directory will be cleaned.