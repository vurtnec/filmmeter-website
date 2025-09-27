# FilmMeter Website

Official website for FilmMeter - Professional iOS Light Meter for Film Photography.

This repository contains the GitHub Pages website that serves as the official web presence for the FilmMeter iOS application, required for App Store submission.

## Website URL

**Production**: `https://zacharyhou.github.io/filmmeter-website`
*(Update with your actual GitHub username/organization)*

## Structure

```
filmmeter-website/
├── _config.yml           # Jekyll configuration
├── index.md             # Landing page
├── privacy-policy.md    # Privacy policy (App Store requirement)
├── support.md           # Support and contact information
├── assets/
│   └── css/
│       └── style.scss   # Custom red-black-white theme
└── README.md           # This file
```

## Features

- **Professional Design**: Clean, minimalist layout inspired by darkroom aesthetics
- **Custom Theme**: Red-black-white color scheme matching the FilmMeter app
- **Responsive**: Mobile-friendly design using Jekyll Minima theme
- **App Store Compliant**: Includes required privacy policy and support pages
- **Fast Loading**: Optimized for GitHub Pages hosting

## Development

### Local Development

1. Install Jekyll:
   ```bash
   gem install bundler jekyll
   ```

2. Clone and setup:
   ```bash
   git clone https://github.com/zacharyhou/filmmeter-website.git
   cd filmmeter-website
   bundle install
   ```

3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

### Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

## Content Guidelines

### Brand Colors
- **Primary Red**: `#dc2626`
- **Black**: `#000000`
- **White**: `#ffffff`
- **Dark Gray**: `#374151`

### Writing Style
- Professional but approachable
- Focus on film photography audience
- Technical accuracy for camera/exposure content
- Clear, concise explanations

## Pages

### Landing Page (`index.md`)
- App overview and key features
- Technical specifications
- Download information
- Links to support pages

### Privacy Policy (`privacy-policy.md`)
- App Store requirement
- Covers camera access, location data, local storage
- GDPR/CCPA compliant language
- Last updated date tracking

### Support (`support.md`)
- FAQ section
- Contact information
- Troubleshooting guides
- Community links

## Customization

### Jekyll Configuration (`_config.yml`)
- Site metadata and SEO settings
- Navigation structure
- Plugin configuration
- Author and contact information

### Custom Styling (`assets/css/style.scss`)
- FilmMeter brand colors
- Darkroom-inspired aesthetic
- Responsive breakpoints
- Print styles

## Requirements

- **Jekyll**: Static site generator
- **GitHub Pages**: Free hosting
- **Minima Theme**: Base theme with customizations

## App Store Integration

This website fulfills App Store Connect requirements:
- **Website URL**: Required field in app submission
- **Privacy Policy**: Accessible public link
- **Support URL**: User assistance and contact

## Maintenance

### Regular Updates
- Update app version information
- Refresh screenshots when app updates
- Monitor and respond to support requests
- Keep privacy policy current with app changes

### Analytics (Optional)
Consider adding Google Analytics or similar to track:
- Page views and user engagement
- Geographic distribution of visitors
- Popular support topics

## Legal

- All content related to FilmMeter app
- Privacy policy covers iOS app functionality
- Contact information for legal compliance
- Regular review for accuracy and compliance

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes following brand guidelines
4. Test locally with Jekyll
5. Submit pull request with clear description

## License

Content and design © 2025 Zachary Hou. All rights reserved.

---

**Contact**: For website issues or content updates, create an issue in this repository or contact support@filmmeter.app