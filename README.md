# Upload SVG images in Magento 2.x

This extension for Magento 2 allows uploading SVG images in the following sections:
* wysiwyg editor in static blocks and pages
* wysiwyg editor on product edit page
* theme logo and favicon


**IMPORTANT:** *if you like the extension, could you please add a star to this GitHub repository in the top right corner. This is really important for us. Thanks.*

## Installation

### Using Composer (recommended)
1) Go to your Magento root folder
2) Downaload the extension using composer:
    ```
    composer require magegadgets/svg-web-images
    ```
3) Run setup commands:

    ```
    php bin/magento setup:upgrade;
    php bin/magento setup:di:compile;
    php bin/magento setup:static-content:deploy -f;
    ```
   
### Manually
1) Go to your Magento root folder:
    
    ```
    cd <magento_root>
    ```
   
2) Copy extension files to *app/code/Magegadgets/SvgWebImages* folder:
    ```
    git clone https://github.com/magegadgets/svg-web-images.git app/code/Magegadgets/SvgWebImages
    ```
    ***NOTE:*** *alternatively, you can manually create the folder and copy the extension files there.*
    
3) Run setup commands:

    ```
    php bin/magento setup:upgrade;
    php bin/magento setup:di:compile;
    php bin/magento setup:static-content:deploy -f;
    
## Other Extensions
You can find more useful extensions for Magento 2 by visiting [Magegadgets Official Website](https://www.magegadgets.com/)
    ```
