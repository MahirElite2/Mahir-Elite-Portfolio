MAHIR ELITE PORTFOLIO — RESTORED + IMAGE UPLOAD FIX

FILES
- index.html: original portfolio website and animations
- admin-dashboard.html: profile, projects, Awards & Achievements, training, skills and settings
- portfolio-manager.html: standalone project manager
- messages.html: contact message inbox
- shared-sync.js: keeps portfolio content connected to the dashboard/project manager
- profile.jpg and assets/: supplied profile, award, training and project images

RUN
1. Extract this complete folder.
2. Open the folder in VS Code.
3. Run index.html with Live Server. Open Admin Dashboard, Project Manager and Messages from the navigation links so every page uses the same localhost origin.

IMAGE UPLOAD
- In Project Manager, click Add Project, choose a file in the image upload field, then Save Project.
- In Admin Dashboard, open Profile Manager, My Projects, Awards & Achievements, or Training & Hackathons. Choose an image file and save the form.
- Images are resized/compressed in your browser and stored in this browser's localStorage. Use moderate image sizes and export a JSON backup regularly.
- Uploaded local images are local to this browser/origin. They are not uploaded to a public server and will not automatically appear for visitors on another device. A backend or hosting upload service is required for public syncing.

DESIGN
The original index.html layout, palette, animation CSS, existing awards cards and supplied assets have been retained. Do not separate shared-sync.js or the assets folder from the HTML files.

NOTE
This is a frontend/local-storage version, not a secure multi-user backend. JavaScript syntax checks were run on the edited files; the site should still be opened in Live Server for visual testing.
