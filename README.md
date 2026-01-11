# Personal Portfolio

A modern, responsive personal portfolio website built with React.js and Tailwind CSS featuring smooth animations and interactive elements.

## Features

- **Modern Design**: Clean, professional layout with gradient accents
- **Responsive**: Fully responsive design that works on all devices
- **Smooth Animations**: CSS and JavaScript animations for enhanced user experience
- **Interactive Elements**: Hover effects, typing animation, and scroll-triggered animations
- **Contact Form**: Functional contact form with validation
- **Skills Visualization**: Animated skill bars and progress indicators
- **Project Showcase**: Filterable project gallery
- **Performance Optimized**: Fast loading with optimized images and code

## Technologies Used

- **Frontend**: React.js, HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Build Tool**: Create React App
- **Animations**: CSS animations, Intersection Observer API
- **Icons**: Custom SVG icons
- **Fonts**: Google Fonts (Inter)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd personal-portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Copy your images:
   - Copy `12.jpg` (profile image) to `public/12.jpg`
   - Copy `22.jpg` (background image) to `public/22.jpg`

4. Start the development server:
```bash
npm start
```

5. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Customization

### Personal Information
Update the following files with your personal information:
- `src/components/Hero.js` - Name, titles, and introduction
- `src/components/About.js` - About section content and stats
- `src/components/Skills.js` - Your skills and proficiency levels
- `src/components/Projects.js` - Your projects and descriptions
- `src/components/Contact.js` - Contact information
- `src/components/Footer.js` - Footer content and social links

### Images
- Replace `public/12.jpg` with your profile picture
- Replace `public/22.jpg` with your preferred background image

### Colors and Styling
The color scheme can be customized in:
- `tailwind.config.js` - Extend the theme with custom colors
- `src/index.css` - Custom CSS classes and animations

## Project Structure

```
src/
├── components/
│   ├── Header.js          # Navigation header
│   ├── Hero.js            # Hero section with intro
│   ├── About.js           # About section
│   ├── Skills.js          # Skills showcase
│   ├── Projects.js        # Projects gallery
│   ├── Contact.js         # Contact form
│   └── Footer.js          # Footer
├── App.js                 # Main app component
├── index.js              # Entry point
└── index.css             # Global styles
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Deployment

### Build for Production
```bash
npm run build
```

The build folder will contain the optimized production build ready for deployment.

### Deploy to Netlify/Vercel
1. Build the project: `npm run build`
2. Deploy the `build` folder to your preferred hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Feel free to reach out if you have any questions or suggestions!

- Email: john.doe@example.com
- LinkedIn: [linkedin.com/in/johndoe](https://linkedin.com/in/johndoe)
- GitHub: [github.com/johndoe](https://github.com/johndoe)