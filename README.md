# ResuMate - Resume Builder

ResuMate is a lightweight, responsive web-based Resume Builder that allows users to create, preview, and export customized professional resumes in real-time.

## Features

- **Real-Time Live Preview**: Instantly see your resume update as you type in your details.
- **Multiple Resume Templates**:
  - **Modern**: Clean design with centered header and organized section divides.
  - **Professional**: Classic single-column layout suitable for corporate roles.
  - **Creative**: Distinctive two-column layout with styled sidebar for contact and skills.
- **Dynamic Template Switching**: Seamlessly toggle between templates in the live builder without losing entered data.
- **One-Click PDF Export**: Download high-resolution vector PDF resumes rendered using `jsPDF` and `html2canvas`.
- **Fully Responsive**: Optimized layout for desktop, tablet, and mobile devices.

## Project Structure

```
resume builder/
├── index.html          # Landing page introducing ResuMate & template options
├── style.css           # Styling for landing page & navigation
├── builder.html        # Main interactive resume builder page
├── builder.css         # Responsive styling for builder form & preview split view
├── modern.html         # Modern resume template markup
├── modern.css          # Styling for Modern resume template
├── modern.png          # Preview image for Modern template
├── professional.html   # Professional resume template markup
├── professional.css    # Styling for Professional resume template
├── professional.png    # Preview image for Professional template
├── creative.html       # Creative resume template markup
├── creative.css        # Styling for Creative resume template
├── image.png           # Preview image for Creative template
└── README.md           # Project documentation
```

## Getting Started

1. Clone or download this repository to your local machine.
2. Open `index.html` in any web browser to view the landing page.
3. Click **"Get Started"** or **"Build my resume"** to navigate to `builder.html`.
4. Fill in your details (Personal Info, Summary, Education, Skills, Projects, Experience).
5. Choose your desired template (**Modern**, **Professional**, or **Creative**).
6. Click **"Download Pdf"** to save your formatted resume.

## Technologies Used

- **HTML5 & CSS3**: Structured layout, flexbox positioning, and responsive media queries.
- **JavaScript (ES6+)**: Real-time DOM manipulation and template iframe synchronization.
- **jsPDF & html2canvas**: Client-side canvas rendering and PDF generation.
- **Google Fonts**: Quicksand typography.

## License

© 2026 ResuMate by Boddeti Ajutesh. All rights reserved.
