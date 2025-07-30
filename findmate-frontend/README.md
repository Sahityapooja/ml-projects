# FindMate - AI-Powered Lost & Found Assistant

A responsive Next.js application built with Tailwind CSS that helps people reunite with their lost items through intelligent AI-powered matching technology.

## Features

### 🎯 Core Functionality
- **Report Lost Items**: Users can submit details about lost items with photos and location
- **Report Found Items**: Users can report items they've found to help reunite them with owners
- **AI-Powered Matching**: Intelligent matching engine analyzes item characteristics, location, and timing
- **Instant Notifications**: Real-time notifications when matches are found

### 🎨 Design & User Experience
- **Responsive Design**: Mobile-first approach with seamless desktop experience
- **Modern UI**: Clean, professional design with Cognizant branding
- **Intuitive Navigation**: Clear user flow through the 3-step process
- **Accessibility**: Built with accessibility best practices

### 📱 Layout Components
- **Header**: Cognizant logo and navigation menu
- **Hero Section**: Eye-catching title and call-to-action buttons
- **Process Section**: Visual 3-step guide (Report → Match → Notify)
- **Footer**: Contact information and helpful links

## Technology Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Icons**: Heroicons (SVG)
- **Deployment Ready**: Optimized for production

## Getting Started

### Prerequisites
- Node.js 18.0 or later
- npm or yarn package manager

### Installation

1. **Clone and navigate to the project**:
   ```bash
   cd findmate-frontend
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Project Structure

```
findmate-frontend/
├── src/
│   ├── app/
│   │   ├── globals.css          # Global styles and Tailwind imports
│   │   ├── layout.tsx           # Root layout component
│   │   └── page.tsx             # Main homepage component
│   └── ...
├── public/                      # Static assets
├── tailwind.config.ts          # Tailwind CSS configuration
├── next.config.ts              # Next.js configuration
└── package.json                # Dependencies and scripts
```

## Key Components

### Header
- Responsive navigation with Cognizant branding
- Mobile-friendly hamburger menu
- Clean, professional styling

### Hero Section
- Gradient background with compelling messaging
- Two prominent CTA buttons for lost/found reporting
- Responsive typography and spacing

### 3-Step Process
- Visual workflow explanation
- Interactive elements and animations
- Mobile-optimized grid layout

### Footer
- Contact information and support links
- Company branding and copyright
- Organized link sections

## Responsive Design

The application is built with a mobile-first approach:

- **Mobile (< 768px)**: Single column layout, stacked elements
- **Tablet (768px - 1024px)**: Optimized spacing and typography
- **Desktop (> 1024px)**: Full multi-column layout with enhanced visuals

## Customization

### Colors
The design uses a blue color scheme reflecting Cognizant's branding:
- Primary: Blue (600-800 range)
- Secondary: Gray (50-900 range)
- Accent: Green for success states

### Typography
- Modern system font stack
- Responsive font sizes using Tailwind's responsive utilities
- Proper hierarchy and spacing

## Future Enhancements

Potential features for future development:
- User authentication and profiles
- Advanced search and filtering
- Real-time chat for matched items
- Mobile app with push notifications
- Integration with social media platforms
- Multi-language support

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly on different devices
5. Submit a pull request

## License

This project is built for Cognizant Technology Solutions as a demonstration of modern web development capabilities.

## Support

For questions or support, please contact:
- Email: support@findmate.com
- Phone: 1-800-FINDMATE

---

**Built with ❤️ by Cognizant Technology Solutions**
