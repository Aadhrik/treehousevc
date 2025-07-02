# Treehouse Ventures Landing Page

An elegant and modern landing page for Treehouse Ventures VC fund, built with HTML and Tailwind CSS.

## Features

- 🎨 Beautiful, modern design with Tailwind CSS
- 📱 Fully responsive layout
- ⚡ Optimized for GitHub Pages
- 🏠 Single-page application with smooth scrolling
- 👥 Team section with placeholder avatars
- 💼 Investment thesis and fund information

## GitHub Pages Setup

1. **Create a new repository** on GitHub (e.g., `treehouse-ventures-site`)

2. **Upload files** to your repository:
   - Upload `index.html` to the root of your repository

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your site will be available** at:
   ```
   https://[your-username].github.io/[repository-name]
   ```

## Customization

### Adding Team Photos
Replace the colored circle placeholders with actual photos:

1. Add image files to an `images/` folder in your repository
2. Update the team section in `index.html`:
   ```html
   <!-- Replace this: -->
   <div class="w-32 h-32 bg-gradient-to-br from-treehouse-400 to-treehouse-600 rounded-full mx-auto mb-6 flex items-center justify-center">
       <span class="text-3xl font-bold text-white">AK</span>
   </div>
   
   <!-- With this: -->
   <img src="images/aadhrik.jpg" alt="Aadhrik Kuila" class="w-32 h-32 rounded-full mx-auto mb-6 object-cover">
   ```

### Updating Content
- **Investment Thesis**: Edit the content in the "Investment Thesis" section
- **Team Bios**: Update the descriptions for each team member
- **Contact Information**: Update the email address in the contact section
- **Colors**: Modify the Tailwind color scheme by adjusting the `treehouse` color palette in the script tag

### Domain Setup (Optional)
To use a custom domain:
1. Add a `CNAME` file to your repository with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## Technologies Used

- HTML5
- Tailwind CSS (CDN)
- Google Fonts (Inter)
- Vanilla JavaScript for smooth scrolling

## Browser Support

This landing page supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. # treehousevc
