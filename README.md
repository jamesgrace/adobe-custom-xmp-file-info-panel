# adobe-custom-xmp-file-info-panel
Adobe Custom XMP File Info Panel that includes example sections displaying both user editable and read-only Custom Metadata fields ( *compatible with Extensis Portfoio* ) , Standard Metadata fields ( *e.g. Description , Keywords , Star Ratings* ) , and Technical Attributes ( *e.g. Image Size , Modified , etc.* ).

#### Requirements :
* Adobe Creative Cloud 2017 ( _or greater_ ).
  * Although the provided example may work properly with earlier Adobe Creative Cloud versions , Creative Cloud 2017 ( *or greater* ) is recommended

## Installation Procedure :

#### 1. PANEL FOLDER
* Copy the entire `Example` folder structure over to the appropriate operating system specific location :
  * Macintosh :point_right: `/Library/Application Support/Adobe/XMP/Metadata Extensions/`
  * Windows :point_right: `C:\Program Files (x86)\Common Files\Adobe\XMP\Metadata Extensions\`
* Download the included `NASA_Worm_Logo.tif` sample image to an accessible location.

#### 2. PANEL VERIFICATION
* Launch Adobe Photoshop 
* Select `File` > `Open` to view the included `NASA_Worm_Logo.tif` image.
* Select `File` > `File Info...` to view the Adobe XMP dialog.
* Verify that the **Example** panel is listed ( *within the left-hand side of the XMP dialog* ).
* Select the **Example** panel and verify that the sample image's Custom Metadata , Standard Metadata , and Technical Attrbutes display as expected.

#### 3. PANEL MAINTENANCE
* The XML files should be viewed , edited , and maintained using a standard programmer's text editor :
  * Macintosh :point_right: Atom ( _https://atom.io/_ ).
  * Windows :point_right: Notepad++ ( _https://notepad-plus-plus.org_ ).
