---
layout: template_file
---

# Download and Install git Bash Client on macOS

While installing the git bash client on Windows OS is simple, performing the same on a macOS requires an additional step to allow the package file to be installed.

Here is the procedure:

1. Download the git bash client package for macOS from [https://git-scm.com/downloads](https://git-scm.com/downloads).
    The downloaded file will have a `.dmg` extension.
2. Double click the `.dmg`file, and you will get the `PKG`file, a `README.txt` file, and a version file.

3. Double click the `PKG` file and the following error message displays:
> `"macOS cannot verify the developer of “git-2.15.0-intel-universal-mavericks.pkg”. Are you sure you want to open it?" Click Open and this should then work.
"git-2.23.0-intel-universal-mavericks.pkg" cannot be opened because it is from an unidentified developer.`
>

4. Click OK to dismiss this error message.

5. Right click the `PKG` file, and select `Open With -> Installer (default)` option.

    The error message appears again but now an addtional `Open` button is displayed.

6. Click `Open` to open the Installation wizarad.

7. Complete the onscreen instructions in the Installation wizard to complete the git bash client installation.
