IoT for Kids website

HOW TO HOST
Upload every file and the assets folder together (keep them side by side) to any static host
(Netlify Drop, GitHub Pages, Cloudflare Pages, or your own hosting). Open index.html to test locally.

CONTENTS
index.html          - the whole website (styles and scripts are inside)
assets/             - images
Components_List.pdf - opened by the "View component list" / "Download PDF" buttons
Teachers_Guide.pdf  - opened by the "View teacher's guide" / "Download PDF" buttons

ENQUIRY FORM
The form shows the thank-you screen but is not yet connected to your email.
1. Make a free form at formspree.io with your email.
2. Open index.html, search for FORM_ENDPOINT and paste your link between the quotes,
   e.g. FORM_ENDPOINT='https://formspree.io/f/xxxxxxxx';

PHOTOS
The gallery and hero use online Unsplash photos, which need internet. The "A little about the person" photo
falls back to assets/ if the online photo fails.
