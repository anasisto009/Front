#  Padel Finder

A modern, responsive web application for finding padel courts across Morocco's major cities.

##  Features

-  **User Authentication** - Register and login system
-  **City Selection** - Browse courts in Casablanca, Rabat, Marrakech, and Fes
-  **Terrain Listings** - View available padel courts with detailed information
-  **Map Integration** - Location cards for each terrain (ready for Google Maps)
-  **Contact System** - Contact form for inquiries
-  **Fully Responsive** - Works perfectly on all devices
-  **Modern Design** - Beautiful UI with gradient colors and smooth animations
-  **Animated Navbar** - Toggle menu with smooth animations



### Installation

1. Navigate to the project directory:
```bash
cd Front
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4.  `http://localhost:5173`

##  Project Structure



     FIRST VIEW OF THE Code (i did modification and i add pages(matches,Friends,) i add also a google maps from google cloud (api key). 
```
Front/
├── src/
│   ├── components/       # Reusable components
│   │   ├── Navbar.jsx    # Animated navigation bar
│   │   ├── Button.jsx    # Custom button component
│   │   └── Input.jsx     # Custom input component
│   ├── pages/            # Page components
│   │   ├── Home.jsx      # Homepage with city selection
│   │   ├── Login.jsx     # Login page
│   │   ├── Register.jsx  # Registration page
│   │   ├── Terrains.jsx  # Terrain listing by city
│   │   ├── TerrainDetail.jsx  # Individual terrain details
│   │   ├── Contact.jsx   # Contact page
│   │   └── Dashboard.jsx # User dashboard
│   ├── data/
│   │   └── terrains.js   # Mock data for terrains
│   ├── App.jsx           # Main app component with routing
│   └── main.jsx          # Entry point
└── package.json
```

##  Design Features

- **Color Scheme**: Modern gradient design with primary (blue) and accent (purple) colors
- **Responsive**: Mobile-first design that works on all screen sizes
- **Animations**: Smooth transitions and hover effects
- **Clean UI**: Minimalist design with excellent UX

##  Available Cities(changeable) avec des frais qui sont logiques et reels 

- **Casablanca** - 2 terrains
- **Rabat** - 2 terrains
- **Marrakech** - 1 terrain
- **Fes** - 1 terrain

## 🔧 Tech Stack

- **React** - UI library
- **Vite** - Build tool
- **React Router** - Routing
- **Tailwind CSS** - Styling
- **Local Storage** - Authentication persistence

##  Notes

- Currently uses mock data for terrains
- Authentication is client-side only (ready for backend integration)
- Map integration placeholder is ready for (Google Maps API)
- All forms include validation




---

BY ANAS ELMARDI ET ZAKARIA EDDARRAZ
