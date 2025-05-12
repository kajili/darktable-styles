# darktable-styles

To use these styles:

1. Click the `Code` button at the top right, and then click `Download ZIP`, then unzip the files.
1. In `darktable`, open the `lighttable` tab at the top right to view your images.
1. Navigate to the `styles` module on the right sidebar.
1. Click import, then select the `.dtstyle` files that you downloaded.
1. Now you can apply the styles to your own images either via:
   1. That same `styles` module in `lighttable`
   1. Or in `darkroom` when editing a specific image, by finding the `styles` icon at the bottom left that looks like 3 circles.

## Specific Style Explanations

### light simulation

This style simulates a light source.

1. This style is just a way of combining two module presets, an instance of `haze removal` and an instance of `color balance rgb`.
2. To use it, you must go into `haze removal` and add a mask to direct the light source properly.
3. Then the `color balance rgb` module should automatically use the same mask as a `raster mask`.
4. From there you can tweak the intensity of the light using dehaze in `haze removal` and the `global brilliance grading` sliders (mostly `highlights`) in `color balance rgb`.
5. You can tweak the color of the light by going into the `4 ways` tab in `color balance rgb` and changing `hue` and `chroma` in the `global offset` section.
