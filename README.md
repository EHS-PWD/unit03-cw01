### **Lesson 01: Add Images **

#### **Objective:**

In this lesson, students will learn how to add images to a webpage using the `<img>` tag, create clickable image links, and enhance accessibility with tooltips, while organizing the content using a table layout.

---

### **Step-by-Step Guide**

#### **Step 1: Set Up the HTML Document**

1. Create a new folder called `media-gallery` inside of your unit03 - cw folder.
2. Drag and drop the `media-gallery` folder on VSCode to open it up.
3. Inside this folder, create a new folder called `images` and a new file named `index.html`.
4. Write the basic HTML structure:
   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Media Gallery</title>
     </head>
     <body></body>
   </html>
   ```

#### **Step 2: Add a Title and Heading**

5. Inside the `<body>` tag, add a heading for your media gallery:
   ```html
   <h1>Media Gallery</h1>
   ```

#### **Step 3: Create a Table for the Gallery**

6. Below the heading, create a table to hold your images:
   ```html
   <table border="1">
     <tr>
       <td>Image 1</td>
       <td>Image 2</td>
       <td>Image 3</td>
     </tr>
   </table>
   ```

#### **Step 4: Add Images to the Table**

7. Replace the text placeholders (`Image 1`, `Image 2`, `Image 3`) with the `<img>` tags for your chosen images (find your own photos from online). Make sure to save the all three images inside the images folder. Use different attributes for each image:
   ```html
   <table border="1">
     <tr>
       <td>
         <img
           src="./images/image1.jpg"
           alt="Description of Image 1"
           width="150"
           height="100"
           title="This is Image 1"
         />
       </td>
       <td>
         <img
           src="./images/image2.jpg"
           alt="Description of Image 2"
           width="150"
           height="100"
           title="This is Image 2"
         />
       </td>
       <td>
         <img
           src="./images/image3.jpg"
           alt="Description of Image 3"
           width="150"
           height="100"
           title="This is Image 3"
         />
       </td>
     </tr>
   </table>
   ```

#### **Step 5: Add a Clickable Image Link**

8. Choose one of your images to make it clickable. Wrap the `<img>` tag in an `<a>` (anchor) tag that links to an external website:
   ```html
   <td>
     <a href="https://www.example.com" target="_blank"
       ><img
         src="./images/image1.jpg"
         alt="Description of Image 1"
         width="150"
         height="100"
         title="This is Image 1"
     /></a>
   </td>
   ```

#### **Step 6: Finalize the Table Structure**

9. Ensure your table looks organized. You can add a second row to include captions below each image:
   ```html
   <tr>
     <td>Caption for Image 1</td>
     <td>Caption for Image 2</td>
     <td>Caption for Image 3</td>
   </tr>
   ```

#### **Step 7: Save and Preview Your Form**

10. Save your index.html file.
11. Open it in a web browser to preview your media gallery.

#### **Step 8: Submit Your Work:**

12. Once you've confirmed that the media gallery looks good, submit the following:
    - The zipped media-gallery folder with the index.html file and images folder that contains 3 images.
    - Upload it to the classwork assignment on Google Classroom

#### **Assessment Criteria:**

- **HTML Structure:** Properly follows the HTML document structure, including `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags.
- **Images:** Successfully includes at least three images with the correct `src`, `alt`, `width`, and `height` attributes.
- **Clickable Link:** One image should be wrapped in an anchor tag (`<a>`), linking to an external website.
- **Tooltips:** Each image must have a tooltip added using the `title` attribute.
- **Table Layout:** Organizes images and captions using a table with appropriate rows and columns.
- **Captions:** Provides captions for each image in a separate row below the images.
