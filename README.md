## 🔹 Step 1: Create a GitHub Repo

1. Go to [GitHub](https://github.com/) → **New Repository**.
2. Give it a name (example: `assets-hosting` or `my-images`).
3. Keep it **Public**.
4. Click **Create repository**.

---

## 🔹 Step 2: Upload Your Image/Video

1. Open your repo.
2. Click **Add file → Upload files**.
3. Select your `image.png` or `video.mp4`.
4. Commit the changes.

---

## 🔹 Step 3: Get the **Raw File Link**

1. Open the uploaded file in your repo.
2. Click the **`Download` / `Raw` button** (top-right).
3. Copy the URL from the browser → it will look like:

```
https://raw.githubusercontent.com/<username>/<repo>/main/<filename>
```

Example:

```
https://raw.githubusercontent.com/vikram/assets-hosting/main/myphoto.png
```

---

## 🔹 Step 4: Use in Your HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Hosted Media</title>
</head>
<body>
  <!-- Image -->
  <img src="https://raw.githubusercontent.com/vikram/assets-hosting/main/myphoto.png" 
       alt="GitHub Hosted Image" width="400">

  <!-- Video -->
  <video width="500" controls>
    <source src="https://raw.githubusercontent.com/vikram/assets-hosting/main/myvideo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</body>
</html>
```

---

## ✅ Advantages of GitHub Hosting

* No need for Google Drive hacks.
* Works anywhere (`<img>`, `<video>`, React, etc.).
* Free + reliable CDN.
* Easy to update (just push a new commit).

---

⚠️ Note: GitHub **raw links are not optimized for very large files** (e.g., >25MB videos). For videos, YouTube/Cloudinary is usually better.

---

👉 Do you want me to make a **ready-to-use example repo with an image + HTML page** so you can clone and test immediately?
