# OpenVGAL Virtual Gallery

Your virtual 3D art gallery is ready to deploy!

## Quick Start

1. Extract this ZIP to your web server folder
2. Open viewer.html in a browser (or serve with any web server)

Your images are already included in the ZIP under these folders:
- Cowgirls/
- Exhibit (1)/
- Exhibit (1)#1/
- Exhibit (2)/
- Exhibit (2)#1/
- Exhibit (3)/
- Exhibit (3)#1/
- Exhibit (4)/
- Exhibit (4)#1/
- Exhibit (5)/
- Exhibit (5)#1/
- Exhibit (6)/
- Exhibit (6)#1/
- Exhibit (7)/
- Exhibit (7)#1/
- Exhibit (8)/
- Exhibit (8)#1/
- Exhibit (9)/
- Exhibit (9)#1/

## Folder Structure

```
your-gallery/
├── viewer.html         # Main viewer
├── building_v2.json    # Gallery configuration
├── declarations.js     # Path configuration
├── templates/          # 3D room templates
├── materials/          # Textures and materials
├── Cowgirls/               # Your images
├── Exhibit (1)/               # Your images
├── Exhibit (1)#1/               # Your images
├── Exhibit (2)/               # Your images
├── Exhibit (2)#1/               # Your images
├── Exhibit (3)/               # Your images
├── Exhibit (3)#1/               # Your images
├── Exhibit (4)/               # Your images
├── Exhibit (4)#1/               # Your images
├── Exhibit (5)/               # Your images
├── Exhibit (5)#1/               # Your images
├── Exhibit (6)/               # Your images
├── Exhibit (6)#1/               # Your images
├── Exhibit (7)/               # Your images
├── Exhibit (7)#1/               # Your images
├── Exhibit (8)/               # Your images
├── Exhibit (8)#1/               # Your images
├── Exhibit (9)/               # Your images
├── Exhibit (9)#1/               # Your images
├── overlay.js          # UI overlay
├── overlay.css         # UI styles
└── babylon.js          # 3D engine
```

## Deploying to a Subfolder

This gallery works in any subfolder — just extract and serve. All paths are
relative to viewer.html, so no configuration needed. For example:
- https://example.com/ (root)
- https://example.com/gallery/ (subfolder)
- https://example.com/art/my-gallery/ (nested subfolder)

If you need to customize paths, edit `declarations.js`.

## Custom Logo

Replace `materials/logo.png` with your own image.
Use white artwork on a black background (the white areas will glow).
Recommended size: 1024x512 px, PNG format.

## Need Help?

Visit https://openvgal.com for documentation and support.

Generated with OpenVGAL Generator
