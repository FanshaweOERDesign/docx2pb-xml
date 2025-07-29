# docx2pb-xml
Converts a DOCX file representing a Pressbooks part to a Pressbooks XML file and extracts images for easy upload to Pressbooks.

## How to Use
This app assumes that the input provided will be a .docx file representing a part to be added to Pressbooks with sub-chapters identified by Heading1 titles within the document. To use the app:
1. Enter the title for your Pressbooks part/chapter
2. Enter a sample image URL from your Pressbook. This can be the URL of any image already added to the Media Library of your Pressbook, and is required for the app to process the images in your Word doc so that they will display on your generated Pressbooks pages.
3. Drag and drop or use the file explorer to upload your Word file. A download button and preview of the file should appear below the file drop zone.
4. Click the download button. A zip archive entitled *project* will download. Within this archive is an XML file (*pressbooks.xml*) and an images folder containing any extracted images.
5. Upload the images to you Pressbook Media Library. This can be done quickly by selecting all of the contents of the downloaded images folder and dragging the contents into the Media Library file uploader.
6. Navigate to **Import** in Pressbooks. Select **PressbooksXML** for upload type and select the downloaded *pressbooks.xml* file, and click the button to begin the import. On the next page, select all of the items and import them.
7. The new part/chapter with its subsections will be added to your Pressbook.

