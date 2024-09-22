#### About
The tool is used for download and sync photos from DeviantArt from selected users.
The script has been calibrated to avoid spam blocks.

#### Requirements (Windows)
- Operating system: Windows 7, 8, 8.1, 10, 11
- Microsoft Visual C++ Redistributable for Visual Studio 2019
- [NGC-TOOLKIT + NGC-UTILITIES](https://github.com/AbyssMorgan/NGC-TOOLKIT/releases)
- Installed .ngcs script support (Run NGC-TOOLKIT as administrator then go to Help \> Install .ngcs script support)

#### Requirements (Linux)
- [Same as NGC-TOOLKIT](https://github.com/AbyssMorgan/NGC-TOOLKIT?tab=readme-ov-file#requirements-linux)

#### How to use (Windows)
- Run DeviantArt.ngcs
- Add user/users you need to sync (type 2 and press enter, then put links separated by space, then press enter)
- Type 0 and press enter for fetch all new posts
- Type 1 and press enter for start download images

#### How to use (Linux)
- For run script in linux you need make .sh file with you custom path for NGC-TOOLKIT and NGC-DEVIANTART-DOWNLOADER, example:
```
#!/bin/bash
cd "$(dirname "$0")"
/usr/bin/php8.3 "{path_to_ngc_toolkit}/includes/script.php" "{path_to_ngc_deviantart_downloader}/DeviantArt.ngcs"
```
- For auto fetch and download you can use
```
#!/bin/bash
cd "$(dirname "$0")"
/usr/bin/php8.3 "{path_to_ngc_toolkit}/includes/script.php" "{path_to_ngc_deviantart_downloader}/DeviantArt.ngcs" --auto
```
