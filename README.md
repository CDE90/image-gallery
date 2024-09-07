# How to Add New Images to The Gallery

Adding new pictures to the gallery is super easy. Just follow these simple steps:

## Step 1: Get Your Picture Ready

1. Find the picture you want to add.
2. Your picture can be any common image format (like .jpg, .png, .gif).
3. Give it a simple, descriptive name, like "sunset-beach.jpg" or "happy-dog.png".

## Step 2: Put the Picture in the Right Place

1. Go to our GitHub repository.
2. Click on the "images" folder.
3. Click the "Add file" button, then "Upload files".
4. Drag your picture file into the upload area or click "choose your files" to select it.
5. At the bottom, write a short message like "Add new image: sunset-beach.jpg".
6. Click the green "Commit changes" button.

## Step 3: Tell the Website About Your New Picture

1. In the GitHub repository, find and click on the "index.html" file.
2. Click the pencil icon to edit the file.
3. Find the part that looks like this:

```html
<div class="gallery">
    <!-- Your new picture goes here -->
</div>
```

4. Add these lines inside the `<div class="gallery">` part:

```html
<figure>
    <img
        src="/images/sunset-beach.jpg"
        alt="Sunset at the beach"
        loading="lazy"
    />
    <figcaption>Beautiful sunset at the beach</figcaption>
</figure>
```

5. Change "sunset-beach.jpg" to match your picture's name.
6. Change "Sunset at the beach" to describe your picture.
7. Write a nice description between `<figcaption>` and `</figcaption>`.
8. At the bottom, write a message like "Add new image to gallery: sunset beach".
9. Click the green "Commit changes" button.

That's it! Your new picture is now part of the art gallery. 🎨🖼️

# How to Add a New Video to The Gallery

Adding a video to the gallery is similar to adding an image, but with a few extra steps:

### Step 1: Prepare Your Video and Thumbnail

1. Have your video ready in MP4 format.
2. Create a thumbnail image for your video (JPG or PNG format).
3. Give both files simple, descriptive names, like "beach-sunset.mp4" and "beach-sunset-thumbnail.jpg".

### Step 2: Upload the Video and Thumbnail

1. Go to our GitHub repository.
2. Click on the "videos" folder and upload your MP4 file.
3. Click on the "images" folder and upload your thumbnail image.
4. For each upload, write a short commit message like "Add new video: beach-sunset.mp4" or "Add new video thumbnail: beach-sunset-thumbnail.jpg".
5. Click the green "Commit changes" button for each upload.

### Step 3: Add the Video to the Website

1. In the GitHub repository, find and click on the "index.html" file.
2. Click the pencil icon to edit the file.
3. Find the `<div class="gallery">` section.
4. Add the following code inside this section:

```
<figure class="video-figure">
    <div class="video-thumbnail" data-video-src="/videos/beach-sunset.mp4">
        <img
            src="/images/beach-sunset-thumbnail.jpg"
            alt="Beach Sunset Video"
            loading="lazy"
        />
        <div class="play-icon">▶</div>
    </div>
    <figcaption>Beautiful beach sunset video</figcaption>
</figure>
```

5. Change "beach-sunset.mp4" to match your video file name.
6. Change "beach-sunset-thumbnail.jpg" to match your thumbnail image name.
7. Update the `alt` attribute and `<figcaption>` to describe your video.
8. At the bottom, write a commit message like "Add new video to gallery: beach sunset".
9. Click the green "Commit changes" button.

That's it! Your new video is now part of the art gallery. 🎥🖼️
