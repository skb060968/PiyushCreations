# Seema Didi Fashion - Indian Fashion Portfolio Website

A modern, responsive Indian fashion portfolio website built with Next.js 14, TypeScript, and Tailwind CSS.

## Features

- **Modern Design**: Clean, minimalist design that puts the focus on the fashion work
- **Responsive**: Fully responsive design that works on all devices
- **Fast Performance**: Optimized images and modern web technologies
- **SEO Optimized**: Built-in SEO optimization with proper meta tags
- **Interactive Components**: Smooth animations and hover effects
- **Contact Form**: Functional contact form with validation
- **Portfolio Gallery**: Filterable portfolio gallery with categories

## Pages

- **Homepage**: Hero section, featured Indian fashion work, about preview, services, testimonials, contact
- **Portfolio**: Complete portfolio gallery with Indian fashion categories (Bridal, Saree, Celebrity, Festival)
- **About**: Detailed about page with Indian fashion experience, awards, and philosophy
- **Services**: Comprehensive Indian fashion services page with pricing in INR and process
- **Contact**: Contact form with Indian fashion project inquiry details and FAQ

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Images**: Next.js Image optimization
- **Fonts**: Google Fonts (Playfair Display, Inter)

## Getting Started

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Run the development server**:
   ```bash
   npm run dev
   ```

3. **Open your browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

## Build for Production

```bash
npm run build
npm start
```

## Customization

### Colors
The website uses a custom color palette defined in `tailwind.config.js`:
- `fashion-gold`: #D4AF37
- `fashion-black`: #1a1a1a
- `fashion-gray`: #f5f5f5

### Images
Replace the placeholder images with actual Indian fashion portfolio images. Update the image URLs in:
- `components/Hero.tsx` - Indian fashion hero image
- `components/FeaturedWork.tsx` - Bridal, saree, and ethnic wear images
- `components/About.tsx` - Professional portrait in Indian attire
- `app/portfolio/page.tsx` - Complete Indian fashion portfolio

### Content
Update the content in each component to reflect actual information:
- Personal details and bio for Seema Didi
- Indian fashion portfolio projects and descriptions
- Services and pricing in INR
- Contact information and location
- Client testimonials from Indian fashion industry

## Deployment

This website can be deployed on:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **AWS Amplify**
- Any hosting service that supports Node.js

## Performance Features

- Image optimization with Next.js Image component
- Lazy loading for images
- Optimized fonts loading
- Minimal JavaScript bundle
- CSS optimization with Tailwind

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is for portfolio use. Please customize with your own content and branding.