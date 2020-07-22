To run the page:

<!-- In a separate terminal tab: -->
npm run compile:sass

<!-- In a separate terminal tab (needs live-server global install): -->
live-server

<!-- To get the icons -->
Icons are downloaded from https://linea.io/

In the downloaded package select:
_basic>_ICONFONT>fonts
_basic>_ICONFONT>styles.css

Rename styles.css to icon-font.css
In the index.html add
<link rel="stylesheet" href="css/icon-font.css">
above style.css link

Reference to icons is in:
_basic>_ICONFONT>icons-reference.html