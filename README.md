# NextJs-temp
A simple, organized nextjs template for having a quick start on projects. 

## Why?
It's simple, I need a quick start when I'm working in a hackathon. 

Using this template gives me a head start. 

## How to run this?
First, you'll have to install everything needed. 

```npm install react react-dom next```

Then in order to simply run the program, you type 
```npm run dev```

## How to use this template?

First, let's look at the important files in the folder structure:

NextJs-temp/
├── README.md
├── public/
│   └── ...static assets (images, icons, etc.)
├── src/
│   ├── app/
│   │   ├── **layout.tsx**      # Root layout 
│   │   ├── **globals.css**     # Global CSS, theme variables, font imports. (Change these how you like)
│   ├── components/
│   │   ├── **Navbar.tsx**      # Navigation bar (site-wide)
│   │   ├── **Footer.tsx**      # Footer (site-wide)
│   │   ├── **Logobar.tsx**     # Logo/settings bar (site-wide)
│   │   ├── styles/          # Folder for storing component's css files.  
|   |   |   ├── **Navbar.module.css** # The css file for the Navbar component. 
|   |   |   ├── **Logobar.module.css** # The css file for the Logobar component. 
|   |   |   ├── **Footer.module.css** # The css file for the Footer component. 
│   ├── fonts/
│   │   ├── **QuickingRegular.otf**     # Font for body (add more fonts as you wish. I personally love these)
│   │   ├── **GobittaRegular.otf**      # Font for heading text 
│   ├── pages/ # Add whatever pages you need here

