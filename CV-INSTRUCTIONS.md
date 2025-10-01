# CV Setup Instructions

## 📄 Adding Your CV PDF

### Option 1: Local File (Recommended)
1. Replace the placeholder file `/workspace/assets/Faisal-Alghamdi-CV.pdf` with your actual CV PDF
2. Keep the same filename: `Faisal-Alghamdi-CV.pdf`
3. The website will automatically display your CV in the embedded viewer

### Option 2: Google Drive Integration
If you prefer to host your CV on Google Drive:

1. Upload your CV to Google Drive
2. Right-click the file → Get link → Change to "Anyone with the link can view"
3. Copy the file ID from the URL (the long string between `/d/` and `/view`)
4. In `index.html`, uncomment the Google Drive iframe section and replace `FILE_ID` with your actual file ID:

```html
<!-- Replace this section -->
<iframe
    src="assets/Faisal-Alghamdi-CV.pdf#view=FitH"
    class="cv-iframe"
    title="Faisal Alghamdi CV"
    loading="lazy">
</iframe>

<!-- With this -->
<iframe
    src="https://drive.google.com/file/d/YOUR_FILE_ID/preview"
    class="cv-iframe"
    allow="autoplay"
    title="Faisal Alghamdi CV"
    loading="lazy">
</iframe>
```

5. Also update the download button href to point to your Google Drive file

## 🔧 Technical Notes

- **File Size**: Keep PDF under 10MB for optimal loading
- **Format**: Ensure it's a standard PDF (not password protected)
- **Mobile**: The viewer is responsive and works on mobile devices
- **Fallback**: If the PDF fails to load, users can still download it
- **Loading**: A loading indicator shows while the PDF loads

## 🚀 Testing

1. Open your website locally
2. Navigate to the CV section
3. Test both the download button and embedded viewer
4. Check on mobile devices for responsiveness

## 📱 Browser Compatibility

- ✅ Chrome, Firefox, Safari, Edge (latest versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)
- ⚠️ Some older browsers may not support PDF embedding (fallback download available)

## 🔒 Privacy Note

If using Google Drive, ensure your CV doesn't contain sensitive information as it will be publicly accessible via the link.