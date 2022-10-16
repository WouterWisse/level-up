### Xcode - Single size app icon
Xcode 14 introduced a way to include an app icon with just one `1024 x 1024` image. Just select `Single Size` in the attributes panel of the `AppIcon` file in the Asset Catalog.<br />

Note: Make sure the Asset Catalog containing the AppIcon is in the root of the Xcode project. It does not seem to work when it's placed in a subfolder like `<Root>/Resources/MyAssetCatalog/...`. This results in validation errors when uploading the app to the AppStore. Also make sure the image does not contain an alpha layer.

<div align="center">
   <img src="assets/validation-errors.png">
   <br />
   <em>Weird errors because my Asset Catalog containing the AppIcon was not in the root of my Xcode project.</em>
</div>
