# How to Add New Images to The Gallery

Hello! Adding new pictures to the gallery is super easy. Just follow these simple steps:

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
