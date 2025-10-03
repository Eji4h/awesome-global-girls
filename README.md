# 🌟 Awesome Global Girls

[![Hacktoberfest 2025](https://img.shields.io/badge/Hacktoberfest-2025-blueviolet.svg)](https://hacktoberfest.com/)
[![Astro](https://img.shields.io/badge/Built%20with-Astro-FF5D01.svg)](https://astro.build)

A curated list of inspiring women from around the world making a difference in their fields. Built with Astro for Hacktoberfest! 🎃

🌐 ** Website**: [awesome-global-girls.com](https://awesome-global-girls.com)

## 🤝 Contributing

We welcome contributions for Hacktoberfest! Here's how you can contribute:

1. **Fork** this repository
2. **Add** an entry to `src/data/girls.json` following this format:

```json
{
  "name": "Full Name",
  "country": "Country",
  "field": "Field of Work",
  "link": "https://link-to-image.com",
  "image": "/images/Full_Name.jpg"
}
```

3. **Add an image** (optional but recommended):
   - Find a high-quality image of the person
   - Save the image to the `public/images/` directory
   - Use a descriptive filename: `FirstName_LastName.jpg` (e.g., `Marie_Curie.jpg`)
   - Supported formats: jpg, png, webp
   - Add the image path to the `image` field in your JSON entry
   - Example: `"image": "/images/Marie_Curie.jpg"`

4. **Commit** your changes:
```bash
git commit -m "Add [Name] to the list"
```

5. **Push** to your fork and submit a **Pull Request**

### Contribution Guidelines

- Add real, inspiring women who have made significant contributions
- Provide accurate information
- Include a reliable source link (link) - Wikipedia, official site, or credible source
- **Image Requirements:**
  - Save images to the `public/images/` directory
  - Use descriptive filenames: `FirstName_LastName.jpg` format
  - Supported formats: jpg, png, webp
  - Use high-quality images (at least 200x200 pixels recommended)
  - Ensure the image is properly licensed for use
  - Avoid copyrighted images without permission
  - Reference the image in JSON as: `"/images/FirstName_LastName.jpg"`
- Ensure the JSON is properly formatted
- Ensure entries are sorted in alphabetical order by name

## 🛠️ Built With

- [Astro](https://astro.build/) - The web framework
- [Tailwind CSS](https://tailwindcss.com/) + [DaisyUI](https://daisyui.com/) - Styling
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- JSON for data storage

## 📜 License

This project is open source and available under the MIT License.

## 🎃 Hacktoberfest

This project is participating in Hacktoberfest! Check out the [official Hacktoberfest website](https://hacktoberfest.com/) to learn more about contributing to open source.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or pnpm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Eji4h/awesome-global-girls.git
cd awesome-global-girls
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Start the development server:
```bash
npm run dev
# or
pnpm dev
```

4. Open your browser and visit `http://localhost:4321`

## 📁 Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── images/             # Directory for contributor images
├── src/
│   ├── data/
│   │   └── girls.json      # The main data file with the list
│   └── pages/
│       └── index.astro     # Main page
├── astro.config.mjs
├── package.json
└── tsconfig.json
```


Made with ❤️ for Hacktoberfest
