# project-6
Photo Gallery Web Page

A simple and responsive photo gallery web page that displays multiple images in a grid layout with captions and basic styling.

Features

Responsive grid layout for images

Image captions

Hover effect on images

Easy to customize with your own images and styles

Demo

You can see a live preview by opening index.html in your browser.

Folder Structure
photo-gallery/
│
├── index.html       # Main HTML file
├── style.css        # CSS styles
├── images/          # Folder containing gallery images
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── README.md        # Project documentation
Getting Started

Clone the repository or download the files.

git clone https://github.com/yourusername/photo-gallery.git

Open index.html in your browser.

Add your images in the images/ folder and update the HTML file with image paths and captions.

HTML Example
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>My Photo Gallery</h1>
    <div class="gallery">
        <div class="gallery-item">
            <img src="images/image1.jpg" alt="Description 1">
            <p>Caption for Image 1</p>
        </div>
        <div class="gallery-item">
            <img src="images/image2.jpg" alt="Description 2">
            <p>Caption for Image 2</p>
        </div>
        <!-- Add more images here -->
    </div>
</body>
</html>
CSS Example (style.css)
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

h1 {
    margin: 20px 0;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    padding: 20px;
}

.gallery-item {
    background-color: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.gallery-item img {
    width: 100%;
    height: auto;
    display: block;
    transition: transform 0.3s;
}

.gallery-item img:hover {
    transform: scale(1.05);
}

.gallery-item p {
    margin: 10px 0;
    padding: 0 10px;
    font-size: 14px;
    color: #333;
}
Customization

Adding Images: Add new images to the images/ folder and add corresponding <div class="gallery-item"> blocks in index.html.

Styling: Modify style.css to change colors, fonts, grid layout, or hover effects.

Captions: Change the <p> content below each image to describe your photos.
output:
 https://aashikbasha07.github.io/project-6/
