# D2P Regional Training of Trainers Workshop Website

## Overview
This website provides information about the Regional Data to Policy (D2P) Training of Trainers Workshop taking place in Lusaka, Zambia, March 2-5, 2026.

## Website Structure

The website consists of 5 main pages:

### 1. **index.html** - Home Page
- Workshop overview
- Objectives and background
- Participating countries
- Expected deliverables
- Key details and quick links

### 2. **agenda.html** - Workshop Agenda
- Detailed 4-day schedule
- Session times and topics
- Break times and logistics
- Important notes for participants

### 3. **facilitators.html** - Facilitators
- Profiles of the three lead facilitators:
  - Andrew Ancharski
  - Chandra Dhakal
  - Diene Kaba
- Facilitation approach
- Contact information

### 4. **materials.html** - Training Materials
- Links to lecture presentations
- Group exercises
- Mentorship resources
- Challenge scenarios
- Example policy briefs
- Reference documents
- Pre-workshop preparation requirements
- Technical requirements

### 5. **logistics.html** - Logistics & Practical Information
- Venue details
- Daily schedule
- Meals and refreshments information
- Travel and accommodation guidance
- What to bring
- Health and safety information
- Workshop expectations
- Pre-departure checklist

## How to Use This Website

### Hosting on GitHub Pages

1. **Create a GitHub Repository:**
   - Go to GitHub and create a new repository
   - Name it something like `d2p-tot-lusaka-2026`
   - Make it public

2. **Upload Files:**
   - Upload all HTML files (index.html, agenda.html, facilitators.html, materials.html, logistics.html)
   - Upload the styles.css file
   - Upload this README.md file

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "main" branch
   - Select "/ (root)" as the folder
   - Click "Save"
   - Your site will be published at: `https://[your-username].github.io/d2p-tot-lusaka-2026/`

### Adding Training Materials

To add links to your training materials (stored in Google Drive or GitHub):

1. **For Google Drive:**
   - Create folders for each category (Lectures, Exercises, etc.)
   - Set sharing permissions to "Anyone with the link can view"
   - Copy the sharing link
   - In materials.html, replace `#` in the href attributes with your Google Drive links

2. **For GitHub:**
   - Create a "materials" folder in your repository
   - Upload files to appropriate subfolders
   - Update links in materials.html to point to these files

### Customization

To customize the website:

1. **Colors:**
   - Edit the CSS variables in styles.css (lines 13-22)
   - Change primary, secondary, and accent colors to match your branding

2. **Content:**
   - Update text directly in the HTML files
   - Add or remove sections as needed

3. **Images:**
   - Add a logo by creating an `<img>` tag in the navbar
   - Add photos of facilitators by replacing the icon divs
   - Add venue photos in the logistics section

## File Organization

```
d2p-tot-lusaka-2026/
├── index.html
├── agenda.html
├── facilitators.html
├── materials.html
├── logistics.html
├── styles.css
├── README.md
└── materials/          (optional - for hosted files)
    ├── lectures/
    ├── exercises/
    ├── mentorship/
    ├── challenges/
    └── examples/
```

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side processing required
- Fully responsive design (works on desktop, tablet, and mobile)
- No JavaScript dependencies

## Maintenance

To update the website:

1. Edit the relevant HTML file(s)
2. Commit and push changes to GitHub
3. Changes will automatically be reflected on the live site within a few minutes

## Contact Information

For questions about the website or workshop:
- **Andrew Ancharski:** aancharski@cdcfoundation.org
- **Chandra Dhakal:** cdhakal@cdcfoundation.org
- **Diene Kaba:** dkaba@cdcfoundation.org

## License

© 2026 CDC Foundation Data for Health Initiative. All rights reserved.

---

## Next Steps

1. Review all pages and update any placeholder text
2. Add links to your training materials folders
3. Add actual hotel information in logistics.html
4. Add venue contact details
5. Consider adding a favicon (small icon for browser tabs)
6. Test all links before the workshop
7. Share the website URL with participants 2 weeks before the workshop

## Tips for Success

- Update materials page weekly as you add new resources
- Keep the agenda page current if schedule changes occur
- Consider adding a FAQ section if you receive common questions
- Add photos from the workshop afterwards to create a gallery page
- Use the website as a template for future workshops
