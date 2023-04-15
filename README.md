## createdummy

A simple command line based tool to create a dummy with a specific list of resolutions.

The tool is **free to use for personal use** (if used for business, I kindly ask you to please purchase a [BetterDisplay](https://github.com/waydabber/BetterDisplay) license to support development).

The tool runs on **macOS Mojave and newer, Intel and Apple Silicon**.

Please add a **thumbs-up** to this post if you download/use it so I may know there is a demand for such a thing. :)

---

Use `createdummy help` to list instructions.

### Example uses

`createdummy`
Creates a dummy with default settings and a wide range of resolutions (both LoDPI and HiDPI)

`createdummy width=21 height=9 hidpi=no`
Creates a 21:9 dummy with no HiDPI resolution counterparts (with halved logical pixel sizes) enabled.

`createdummy serial=7777 name=MyDummy`
Creates a 16:9 dummy with a serial number of 7777 and display name `MyDummy`.

`createdummy min=720 max=2560`
Creates a 16:9 dummy with minimum (vertical) framebuffer resolution mode of 720 and maximum (horizontal) of 2560.

`createdummy width=4 height=3 step=100`
Creates a 4:3 dummy with framebuffer resolution steps of 100x (800:600, 1200:900, 1600:1200...).

`createdummy res=2560x1440 res=1600x1200 res=1280x1024 res=1280x960 res=1024x768`
Creates a variable aspect ratio dummy with some specific resolution modes.

All paramteres can be used together, except `res` and `width/height/step` as they are mutually exclusive.
