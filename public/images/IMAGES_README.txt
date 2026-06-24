REQUIRED IMAGES — Replace these placeholders before launch
==========================================================

1. yaser-garcia.jpg
   - Yaser's headshot: navy blue polo, PXG cap, arms crossed, grass backdrop
   - Recommended size: 440 x 560 px (4:5 aspect ratio), JPG 85%
   - Used in: Coaches section (left card)
   - HTML: <img id="yaser-img" src="..."> → change src to "images/yaser-garcia.jpg"

2. memo-vega.jpg
   - Memo's headshot: orange striped polo, glasses, smiling, grass backdrop
   - Recommended size: 440 x 560 px (4:5 aspect ratio), JPG 85%
   - Used in: Coaches section (right card)
   - HTML: <img id="memo-img" src="..."> → change src to "images/memo-vega.jpg"

3. studio-lesson.jpg  (optional but recommended)
   - Interior shot of the studio / lesson bay / launch monitor setup
   - Recommended size: 700 x 875 px (4:5 aspect ratio), JPG 85%
   - Used in: About section
   - HTML: <img class="about-img-main" src="..."> → change src to "images/studio-lesson.jpg"

4. og-image.jpg  (for social sharing previews)
   - A wide crop of the hero or studio — any good horizontal golf photo
   - Recommended size: 1200 x 630 px, JPG
   - Referenced in: <meta property="og:image"> in the <head>
   - Update the URL to your actual domain once deployed

HOW TO SWAP IMAGES IN index.html:
  Open index.html and search for the image ID or class name.
  Replace the src="https://images.unsplash.com/..." with your image path.
  Example: src="images/yaser-garcia.jpg"

VERCEL DEPLOYMENT:
  1. Push this repo to GitHub (any branch).
  2. Connect the repo to Vercel at vercel.com/new
  3. Set the Output Directory to: . (root)
  4. No build command needed — this is a static HTML site.
  5. Vercel will serve index.html at your domain automatically.
