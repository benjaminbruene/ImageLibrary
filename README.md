# ImageLibrary

## File Uploads & Security

This ASP.NET Core Razor Pages application allows users to upload images and view them in a gallery.

## Features

- Upload JPG and PNG images
- Validate file types and file sizes under 2 MB
- Require a title for each image
- Generate unique filenames for uploaded files
- Save uploaded images in `wwwroot/uploads/`
- Store image information in `data/images.json`
- Display uploaded images with their titles
- Handle invalid uploads and display error messages
- Use anti-forgery protection on the upload form

## Technologies Used

- C#
- ASP.NET Core Razor Pages
- .NET 10
- JSON
- Visual Studio

## Screenshots

### Upload Form
![Upload Form](Screenshots/UploadImage.png)

### File Size Validation
![File Size Error](Screenshots/FileSizeError.png)

### Image Gallery
![Image Gallery](Screenshots/Gallery.png)

## How to Run

1. Open the project in Visual Studio.
2. Build and run the application.
3. Navigate to `/Upload`.
4. Enter an image title and select a JPG or PNG file smaller than 2 MB.
5. Click Upload to save the image.
6. Navigate to `/Gallery` to view uploaded images and their titles.

## File Storage

The application saves uploaded images in `wwwroot/uploads/`.

Image filenames and titles are stored in `data/images.json`.