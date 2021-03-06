# Homepage

`/dashboard/settings/homepage`

## Style

| Value  | Effect  |
|---|---|
| Landing page  | Set homepage as a landing page with a heading and a call to action button  |
| Split landing + images  | Set homepage as split landing plus a list of images  |
| Route explore  | Set homepage as `/explore`  |
| Route upload  | Set homepage as `/upload` |

## Cover image (`n`)

Determines the cover image used in homepage (multiple instances).

| Type  | Recommended  |
|---|---|
| Image  | `<400KB` |

## Add new cover image

Adds a new cover image.

| Type  | Recommended  |
|---|---|
| Image  | `<400KB` |

## Vector logo image

The vector logo image for homepage. The size is just for reference, the system will display the logo fixing height.

| Type  | Default  |
|---|---|
| SVG  | 500x76 |

## Raster logo image

The raster logo image homepage. The size is just for reference, the system will display the logo fixing height.

| Type  | Default  |
|---|---|
| PNG  | 314x48 |

## Title

Determines the title shown in homepage.

| Type  | Default  |
|---|---|
| String  | Upload and share your images. |

## Paragraph

Determines the paragraph shown in homepage.

| Type  | Default  |
|---|---|
| String  | Drag and drop anywhere you want and start uploading your images now. 2 MB limit. Direct image links, BBCode and HTML thumbnails. |

## Call to action button color

Determines the color for the homepage call to action button.

| Type  | Options  |
|---|---|
| String  | Blue, Green, Orange, Red, Grey, Black, White, Default|

## Call to action outline style button

Toggles homepage call to action outline style.

| Value  | Effect  |
|---|---|
| Enabled  | Enable homepage call to action outline style  |
| Disabled  | Disable homepage call to action outline style  |

## Call to action functionality

| Value  | Effect  |
|---|---|
| Trigger uploader  | Prompt image upload file picker  |
| Open URL  | Link to the target URL  |

## Call to action URL

* Applies only when `Call to action functionality` is set to `Open URL`.

Determines the target URL for the homepage call to action button.

| Type  | Example  |
|---|---|
| String  | `/page/tos`  |

## Call to action HTML

Determines the HTML for the homepage call to action button.

| Type  | Default  |
|---|---|
| String  | Start uploading  |

## User IDs

* Applies only when `Style` is set to `Split landing + images`.

Determines the user ids which will source the homepage images.

| Type  | Example  |
|---|---|
| Integer  | 1,2,3,5,70  |
