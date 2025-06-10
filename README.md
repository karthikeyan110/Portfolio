#  Portfolio Website

A sleek, modern portfolio website built with Next.js, TypeScript, and Tailwind CSS. Features interactive animations, particle backgrounds, and a responsive design showcasing technical skills and professional presence.

## 🚀 Features

- **Modern Design**: Dark theme with red accent colors and glassmorphism effects
- **Interactive Animations**: Custom cursor, particle background, and smooth transitions
- **Responsive Layout**: Mobile-first design that works on all devices
- **Performance Optimized**: Built with Next.js for fast loading and SEO
- **TypeScript**: Type-safe development for better code quality
- **Accessibility**: WCAG compliant with proper semantic HTML

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Custom SVG icons
- **Animations**: CSS animations and transitions
- **Deployment**: Vercel (recommended)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/karthikeyan110/modern-portfolio.git
cd modern-portfolio
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🎨 Customization

### Personal Information

Update the following files with your information:

- `components/hero.tsx` - Name and title
- `components/about.tsx` - About description
- `components/social-apps.tsx` - Social media links
- `components/contact.tsx` - Contact information
- `components/projects.tsx` - Project details

### Styling

The design uses a consistent color scheme defined in Tailwind CSS:

- **Primary**: Red (#EF4444)
- **Secondary**: Cyan (#4ECDC4)
- **Background**: Black (#000000)
- **Text**: White/Gray variants

To change colors, update the Tailwind classes throughout the components.

### Skills Section

Modify `components/services.tsx` to update your technical skills:

```typescript
const skills = [
  {
    icon: "🤖",
    title: "Your Skill",
    description: "Your skill description",
    color: "from-purple-500 to-pink-500",
  },
  // Add more skills...
]
```

## 📁 Project Structure

```
├── app/
│   ├── globals.css          # Global styles and animations
│   ├── layout.tsx           # Root layout component
│   └── page.tsx             # Main page component
├── components/
│   ├── about.tsx            # About section
│   ├── contact.tsx          # Contact section
│   ├── custom-cursor.tsx    # Custom cursor component
│   ├── header.tsx           # Navigation header
│   ├── hero.tsx             # Hero section
│   ├── particle-background.tsx # Particle animation system
│   ├── projects.tsx         # Projects showcase
│   ├── scroll-progress.tsx  # Scroll progress indicator
│   ├── services.tsx         # Skills/services section
│   └── social-apps.tsx      # Social media links
├── public/
│   └── images/              # Static images
└── README.md
```

## 🎯 Key Components

### Particle Background
Interactive particle system that responds to mouse movement:
- 150 animated particles with connections
- Mouse attraction effects
- Performance optimized with canvas rendering

### Custom Cursor
Blend-mode cursor that changes based on hover states:
- Different sizes for different elements
- Smooth following animation
- Hidden on mobile devices

### Social Apps
Clean social media integration:
- LinkedIn, GitHub, and Email links
- Hover animations and platform colors
- Professional SVG icons

### Skills Section
Technical skills showcase:
- 8 programming languages/technologies
- Animated progress indicators
- Gradient color schemes for each skill

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with zero configuration

### Other Platforms

The site can be deployed to any platform that supports Next.js:

- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Karthikeyan Pandita**
- LinkedIn: [Karthikeyan Pandita](https://linkedin.com/in/karthikeyan-pandita-900a7a287)
- GitHub: [@karthikeyan110](https://github.com/karthikeyan110)
- Email: 110karthikeyan@gmail.com

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Particle system inspired by interactive web experiences
- Icons and animations from various open-source projects

---
