# CodeStart - Programming Course Landing Page

A responsive landing page for a beginner programming course, built with React and Tailwind CSS with Stripe Payment Links integration.

![CodeStart Landing Page](https://picsum.photos/800/400)

## Overview

This project is a complete landing page for selling a coding course. It features a clean, light design with multiple sections to showcase course features, curriculum, instructor information, pricing options, and more. The page is fully responsive and works on all device sizes.

## Technologies Used

- **React** - For component-based UI development
- **Tailwind CSS** - For responsive styling
- **Font Awesome** - For icons
- **Stripe Payment Links** - For payment processing (placeholder integration)

## Features

- **Responsive Design** - Looks great on mobile, tablet, and desktop
- **Interactive Navigation** - Smooth scrolling to page sections
- **Multiple Content Sections**:
  - Hero section with call-to-action
  - Course features overview
  - Detailed curriculum breakdown
  - Instructor profile
  - Three-tier pricing structure
  - Student testimonials
  - Frequently asked questions
  - Call-to-action sections
- **Placeholder for Stripe Payment Integration**

## Setup Instructions

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript

### Quick Start

1. Clone the repository:
   ```
   git clone https://github.com/svpino/factory-sample.git
   cd factory-sample
   ```

2. Open the `index.html` file in your browser:
   ```
   open index.html
   ```

3. That's it! The landing page uses CDN links for React, Tailwind, and other dependencies, so no build process is required for basic viewing.

### Development Setup

For active development with hot reloading:

1. Install a simple development server like `live-server`:
   ```
   npm install -g live-server
   ```

2. Run the server in the project directory:
   ```
   live-server
   ```

## Customization

### Content Customization

Most content can be modified directly in the React components:

- Update course details in the respective component sections
- Modify pricing tiers in the `Pricing` component
- Change testimonials in the `Testimonials` component
- Update FAQ items in the `FAQ` component

### Styling Customization

The project uses Tailwind CSS for styling:

- Modify colors by changing the color classes (e.g., `bg-blue-600` to `bg-green-600`)
- Adjust spacing with Tailwind's spacing utilities
- Change fonts by adding custom font imports and updating font classes

## Stripe Integration

The landing page includes placeholder buttons for Stripe Payment Links. To connect actual payment processing:

1. Create a [Stripe](https://stripe.com) account if you don't have one
2. Set up Payment Links in the Stripe Dashboard
3. Replace the placeholder buttons with your actual Payment Link URLs:
   ```jsx
   <button className="mt-8 block w-full bg-blue-600 border border-transparent rounded-md py-3 px-6 text-center font-medium text-white hover:bg-blue-700">
     <a href="YOUR_STRIPE_PAYMENT_LINK_HERE">Get Started</a>
   </button>
   ```

## Deployment

### Basic Deployment

For simple static hosting:

1. Upload the `index.html` file to any web hosting service
2. Ensure all CDN links are accessible from your hosting environment

### Advanced Deployment

For production environments:

1. Consider extracting the React components to separate files
2. Set up a build process with Webpack or Create React App
3. Use environment variables for Stripe keys
4. Deploy to services like Netlify, Vercel, or GitHub Pages

## License

This project is available for personal and commercial use.

## Credits

- Placeholder images from [Picsum Photos](https://picsum.photos)
- Icons from [Font Awesome](https://fontawesome.com)
- React and Tailwind CSS via CDN
