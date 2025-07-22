# Kevin Baker Personal Branding Website

A modern, professional personal branding website showcasing Kevin Baker's expertise in executive coaching, speaking, and conscious leadership.

## 🎯 Project Overview

This website serves as Kevin's digital presence, highlighting his:
- Executive coaching services
- Speaking engagements and topics
- Professional background and values
- Easy booking functionality via Microsoft Bookings

## 🚀 Features

- **Modern Design**: Google Cloud-inspired color scheme with clean, professional aesthetics
- **Responsive Layout**: Mobile-first design that works on all devices
- **Easy Navigation**: Intuitive user experience with clear call-to-actions
- **Booking Integration**: Seamless Microsoft Bookings integration for coaching sessions
- **Fast Performance**: Optimized for speed and accessibility
- **SEO Optimized**: Meta tags and structured content for search engines

## 📁 File Structure

```
src/
├── index.html          # Homepage
├── about.html          # About page
├── coaching.html       # Executive coaching services
├── speaking.html       # Speaking engagements
├── contact.html        # Contact and booking
├── css/
│   └── style.css       # Custom styles
├── js/
│   └── main.js         # Interactive functionality
├── images/
│   └── headshot.jpg    # Kevin's professional photo
└── assets/
    └── documents/      # Additional assets
```

## 🛠️ Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap 5.3+**: Responsive framework
- **Google Fonts**: Inter font family
- **Microsoft Bookings**: Appointment scheduling

## 🎨 Design System

### Color Palette
- **Primary Blue**: #1a73e8 (Google Cloud blue)
- **Secondary Blue**: #4285f4
- **Accent Green**: #34a853
- **Text Colors**: #202124 (dark), #5f6368 (medium), #80868b (light)
- **Background**: #f8f9fa (light gray)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Hierarchy**: Clear heading structure with proper contrast

## 📱 Pages

### 1. Homepage (`index.html`)
- Hero section with Kevin's photo and value proposition
- Service overview cards
- Clear call-to-action buttons

### 2. About (`about.html`)
- Professional background and mission
- Values and principles
- Current role at Improving

### 3. Coaching (`coaching.html`)
- Executive coaching services
- Target audience and approach
- What to expect from sessions
- Booking integration

### 4. Speaking (`speaking.html`)
- Speaking experience since 2014
- Popular topics and formats
- Event types and venues
- Booking process

### 5. Contact (`contact.html`)
- Microsoft Bookings integration
- Multiple contact methods
- LinkedIn profile link
- Response time expectations

## 🚀 Getting Started

### Local Development

1. **Clone or download** the project files
2. **Navigate** to the `src` directory
3. **Open** `index.html` in your web browser
4. **Test** all pages and functionality

### File Server (Recommended)

For the best experience, serve files through a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🌐 Deployment

### GitHub Pages

1. **Create** a new GitHub repository
2. **Upload** all files from the `src` directory to the repository
3. **Enable** GitHub Pages in repository settings
4. **Set** source to main branch
5. **Access** your site at `https://username.github.io/repository-name`

### Custom Domain

To use your custom domain (e.g., kevindbaker.com):

1. **Add** a `CNAME` file to the repository with your domain
2. **Configure** DNS settings with your domain provider
3. **Update** domain settings in GitHub Pages

### Other Hosting Options

- **Netlify**: Drag and drop the `src` folder
- **Vercel**: Connect your GitHub repository
- **AWS S3**: Upload files to S3 bucket with static website hosting
- **Traditional hosting**: Upload files via FTP

## 🔧 Customization

### Updating Content

- **Text content**: Edit HTML files directly
- **Images**: Replace `images/headshot.jpg` with new photos
- **Colors**: Modify CSS variables in `css/style.css`
- **Booking URL**: Update Microsoft Bookings URL in `js/main.js`

### Adding Features

- **Blog section**: Add new HTML pages and update navigation
- **Testimonials**: Create testimonials component
- **Newsletter signup**: Integrate email service
- **Analytics**: Add Google Analytics or other tracking

## 📊 Performance

### Optimization Features

- **Minified CSS and JS** (for production)
- **Optimized images** (compressed JPG)
- **Lazy loading** for images
- **CDN resources** (Bootstrap, Google Fonts)
- **Efficient animations** with CSS transforms

### Performance Targets

- **Load time**: < 3 seconds
- **Mobile score**: 90+ (Lighthouse)
- **Desktop score**: 95+ (Lighthouse)
- **Accessibility**: WCAG 2.1 AA compliant

## 🔒 Security

- **HTTPS only** for production
- **No sensitive data** in client-side code
- **External links** open in new tabs
- **Form validation** on client and server side

## 📈 SEO

### Meta Tags

- **Title tags**: Optimized for each page
- **Meta descriptions**: Compelling summaries
- **Open Graph**: Social media sharing
- **Structured data**: Schema markup for rich snippets

### Content Strategy

- **Keyword optimization**: Executive coaching, conscious leadership
- **Internal linking**: Strategic page connections
- **Alt text**: Descriptive image alt attributes
- **URL structure**: Clean, semantic URLs

## 🐛 Troubleshooting

### Common Issues

1. **Microsoft Bookings not working**
   - Verify the booking URL is correct
   - Check if popup blockers are enabled
   - Test in different browsers

2. **Images not loading**
   - Check file paths and names
   - Ensure images are in the correct directory
   - Verify file permissions

3. **Styling issues**
   - Clear browser cache
   - Check CSS file path
   - Verify Bootstrap CDN is accessible

### Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile browsers**: iOS Safari 14+, Chrome Mobile 90+

## 📞 Support

For technical support or questions about the website:

- **LinkedIn**: [Kevin Baker](https://www.linkedin.com/in/kevindbaker/)

## 📄 License

This project is created for Kevin Baker's personal branding website. All rights reserved.
