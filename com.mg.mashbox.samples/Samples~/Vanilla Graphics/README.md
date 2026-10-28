# Vanilla Graphics

The `Vehicles_BMX_Brands` folder contains 221 PNG images from the Creative
Cloud library, arranged in their original brand and asset groups.
Removed 127 UV Layout images and converted 168 remaining Photoshop
files to PNG using their saved merged composites, preserving dimensions,
transparency, embedded color profiles, and Unity texture GUIDs. No PSD files remain.

`Vehicles_BMX_Brands/ImageCatalog.json` lists each retained image's name, group,
dimensions, and current SHA-256 checksum. Converted images also record the
original PSD checksum. All conversions were checked for exact decoded pixel
equality with the saved Photoshop composite. The cloud library is unchanged.

Add more reusable 2D graphics to this folder (subfolders are supported).
Commit each image together with its Unity `.meta` file to preserve references.

In MashBox Studio's 2.5D Imaging window, open **Image Library** and click
**Install Vanilla Graphics**. You can also import this sample from Unity's
Package Manager in the **MashBox Samples** package. Images appear under **Vanilla Graphics** in the library.
Double-click an image to add a layer, or drag it onto the canvas.

For project-specific images, use `Assets/MashBox/Image Library` instead.
The library's **Project Folder** button creates and selects that folder.

The install button adds missing files without overwriting project files.
After adding more graphics to the samples package, click it again to install those additions.
Existing samples imported from earlier SDK versions remain visible in the library.

This sample is maintained in the separate `mashbox-sdk-samples` Git repository,
under `com.mg.mashbox.samples/Samples~/Vanilla Graphics`. The Image Library editor
code is maintained in the SDK repository.
