# Uploading the module

## 2.12.2.1    Preparing the module files for upload to a remote server

Many module scripts are self-configuring once installed. However, some require some initial configuration as detailed in Ancillary files described above. Make sure you edit any files in a plain text editor, or application suitable for the file type. It is unwise to use web-authoring WYSIWYG applications such as FrontPage or Dreamweaver as they can add spurious code to your files. If you intend to make any extensive edits, prepare a backup beforehand.

## 2.12.2.2    Using FTP or browser file uploader

FTP is the preferred method of file transfer as it allows you to transfer a whole module directory automatically and maintain it structure. If you use a browser upload with limited file transfers, be sure to maintain the original directory structure.

## 2.12.2.3    Upload the module package

When you are sure your files are ready, upload the file set complete in its directory to the **./modules/** directory on your server.

## 2.12.2.4    Setting file/directory permissions

You may need to change ‘read/write/execute’ permissions for various files and folders, if stated in Ancillary files supplied with the package. Settings can vary between different server operating systems. Some modules will only work correctly with register\_globals set to 'on'. Please be aware of these requirements when installing modules.

