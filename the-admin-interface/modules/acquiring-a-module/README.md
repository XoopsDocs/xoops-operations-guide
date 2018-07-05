# Acquiring a module

## 2.12.1.1    Module origins

All modules need to be specifically designed for the XOOPS content management system. Currently there are 3 grades of modules available:

* Official certified modules available from XOOPS parent sites;
* 3rd party certified modules;
* 3rd party uncertified modules.

The recommended guidelines for acquiring these are described elsewhere in this manual.

Modules are normally packed in a compressed file format such as .zip or .tar format. You will need a file expander tool like WinZip or winrar to decompress the package and make the files useable.

After downloading and decompressing the module package, it is important to maintain the current directory structure and distribution of all associated files.

Please note: It is not essential to upload ‘ancillary files’ such as readme/changelog/install and other non-operational files. Likewise, you may wish to remove any language packs that are not required in your installation. It is wise however to retain any index files in all directories, regardless of blank content. This is a security measure. Leave files alone, if you are unsure.

Once the module package is unzipped, study the structure of the files in the local computer. Some modules are ready for uploading to the root directory instead of just the **/modules/** directory.

Normally you will need to upload the files into the **/modules/** directory which will be a second level sub-directory within your site root: e.g. [http://your\_xoops\_site.com/modules/your\_new\_module\_package](http://your_xoops_site.com/modules/your_new_module_package). However, some modules have extra files that need to be uploaded to other folders such as the **/include/** and the **/class/** directories.

It is important to upload ONLY the directory holding the main file set. Some modules are packed within nested sub-directories 2 or 3 layers beneath the package root, like this:

**my downloads V1.23/my\_downloads/mydownloads/\(this directory contains the main file set\)**

In this case be certain to upload the directory holding the main file set, NOT the root \(my downloads V1.23\) If you upload the module file set within nested directories by mistake the XOOPS install system will not register the new module package!

### 2.12.1.2    Ancillary files

Readme, install, changelog and other information files. Always view any Readme, install or changelog files if included. They often give important details about module installation requirements, setup and usage. If you require further information and assistance, they may also contain the author’s website address and/or email contact.

### 2.12.1.3    Copyrights and GPL notices

You may also see files relating to copyright and The General Public Licence. These may be viewed to verify the source, distribution rights, and conditions of use and authenticity of the module scripts within the package.

