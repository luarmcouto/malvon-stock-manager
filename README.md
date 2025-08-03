# 🥟 Malvón Stock Manager

> Progressive Web App for inventory management at Malvón Empanadas. Track stock levels, manage batches, and monitor production with real-time updates and offline functionality.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://malvon-stock-manager.vercel.app)
[![PWA](https://img.shields.io/badge/PWA-enabled-purple)](https://web.dev/progressive-web-apps/)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

## ✨ Features

### 📊 **Stock Management**
- Real-time inventory tracking for 21+ empanada flavors
- Organized by categories: Vegan, Classic, and Gourmet
- Color-coded status indicators (In Stock, Low Stock, Out of Stock)
- Instant stock level updates

### 🍳 **Production Control**
- **Batch Entry**: Record new production batches
- **Cooking Batches**: Track empanadas sent for cooking
- **Loss Management**: Record spoiled or damaged items
- Complete operation history with timestamps

### 📱 **Progressive Web App**
- **Offline Functionality**: Works without internet connection
- **Native App Experience**: Install on any device
- **Responsive Design**: Perfect on mobile, tablet, and desktop
- **Local Storage**: All data saved securely on device

### 📈 **Analytics Dashboard**
- Total stock overview
- Low stock alerts (< 80 units)
- Out of stock notifications
- Expandable detailed views

## 🚀 Live Demo

**[👉 Try the app now](https://malvon-stock-manager.vercel.app)**

### Install as App:
1. Open the link above
2. Look for the install icon (➕) in your browser
3. Click "Install Malvón Stock Manager"
4. Use it like a native app!

## 📱 Screenshots

### Desktop View
![Desktop Dashboard](https://via.placeholder.com/800x450/f3f4f6/1f2937?text=Desktop+Dashboard)

### Mobile View
![Mobile Interface](https://via.placeholder.com/300x600/f3f4f6/1f2937?text=Mobile+Interface)

## 🛠️ Technology Stack

- **Frontend**: React 18 with Hooks
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Storage**: Local Storage API
- **PWA**: Service Worker + Web App Manifest
- **Deployment**: Vercel

## 📋 Empanada Flavors

### 🌱 Vegan
- Humita Vegana

### 🥩 Classic (8 flavors)
- Kebab
- Carne Suave
- Carne Picante
- Fiambre Queijo
- Atum
- Cebola e Queijo
- Cheese Bacon
- Frango Especial

### 🍷 Gourmet (12 flavors)
- Roquefort Pera
- Mortadela Pistacio
- Oh My Goat
- Cochinita
- Smash Burger
- Caprese
- Assado Especial
- Rabo de Boi
- Costelinha BBG
- Frango Thai
- Bochecha Especial
- Provolone e Tomate Seco

## 🎯 How to Use

### Stock Management
1. **View Current Stock**: Click "Estoque Atual" to see all inventory
2. **Add Inventory**: Click "Entrada" → Enter quantities → Save
3. **Record Cooking**: Click "Fornada" → Select items to cook → Save
4. **Report Losses**: Click "Rutura" → Enter damaged quantities → Save

### Analytics
1. **Dashboard**: Click "Dashboard" for overview
2. **Total Stock**: Click total to see all items with status
3. **Filter History**: Use filters to view specific operations

## 🔧 Local Development

### Prerequisites
- Modern web browser
- Local web server (Live Server, Python, etc.)

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/malvon-stock-manager.git
   cd malvon-stock-manager
   ```

2. **Start local server**
   
   **Option A: Python**
   ```bash
   python -m http.server 8000
   ```
   
   **Option B: VS Code Live Server**
   - Install Live Server extension
   - Right-click `index.html` → "Open with Live Server"

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### File Structure
```
malvon-stock-manager/
├── index.html          # Main application
├── manifest.json       # PWA configuration
├── sw.js              # Service worker
├── logo-header.png     # Header logo
├── logo-background.png # Background logo
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # Documentation
```

## 🌍 Browser Support

| Browser | Desktop | Mobile |
|---------|---------|---------|
| Chrome  | ✅      | ✅      |
| Firefox | ✅      | ✅      |
| Safari  | ✅      | ✅      |
| Edge    | ✅      | ✅      |

## 📦 Deployment

### Vercel (Recommended)
1. Fork this repository
2. Connect to [Vercel](https://vercel.com)
3. Deploy automatically from GitHub
4. Your PWA is live!

### Other Platforms
- **Netlify**: Drag & drop deployment
- **GitHub Pages**: Enable in repository settings
- **Firebase Hosting**: `firebase deploy`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines
1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Malvón

Malvón specializes in authentic Argentine empanadas, crafted with traditional recipes and premium ingredients. This stock management system helps maintain quality and efficiency in our production process.

**Empanadas Argentinas - Confeccionadas à Mão**

## 🔗 Links

- **Live App**: [malvon-stock-manager.vercel.app](https://malvon-stock-manager.vercel.app)
- **Repository**: [GitHub](https://github.com/yourusername/malvon-stock-manager)
- **Issues**: [Report Bug](https://github.com/yourusername/malvon-stock-manager/issues)
- **Feature Requests**: [Suggest Feature](https://github.com/yourusername/malvon-stock-manager/issues)

---

<div align="center">
  <strong>Made with ❤️ for Malvón Empanadas</strong>
</div>
