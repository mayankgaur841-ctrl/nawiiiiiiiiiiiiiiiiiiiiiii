# OIML R 76-1:2006 & R 76-2:2007 NAWI TEST REPORT GENERATOR & REPOSITORY
### Complete Consolidated Codebase & Project Files
**Ministry of Consumer Affairs, Food & Public Distribution | Directorate of Legal Metrology, Government of India**
*Generated: 2026-10-24T08:35:22.543Z*

---

## 📋 Table of Contents & File Index

| # | Relative Path | Type | Size (Bytes) | Description |
|---|---|---|---|---|
| 1 | [.env.example](#file-1--env-example) | `.example` | 161 | Environment Variables Template for Gemma 4 API Key |
| 2 | [.gitignore](#file-2--gitignore) | `file` | 253 | Source File |
| 3 | [.oxlintrc.json](#file-3--oxlintrc-json) | `.json` | 245 | Source File |
| 4 | [Dockerfile](#file-4-dockerfile) | `file` | 361 | Source File |
| 5 | [index.html](#file-5-index-html) | `.html` | 1,424 | Source File |
| 6 | [netlify.toml](#file-6-netlify-toml) | `.toml` | 120 | Source File |
| 7 | [nginx.conf](#file-7-nginx-conf) | `.conf` | 701 | Source File |
| 8 | [package.json](#file-8-package-json) | `.json` | 733 | Project Dependencies & Scripts |
| 9 | [public/favicon.svg](#file-9-public-favicon-svg) | `.svg` | 9,522 | Source File |
| 10 | [public/icons.svg](#file-10-public-icons-svg) | `.svg` | 5,031 | Source File |
| 11 | [README.md](#file-11-readme-md) | `.md` | 1,278 | Project Documentation & Architecture Guide |
| 12 | [src/App.css](#file-12-src-app-css) | `.css` | 40,460 | Complete CSS Design Tokens & Print Stylesheet |
| 13 | [src/App.tsx](#file-13-src-app-tsx) | `.tsx` | 17,384 | Main Controller, Persistence & State Management |
| 14 | [src/assets/hero.png](#file-14-src-assets-hero-png) | `.png` | 13,057 | Source File |
| 15 | [src/assets/react.svg](#file-15-src-assets-react-svg) | `.svg` | 4,126 | Source File |
| 16 | [src/assets/vite.svg](#file-16-src-assets-vite-svg) | `.svg` | 8,709 | Source File |
| 17 | [src/components/AICopilotDrawer.tsx](#file-17-src-components-aicopilotdrawer-tsx) | `.tsx` | 19,766 | Context-Aware Metrology AI Copilot Chat Drawer |
| 18 | [src/components/AISettingsModal.tsx](#file-18-src-components-aisettingsmodal-tsx) | `.tsx` | 14,766 | Gemma 4 API Key Management & Connection Tester Modal |
| 19 | [src/components/Dashboard.tsx](#file-19-src-components-dashboard-tsx) | `.tsx` | 17,290 | Repository Hub, KPI Cards & Accuracy Class Filters |
| 20 | [src/components/DocumentationModal.tsx](#file-20-src-components-documentationmodal-tsx) | `.tsx` | 15,812 | OIML R 76-1 Reference Handbook & Formulas |
| 21 | [src/components/EccentricityDiagram.tsx](#file-21-src-components-eccentricitydiagram-tsx) | `.tsx` | 8,224 | Platform Eccentricity Visual Receptor with Corner Nodes |
| 22 | [src/components/InteractiveErrorCurve.tsx](#file-22-src-components-interactiveerrorcurve-tsx) | `.tsx` | 11,245 | Interactive SVG Error Curve with MPE Corridor |
| 23 | [src/components/Navbar.tsx](#file-23-src-components-navbar-tsx) | `.tsx` | 6,025 | Header with Indian Emblem, Role Switcher & AI Status |
| 24 | [src/components/ReportEditor.tsx](#file-24-src-components-reporteditor-tsx) | `.tsx` | 87,438 | 7-Tab Testing Workbench & OIML Evaluation Form |
| 25 | [src/index.css](#file-25-src-index-css) | `.css` | 2,683 | Source File |
| 26 | [src/main.tsx](#file-26-src-main-tsx) | `.tsx` | 230 | Source File |
| 27 | [src/types/oiml.ts](#file-27-src-types-oiml-ts) | `.ts` | 6,802 | TypeScript Type Definitions & OIML R 76 Schema |
| 28 | [src/utils/aiService.ts](#file-28-src-utils-aiservice-ts) | `.ts` | 13,240 | Gemma 4 & Gemini AI Integration & Dual API Caller |
| 29 | [src/utils/docxExport.ts](#file-29-src-utils-docxexport-ts) | `.ts` | 7,007 | Word (.docx) Report Generator with Tables |
| 30 | [src/utils/metrologyEngine.ts](#file-30-src-utils-metrologyengine-ts) | `.ts` | 15,205 | Metrological Calculation Engine (MPE Table 6, True Indication, Ec, n) |
| 31 | [src/utils/pdfExport.ts](#file-31-src-utils-pdfexport-ts) | `.ts` | 19,816 | Multi-page Official OIML R 76-2 PDF Exporter |
| 32 | [src/utils/sampleData.ts](#file-32-src-utils-sampledata-ts) | `.ts` | 37,367 | 4 Reference NAWI Instruments Benchmark Dataset |
| 33 | [start.bat](#file-33-start-bat) | `.bat` | 240 | Source File |
| 34 | [tsconfig.app.json](#file-34-tsconfig-app-json) | `.json` | 655 | Source File |
| 35 | [tsconfig.json](#file-35-tsconfig-json) | `.json` | 119 | Source File |
| 36 | [tsconfig.node.json](#file-36-tsconfig-node-json) | `.json` | 558 | Source File |
| 37 | [vercel.json](#file-37-vercel-json) | `.json` | 183 | Source File |
| 38 | [vite.config.ts](#file-38-vite-config-ts) | `.ts` | 161 | Vite Build & Bundler Config |

---

## 📂 Complete File Contents

### File 1: `.env.example`
*Path: `.env.example` | Size: 161 bytes | Environment Variables Template for Gemma 4 API Key*

```bash
# Gemma 4 & Gemini API Configuration
# Get your API key from Google AI Studio: https://aistudio.google.com/app/apikey
VITE_GEMMA_API_KEY=your_gemma_api_key_here

```

---

### File 2: `.gitignore`
*Path: `.gitignore` | Size: 253 bytes | Source File*

```text
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
lerna-debug.log*

node_modules
dist
dist-ssr
*.local

# Editor directories and files
.vscode/*
!.vscode/extensions.json
.idea
.DS_Store
*.suo
*.ntvs*
*.njsproj
*.sln
*.sw?

```

---

### File 3: `.oxlintrc.json`
*Path: `.oxlintrc.json` | Size: 245 bytes | Source File*

```json
{
  "$schema": "./node_modules/oxlint/configuration_schema.json",
  "plugins": ["react", "typescript", "oxc"],
  "rules": {
    "react/rules-of-hooks": "error",
    "react/only-export-components": ["warn", { "allowConstantExport": true }]
  }
}

```

---

### File 4: `Dockerfile`
*Path: `Dockerfile` | Size: 361 bytes | Source File*

```text
# Step 1: Build the Vite production bundle
FROM node:20-alpine AS builder
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
RUN npm run build

# Step 2: Serve with lightweight Nginx web server
FROM nginx:alpine
COPY --from=builder /app/dist /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

```

---

### File 5: `index.html`
*Path: `index.html` | Size: 1424 bytes | Source File*

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='%230f2b48' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'><path d='m16 16 3-8 3 8c-.87.65-1.92 1-3 1s-2.13-.35-3-1Z'/><path d='m2 16 3-8 3 8c-.87.65-1.92 1-3 1s-2.13-.35-3-1Z'/><path d='M7 21h10'/><path d='M12 3v18'/><path d='M3 7h2c2 0 5-1 7-2 2 1 5 2 7 2h2'/></svg>" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>OIML R 76 NAWI Test Report Generator & Type Evaluation System | Legal Metrology India</title>
    <meta name="description" content="Official Legal Metrology Type Evaluation & Test Report Generation System for Non-Automatic Weighing Instruments (NAWI) conforming to OIML R 76-1:2006 and OIML R 76-2:2007." />
    <!-- Google Fonts: Inter, Outfit, JetBrains Mono -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600;700&family=Outfit:wght@500;600;700;800&display=swap" rel="stylesheet" />
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>

```

---

### File 6: `netlify.toml`
*Path: `netlify.toml` | Size: 120 bytes | Source File*

```text
[build]
  command = "npm run build"
  publish = "dist"

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200

```

---

### File 7: `nginx.conf`
*Path: `nginx.conf` | Size: 701 bytes | Source File*

```text
server {
    listen 80;
    server_name localhost;

    root /usr/share/nginx/html;
    index index.html index.htm;

    # Gzip Compression
    gzip on;
    gzip_vary on;
    gzip_proxied any;
    gzip_comp_level 6;
    gzip_types text/plain text/css text/xml application/json application/javascript application/rss+xml application/atom+xml image/svg+xml;

    location / {
        try_files $uri $uri/ /index.html;
    }

    # Cache static assets
    location ~* \.(js|css|png|jpg|jpeg|gif|ico|svg)$ {
        expires 1y;
        add_header Cache-Control "public, no-transform";
    }

    error_page 500 502 503 504 /50x.html;
    location = /50x.html {
        root /usr/share/nginx/html;
    }
}

```

---

### File 8: `package.json`
*Path: `package.json` | Size: 733 bytes | Project Dependencies & Scripts*

```json
{
  "name": "your-ircr",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "tsc -b && vite build",
    "lint": "oxlint",
    "preview": "vite preview"
  },
  "dependencies": {
    "@google/genai": "^2.31.0",
    "docx": "^9.14.0",
    "file-saver": "^2.0.5",
    "jspdf": "^4.2.1",
    "jspdf-autotable": "^5.0.9",
    "lucide-react": "^1.61.0",
    "react": "^19.3.1",
    "react-dom": "^19.3.1"
  },
  "devDependencies": {
    "@types/file-saver": "^2.0.7",
    "@types/node": "^24.19.2",
    "@types/react": "^19.3.0",
    "@types/react-dom": "^19.3.0",
    "@vitejs/plugin-react": "^6.1.2",
    "oxlint": "^1.88.0",
    "typescript": "~6.0.3",
    "vite": "^8.3.4"
  }
}

```

---

### File 9: `public/favicon.svg`
*Path: `public/favicon.svg` | Size: 9522 bytes | Source File*

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="48" height="46" fill="none" viewBox="0 0 48 46"><path fill="#863bff" d="M25.946 44.938c-.664.845-2.021.375-2.021-.698V33.937a2.26 2.26 0 0 0-2.262-2.262H10.287c-.92 0-1.456-1.04-.92-1.788l7.48-10.471c1.07-1.497 0-3.578-1.842-3.578H1.237c-.92 0-1.456-1.04-.92-1.788L10.013.474c.214-.297.556-.474.92-.474h28.894c.92 0 1.456 1.04.92 1.788l-7.48 10.471c-1.07 1.498 0 3.579 1.842 3.579h11.377c.943 0 1.473 1.088.89 1.83L25.947 44.94z" style="fill:#863bff;fill:color(display-p3 .5252 .23 1);fill-opacity:1"/><mask id="a" width="48" height="46" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path fill="#000" d="M25.842 44.938c-.664.844-2.021.375-2.021-.698V33.937a2.26 2.26 0 0 0-2.262-2.262H10.183c-.92 0-1.456-1.04-.92-1.788l7.48-10.471c1.07-1.498 0-3.579-1.842-3.579H1.133c-.92 0-1.456-1.04-.92-1.787L9.91.473c.214-.297.556-.474.92-.474h28.894c.92 0 1.456 1.04.92 1.788l-7.48 10.471c-1.07 1.498 0 3.578 1.842 3.578h11.377c.943 0 1.473 1.088.89 1.832L25.843 44.94z" style="fill:#000;fill-opacity:1"/></mask><g mask="url(#a)"><g filter="url(#b)"><ellipse cx="5.508" cy="14.704" fill="#ede6ff" rx="5.508" ry="14.704" style="fill:#ede6ff;fill:color(display-p3 .9275 .9033 1);fill-opacity:1" transform="matrix(.00324 1 1 -.00324 -4.47 31.516)"/></g><g filter="url(#c)"><ellipse cx="10.399" cy="29.851" fill="#ede6ff" rx="10.399" ry="29.851" style="fill:#ede6ff;fill:color(display-p3 .9275 .9033 1);fill-opacity:1" transform="matrix(.00324 1 1 -.00324 -39.328 7.883)"/></g><g filter="url(#d)"><ellipse cx="5.508" cy="30.487" fill="#7e14ff" rx="5.508" ry="30.487" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(89.814 -25.913 -14.639)scale(1 -1)"/></g><g filter="url(#e)"><ellipse cx="5.508" cy="30.599" fill="#7e14ff" rx="5.508" ry="30.599" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(89.814 -32.644 -3.334)scale(1 -1)"/></g><g filter="url(#f)"><ellipse cx="5.508" cy="30.599" fill="#7e14ff" rx="5.508" ry="30.599" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="matrix(.00324 1 1 -.00324 -34.34 30.47)"/></g><g filter="url(#g)"><ellipse cx="14.072" cy="22.078" fill="#ede6ff" rx="14.072" ry="22.078" style="fill:#ede6ff;fill:color(display-p3 .9275 .9033 1);fill-opacity:1" transform="rotate(93.35 24.506 48.493)scale(-1 1)"/></g><g filter="url(#h)"><ellipse cx="3.47" cy="21.501" fill="#7e14ff" rx="3.47" ry="21.501" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(89.009 28.708 47.59)scale(-1 1)"/></g><g filter="url(#i)"><ellipse cx="3.47" cy="21.501" fill="#7e14ff" rx="3.47" ry="21.501" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(89.009 28.708 47.59)scale(-1 1)"/></g><g filter="url(#j)"><ellipse cx=".387" cy="8.972" fill="#7e14ff" rx="4.407" ry="29.108" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(39.51 .387 8.972)"/></g><g filter="url(#k)"><ellipse cx="47.523" cy="-6.092" fill="#7e14ff" rx="4.407" ry="29.108" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(37.892 47.523 -6.092)"/></g><g filter="url(#l)"><ellipse cx="41.412" cy="6.333" fill="#47bfff" rx="5.971" ry="9.665" style="fill:#47bfff;fill:color(display-p3 .2799 .748 1);fill-opacity:1" transform="rotate(37.892 41.412 6.333)"/></g><g filter="url(#m)"><ellipse cx="-1.879" cy="38.332" fill="#7e14ff" rx="4.407" ry="29.108" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(37.892 -1.88 38.332)"/></g><g filter="url(#n)"><ellipse cx="-1.879" cy="38.332" fill="#7e14ff" rx="4.407" ry="29.108" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(37.892 -1.88 38.332)"/></g><g filter="url(#o)"><ellipse cx="35.651" cy="29.907" fill="#7e14ff" rx="4.407" ry="29.108" style="fill:#7e14ff;fill:color(display-p3 .4922 .0767 1);fill-opacity:1" transform="rotate(37.892 35.651 29.907)"/></g><g filter="url(#p)"><ellipse cx="38.418" cy="32.4" fill="#47bfff" rx="5.971" ry="15.297" style="fill:#47bfff;fill:color(display-p3 .2799 .748 1);fill-opacity:1" transform="rotate(37.892 38.418 32.4)"/></g></g><defs><filter id="b" width="60.045" height="41.654" x="-19.77" y="16.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="7.659"/></filter><filter id="c" width="90.34" height="51.437" x="-54.613" y="-7.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="7.659"/></filter><filter id="d" width="79.355" height="29.4" x="-49.64" y="2.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="e" width="79.579" height="29.4" x="-45.045" y="20.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="f" width="79.579" height="29.4" x="-43.513" y="21.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="g" width="74.749" height="58.852" x="15.756" y="-17.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="7.659"/></filter><filter id="h" width="61.377" height="25.362" x="23.548" y="2.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="i" width="61.377" height="25.362" x="23.548" y="2.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="j" width="56.045" height="63.649" x="-27.636" y="-22.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="k" width="54.814" height="64.646" x="20.116" y="-38.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="l" width="33.541" height="35.313" x="24.641" y="-11.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="m" width="54.814" height="64.646" x="-29.286" y="6.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="n" width="54.814" height="64.646" x="-29.286" y="6.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="o" width="54.814" height="64.646" x="8.244" y="-2.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter><filter id="p" width="39.409" height="43.623" x="18.713" y="10.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17158" stdDeviation="4.596"/></filter></defs></svg>
```

---

### File 10: `public/icons.svg`
*Path: `public/icons.svg` | Size: 5031 bytes | Source File*

```xml
<svg xmlns="http://www.w3.org/2000/svg">
  <symbol id="bluesky-icon" viewBox="0 0 16 17">
    <g clip-path="url(#bluesky-clip)"><path fill="#08060d" d="M7.75 7.735c-.693-1.348-2.58-3.86-4.334-5.097-1.68-1.187-2.32-.981-2.74-.79C.188 2.065.1 2.812.1 3.251s.241 3.602.398 4.13c.52 1.744 2.367 2.333 4.07 2.145-2.495.37-4.71 1.278-1.805 4.512 3.196 3.309 4.38-.71 4.987-2.746.608 2.036 1.307 5.91 4.93 2.746 2.72-2.746.747-4.143-1.747-4.512 1.702.189 3.55-.4 4.07-2.145.156-.528.397-3.691.397-4.13s-.088-1.186-.575-1.406c-.42-.19-1.06-.395-2.741.79-1.755 1.24-3.64 3.752-4.334 5.099"/></g>
    <defs><clipPath id="bluesky-clip"><path fill="#fff" d="M.1.85h15.3v15.3H.1z"/></clipPath></defs>
  </symbol>
  <symbol id="discord-icon" viewBox="0 0 20 19">
    <path fill="#08060d" d="M16.224 3.768a14.5 14.5 0 0 0-3.67-1.153c-.158.286-.343.67-.47.976a13.5 13.5 0 0 0-4.067 0c-.128-.306-.317-.69-.476-.976A14.4 14.4 0 0 0 3.868 3.77C1.546 7.28.916 10.703 1.231 14.077a14.7 14.7 0 0 0 4.5 2.306q.545-.748.965-1.587a9.5 9.5 0 0 1-1.518-.74q.191-.14.372-.293c2.927 1.369 6.107 1.369 8.999 0q.183.152.372.294-.723.437-1.52.74.418.838.963 1.588a14.6 14.6 0 0 0 4.504-2.308c.37-3.911-.63-7.302-2.644-10.309m-9.13 8.234c-.878 0-1.599-.82-1.599-1.82 0-.998.705-1.82 1.6-1.82.894 0 1.614.82 1.599 1.82.001 1-.705 1.82-1.6 1.82m5.91 0c-.878 0-1.599-.82-1.599-1.82 0-.998.705-1.82 1.6-1.82.893 0 1.614.82 1.599 1.82 0 1-.706 1.82-1.6 1.82"/>
  </symbol>
  <symbol id="documentation-icon" viewBox="0 0 21 20">
    <path fill="none" stroke="#aa3bff" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.35" d="m15.5 13.333 1.533 1.322c.645.555.967.833.967 1.178s-.322.623-.967 1.179L15.5 18.333m-3.333-5-1.534 1.322c-.644.555-.966.833-.966 1.178s.322.623.966 1.179l1.534 1.321"/>
    <path fill="none" stroke="#aa3bff" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.35" d="M17.167 10.836v-4.32c0-1.41 0-2.117-.224-2.68-.359-.906-1.118-1.621-2.08-1.96-.599-.21-1.349-.21-2.848-.21-2.623 0-3.935 0-4.983.369-1.684.591-3.013 1.842-3.641 3.428C3 6.449 3 7.684 3 10.154v2.122c0 2.558 0 3.838.706 4.726q.306.383.713.671c.76.536 1.79.64 3.581.66"/>
    <path fill="none" stroke="#aa3bff" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.35" d="M3 10a2.78 2.78 0 0 1 2.778-2.778c.555 0 1.209.097 1.748-.047.48-.129.854-.503.982-.982.145-.54.048-1.194.048-1.749a2.78 2.78 0 0 1 2.777-2.777"/>
  </symbol>
  <symbol id="github-icon" viewBox="0 0 19 19">
    <path fill="#08060d" fill-rule="evenodd" d="M9.356 1.85C5.05 1.85 1.57 5.356 1.57 9.694a7.84 7.84 0 0 0 5.324 7.44c.387.079.528-.168.528-.376 0-.182-.013-.805-.013-1.454-2.165.467-2.616-.935-2.616-.935-.349-.91-.864-1.143-.864-1.143-.71-.48.051-.48.051-.48.787.051 1.2.805 1.2.805.695 1.194 1.817.857 2.268.649.064-.507.27-.857.49-1.052-1.728-.182-3.545-.857-3.545-3.87 0-.857.31-1.558.8-2.104-.078-.195-.349-1 .077-2.078 0 0 .657-.208 2.14.805a7.5 7.5 0 0 1 1.946-.26c.657 0 1.328.092 1.946.26 1.483-1.013 2.14-.805 2.14-.805.426 1.078.155 1.883.078 2.078.502.546.799 1.247.799 2.104 0 3.013-1.818 3.675-3.558 3.87.284.247.528.714.528 1.454 0 1.052-.012 1.896-.012 2.156 0 .208.142.455.528.377a7.84 7.84 0 0 0 5.324-7.441c.013-4.338-3.48-7.844-7.773-7.844" clip-rule="evenodd"/>
  </symbol>
  <symbol id="social-icon" viewBox="0 0 20 20">
    <path fill="none" stroke="#aa3bff" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.35" d="M12.5 6.667a4.167 4.167 0 1 0-8.334 0 4.167 4.167 0 0 0 8.334 0"/>
    <path fill="none" stroke="#aa3bff" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.35" d="M2.5 16.667a5.833 5.833 0 0 1 8.75-5.053m3.837.474.513 1.035c.07.144.257.282.414.309l.93.155c.596.1.736.536.307.965l-.723.73a.64.64 0 0 0-.152.531l.207.903c.164.715-.213.991-.84.618l-.872-.52a.63.63 0 0 0-.577 0l-.872.52c-.624.373-1.003.094-.84-.618l.207-.903a.64.64 0 0 0-.152-.532l-.723-.729c-.426-.43-.289-.864.306-.964l.93-.156a.64.64 0 0 0 .412-.31l.513-1.034c.28-.562.735-.562 1.012 0"/>
  </symbol>
  <symbol id="x-icon" viewBox="0 0 19 19">
    <path fill="#08060d" fill-rule="evenodd" d="M1.893 1.98c.052.072 1.245 1.769 2.653 3.77l2.892 4.114c.183.261.333.48.333.486s-.068.089-.152.183l-.522.593-.765.867-3.597 4.087c-.375.426-.734.834-.798.905a1 1 0 0 0-.118.148c0 .01.236.017.664.017h.663l.729-.83c.4-.457.796-.906.879-.999a692 692 0 0 0 1.794-2.038c.034-.037.301-.34.594-.675l.551-.624.345-.392a7 7 0 0 1 .34-.374c.006 0 .93 1.306 2.052 2.903l2.084 2.965.045.063h2.275c1.87 0 2.273-.003 2.266-.021-.008-.02-1.098-1.572-3.894-5.547-2.013-2.862-2.28-3.246-2.273-3.266.008-.019.282-.332 2.085-2.38l2-2.274 1.567-1.782c.022-.028-.016-.03-.65-.03h-.674l-.3.342a871 871 0 0 1-1.782 2.025c-.067.075-.405.458-.75.852a100 100 0 0 1-.803.91c-.148.172-.299.344-.99 1.127-.304.343-.32.358-.345.327-.015-.019-.904-1.282-1.976-2.808L6.365 1.85H1.8zm1.782.91 8.078 11.294c.772 1.08 1.413 1.973 1.425 1.984.016.017.241.02 1.05.017l1.03-.004-2.694-3.766L7.796 5.75 5.722 2.852l-1.039-.004-1.039-.004z" clip-rule="evenodd"/>
  </symbol>
</svg>

```

---

### File 11: `README.md`
*Path: `README.md` | Size: 1278 bytes | Project Documentation & Architecture Guide*

```markdown
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend enabling type-aware lint rules by installing `oxlint-tsgolint` and editing `.oxlintrc.json`:

```json
{
  "$schema": "./node_modules/oxlint/configuration_schema.json",
  "plugins": ["react", "typescript", "oxc"],
  "options": {
    "typeAware": true
  },
  "rules": {
    "react/rules-of-hooks": "error",
    "react/only-export-components": ["warn", { "allowConstantExport": true }]
  }
}
```

See the [Oxlint rules documentation](https://oxc.rs/docs/guide/usage/linter/rules) for the full list of rules and categories.

```

---

### File 12: `src/App.css`
*Path: `src/App.css` | Size: 40460 bytes | Complete CSS Design Tokens & Print Stylesheet*

```css
/* =========================================================================
   OIML R 76 NAWI TEST REPORT GENERATOR - MASTER STYLESHEET
   Legal Metrology Division | Ministry of Consumer Affairs, GoI
   ========================================================================= */

.app-root {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  background-color: var(--bg-canvas);
}

/* ================= TRICOLOR INDIA STRIP ================= */
.tricolor-strip {
  display: flex;
  height: 4px;
  width: 100%;
}

.strip-saffron {
  flex: 1;
  background-color: #ff9933;
}

.strip-white {
  flex: 1;
  background-color: #ffffff;
}

.strip-green {
  flex: 1;
  background-color: #138808;
}

/* ================= NAVBAR ================= */
.navbar-wrapper {
  background: var(--surface-card);
  border-bottom: 1px solid var(--border-subtle);
  position: sticky;
  top: 0;
  z-index: 50;
  box-shadow: var(--shadow-sm);
}

.navbar-container {
  max-width: 1600px;
  margin: 0 auto;
  padding: 0.65rem 1.5rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.5rem;
}

.navbar-brand-section {
  display: flex;
  align-items: center;
  gap: 0.85rem;
}

.brand-logo-box {
  width: 44px;
  height: 44px;
  border-radius: var(--radius-md);
  background: linear-gradient(135deg, var(--brand-navy) 0%, #1e3a8a 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  box-shadow: 0 4px 10px rgba(15, 43, 72, 0.25);
  flex-shrink: 0;
}

.brand-text-box {
  display: flex;
  flex-direction: column;
}

.brand-title-row {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.brand-ministry {
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--brand-navy);
}

.brand-badge-oiml {
  font-size: 0.65rem;
  font-weight: 800;
  padding: 0.1rem 0.4rem;
  border-radius: var(--radius-sm);
  background: var(--brand-teal);
  color: #ffffff;
  letter-spacing: 0.03em;
}

.brand-app-name {
  font-family: var(--font-heading);
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--text-primary);
  line-height: 1.25;
}

.brand-sub {
  font-size: 0.73rem;
  color: var(--text-muted);
}

.navbar-actions-section {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.nav-action-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0.48rem 0.85rem;
  border-radius: var(--radius-sm);
  font-size: 0.84rem;
  font-weight: 600;
  color: var(--text-secondary);
  background: transparent;
  border: 1px solid transparent;
  transition: all var(--transition-fast);
}

.nav-action-btn:hover {
  background: var(--surface-subtle);
  color: var(--text-primary);
}

.nav-action-btn.active {
  background: #f1f5f9;
  color: var(--brand-navy);
  border-color: var(--border-medium);
}

.btn-new-report {
  background: var(--brand-navy);
  color: #ffffff !important;
  border-color: var(--brand-navy);
}

.btn-new-report:hover {
  background: var(--brand-navy-hover);
}

.btn-ghost {
  border-color: var(--border-subtle);
}

.btn-ghost:hover {
  border-color: var(--border-medium);
}

.file-upload-label {
  cursor: pointer;
}

/* User Role Badge in Navbar */
.navbar-user-section {
  display: flex;
  align-items: center;
}

.user-profile-badge {
  position: relative;
  display: flex;
  align-items: center;
  gap: 0.65rem;
  padding: 0.4rem 0.75rem;
  background: var(--surface-subtle);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-md);
  transition: all var(--transition-fast);
}

.user-profile-badge:hover {
  border-color: var(--border-medium);
}

.user-avatar {
  width: 32px;
  height: 32px;
  border-radius: var(--radius-full);
  background: #e2e8f0;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--brand-navy);
}

.user-info-text {
  display: flex;
  flex-direction: column;
}

.user-name-role {
  display: flex;
  align-items: center;
  gap: 0.4rem;
}

.user-name {
  font-size: 0.82rem;
  font-weight: 700;
  color: var(--text-primary);
}

.role-pill {
  font-size: 0.62rem;
  font-weight: 700;
  padding: 0.1rem 0.35rem;
  border-radius: var(--radius-sm);
  text-transform: uppercase;
}

.role-senior_metrologist {
  background: #e0f2fe;
  color: #0369a1;
}

.role-testing_officer {
  background: #fef3c7;
  color: #b45309;
}

.role-director {
  background: #dcfce7;
  color: #15803d;
}

.role-auditor {
  background: #f3e8ff;
  color: #7e22ce;
}

.user-designation {
  font-size: 0.68rem;
  color: var(--text-muted);
  max-width: 220px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.user-select-hidden {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  cursor: pointer;
}

/* ================= MAIN CONTENT ================= */
.main-content-area {
  flex: 1;
  max-width: 1600px;
  width: 100%;
  margin: 0 auto;
  padding: 1.5rem;
}

/* ================= BUTTONS & COMMON ================= */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  padding: 0.55rem 1rem;
  border-radius: var(--radius-sm);
  font-size: 0.86rem;
  font-weight: 600;
  transition: all var(--transition-fast);
}

.btn-primary {
  background: var(--brand-navy);
  color: #ffffff;
  box-shadow: 0 2px 4px rgba(15, 43, 72, 0.15);
}

.btn-primary:hover {
  background: var(--brand-navy-hover);
}

.btn-secondary {
  background: var(--surface-card);
  color: var(--text-primary);
  border: 1px solid var(--border-medium);
}

.btn-secondary:hover {
  background: var(--surface-subtle);
  border-color: var(--border-strong);
}

.btn-icon-text {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
}

/* Semantic Badges (Icons + Text + High Contrast) */
.badge {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  font-size: 0.72rem;
  font-weight: 700;
  padding: 0.2rem 0.55rem;
  border-radius: var(--radius-sm);
  letter-spacing: 0.02em;
}

.badge-pass {
  background: var(--color-pass-bg);
  color: var(--color-pass-text);
  border: 1px solid var(--color-pass-border);
}

.badge-fail {
  background: var(--color-fail-bg);
  color: var(--color-fail-text);
  border: 1px solid var(--color-fail-border);
}

.badge-warning {
  background: var(--color-warning-bg);
  color: var(--color-warning-text);
  border: 1px solid var(--color-warning-border);
}

.status-pill {
  font-size: 0.7rem;
  font-weight: 700;
  padding: 0.18rem 0.5rem;
  border-radius: var(--radius-sm);
  text-transform: uppercase;
}

.status-approved {
  background: #dcfce7;
  color: #15803d;
  border: 1px solid #bbf7d0;
}

.status-pending_approval {
  background: #fef3c7;
  color: #b45309;
  border: 1px solid #fde68a;
}

.status-under_evaluation {
  background: #e0f2fe;
  color: #0369a1;
  border: 1px solid #bae6fd;
}

.status-rejected {
  background: #fee2e2;
  color: #b91c1c;
  border: 1px solid #fecaca;
}

.status-draft {
  background: #f1f5f9;
  color: #475569;
  border: 1px solid #cbd5e1;
}

.class-badge {
  font-size: 0.72rem;
  font-weight: 800;
  padding: 0.2rem 0.55rem;
  border-radius: var(--radius-sm);
}

.class-I {
  background: #fdf4ff;
  color: #86198f;
  border: 1px solid #f0abfc;
}

.class-II {
  background: #eff6ff;
  color: #1d4ed8;
  border: 1px solid #bfdbfe;
}

.class-III {
  background: #ecfdf5;
  color: #047857;
  border: 1px solid #a7f3d0;
}

.class-IIII {
  background: #fffbeb;
  color: #b45309;
  border: 1px solid #fde68a;
}

.text-success {
  color: var(--color-pass);
}

.text-danger {
  color: var(--color-fail);
}

/* ================= DASHBOARD ================= */
.dashboard-wrapper {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.kpi-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.25rem;
}

.kpi-card {
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  padding: 1.25rem;
  display: flex;
  align-items: center;
  gap: 1.15rem;
  box-shadow: var(--shadow-sm);
  transition: transform var(--transition-fast), box-shadow var(--transition-fast);
}

.kpi-card:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

.kpi-icon-wrapper {
  width: 52px;
  height: 52px;
  border-radius: var(--radius-md);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.kpi-primary {
  background: #e0f2fe;
  color: #0369a1;
}

.kpi-success {
  background: #dcfce7;
  color: #15803d;
}

.kpi-warning {
  background: #fef3c7;
  color: #b45309;
}

.kpi-danger {
  background: #fee2e2;
  color: #b91c1c;
}

.kpi-content {
  display: flex;
  flex-direction: column;
}

.kpi-label {
  font-size: 0.8rem;
  font-weight: 600;
  color: var(--text-secondary);
}

.kpi-value {
  font-family: var(--font-heading);
  font-size: 1.85rem;
  font-weight: 700;
  color: var(--text-primary);
  line-height: 1.15;
  margin: 0.15rem 0;
}

.kpi-sub {
  font-size: 0.74rem;
  color: var(--text-muted);
}

/* Class Breakdown Bar */
.class-breakdown-bar {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding: 0.75rem 1.25rem;
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-md);
  box-shadow: var(--shadow-sm);
}

.class-bar-title {
  font-size: 0.84rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.class-pill-group {
  display: flex;
  gap: 0.6rem;
  flex-wrap: wrap;
}

.class-filter-pill {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0.35rem 0.75rem;
  border-radius: var(--radius-full);
  font-size: 0.78rem;
  font-weight: 600;
  background: var(--surface-subtle);
  border: 1px solid var(--border-subtle);
  color: var(--text-secondary);
  transition: all var(--transition-fast);
}

.class-filter-pill:hover, .class-filter-pill.active {
  background: var(--brand-navy);
  color: #ffffff;
  border-color: var(--brand-navy);
}

.class-filter-pill .pill-count {
  background: rgba(255, 255, 255, 0.25);
  padding: 0.05rem 0.35rem;
  border-radius: var(--radius-full);
  font-size: 0.7rem;
}

.class-filter-pill:not(.active) .pill-count {
  background: #cbd5e1;
  color: var(--text-primary);
}

/* Search and Filter Panel */
.search-filter-panel {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
}

.search-input-box {
  position: relative;
  flex: 1;
  min-width: 320px;
}

.search-icon {
  position: absolute;
  left: 0.85rem;
  top: 50%;
  transform: translateY(-50%);
  color: var(--text-muted);
}

.search-input {
  width: 100%;
  padding: 0.6rem 2.2rem 0.6rem 2.5rem;
  border-radius: var(--radius-md);
  border: 1px solid var(--border-medium);
  background: var(--surface-card);
  color: var(--text-primary);
  font-size: 0.88rem;
  transition: border-color var(--transition-fast), box-shadow var(--transition-fast);
}

.search-input:focus {
  outline: none;
  border-color: var(--brand-navy);
  box-shadow: 0 0 0 3px rgba(15, 43, 72, 0.1);
}

.search-clear {
  position: absolute;
  right: 0.75rem;
  top: 50%;
  transform: translateY(-50%);
  color: var(--text-muted);
  font-size: 0.85rem;
}

.filter-dropdowns {
  display: flex;
  align-items: center;
  gap: 0.85rem;
  flex-wrap: wrap;
}

.filter-group {
  display: flex;
  align-items: center;
  gap: 0.4rem;
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--text-secondary);
}

.filter-select {
  padding: 0.55rem 0.85rem;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-medium);
  background: var(--surface-card);
  color: var(--text-primary);
  font-size: 0.82rem;
  font-weight: 500;
  outline: none;
}

.filter-select:focus {
  border-color: var(--brand-navy);
}

/* Reports Table Card */
.reports-table-card {
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  box-shadow: var(--shadow-sm);
  overflow: hidden;
}

.table-header-info {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.15rem 1.5rem;
  border-bottom: 1px solid var(--border-subtle);
}

.table-header-info h4 {
  font-family: var(--font-heading);
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--text-primary);
}

.results-count {
  font-size: 0.78rem;
  color: var(--text-muted);
  font-weight: 600;
}

.table-responsive {
  width: 100%;
  overflow-x: auto;
}

.data-table {
  width: 100%;
  border-collapse: collapse;
  text-align: left;
  font-size: 0.82rem;
}

.data-table th {
  background: #f8fafc;
  color: var(--text-secondary);
  font-weight: 700;
  padding: 0.75rem 1rem;
  border-bottom: 1px solid var(--border-medium);
  white-space: nowrap;
}

.data-table td {
  padding: 0.85rem 1rem;
  border-bottom: 1px solid var(--border-subtle);
  vertical-align: middle;
}

.report-row:hover {
  background: #f8fafc;
}

.report-id-cell {
  display: flex;
  flex-direction: column;
}

.report-number-text {
  font-family: var(--font-mono);
  font-size: 0.84rem;
  color: var(--brand-navy);
  font-weight: 700;
}

.report-date-text {
  font-size: 0.72rem;
  color: var(--text-muted);
}

.inst-meta-cell {
  display: flex;
  flex-direction: column;
}

.inst-model {
  font-weight: 700;
  color: var(--text-primary);
}

.inst-mfg {
  font-size: 0.75rem;
  color: var(--text-secondary);
}

.inst-sn {
  font-family: var(--font-mono);
  font-size: 0.7rem;
  color: var(--text-muted);
}

.class-cap-cell {
  display: flex;
  flex-direction: column;
  gap: 0.2rem;
}

.cap-text {
  font-size: 0.75rem;
  font-weight: 600;
  color: var(--text-secondary);
}

.interval-cell {
  display: flex;
  flex-direction: column;
  font-family: var(--font-mono);
  font-size: 0.78rem;
}

.n-count {
  font-size: 0.72rem;
  color: var(--text-muted);
}

.lab-cell {
  max-width: 200px;
  display: flex;
  flex-direction: column;
}

.lab-name {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  font-weight: 600;
  color: var(--text-primary);
}

.lab-nabl {
  font-size: 0.7rem;
  color: var(--text-muted);
}

.action-buttons-group {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.35rem;
}

.btn-action {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  padding: 0.35rem 0.6rem;
  border-radius: var(--radius-sm);
  font-size: 0.75rem;
  font-weight: 600;
  background: var(--surface-subtle);
  border: 1px solid var(--border-subtle);
  color: var(--text-secondary);
  transition: all var(--transition-fast);
}

.btn-action:hover {
  background: #e2e8f0;
  color: var(--text-primary);
}

.btn-edit {
  background: #e0f2fe;
  color: #0369a1;
  border-color: #bae6fd;
}

.btn-edit:hover {
  background: #bae6fd;
}

.btn-danger-action:hover {
  background: #fee2e2;
  color: #b91c1c;
  border-color: #fecaca;
}

/* Empty State */
.empty-state {
  text-align: center;
  padding: 3.5rem 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.85rem;
}

.empty-icon {
  color: var(--text-muted);
}

.empty-state h5 {
  font-size: 1.1rem;
  font-weight: 700;
}

.empty-state p {
  color: var(--text-muted);
  font-size: 0.88rem;
}

/* ================= REPORT WORKBENCH / EDITOR ================= */
.report-editor-wrapper {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
}

.editor-top-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  padding: 0.85rem 1.25rem;
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  box-shadow: var(--shadow-sm);
  flex-wrap: wrap;
}

.top-bar-left {
  display: flex;
  align-items: center;
  gap: 1.15rem;
}

.report-title-meta {
  display: flex;
  flex-direction: column;
}

.rep-number-badge {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.rep-num {
  font-family: var(--font-mono);
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.rep-desc {
  font-size: 0.78rem;
  color: var(--text-secondary);
}

.top-bar-right {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  flex-wrap: wrap;
}

.verdict-pill {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0.45rem 0.85rem;
  border-radius: var(--radius-sm);
  font-size: 0.82rem;
  font-weight: 800;
  letter-spacing: 0.03em;
}

.verdict-pass {
  background: var(--color-pass-bg);
  color: var(--color-pass-text);
  border: 1.5px solid var(--color-pass-border);
}

.verdict-fail {
  background: var(--color-fail-bg);
  color: var(--color-fail-text);
  border: 1.5px solid var(--color-fail-border);
}

.save-toast-banner {
  background: #ecfdf5;
  border: 1px solid #a7f3d0;
  color: #065f46;
  padding: 0.65rem 1rem;
  border-radius: var(--radius-md);
  font-size: 0.84rem;
  font-weight: 600;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  animation: fadeIn 200ms ease;
}

/* Master Tabs Navigation Bar */
.editor-tabs-bar {
  display: flex;
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-md);
  padding: 0.35rem;
  gap: 0.35rem;
  overflow-x: auto;
  box-shadow: var(--shadow-sm);
}

.tab-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.6rem 1rem;
  border-radius: var(--radius-sm);
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--text-secondary);
  background: transparent;
  white-space: nowrap;
  transition: all var(--transition-fast);
}

.tab-btn:hover {
  background: var(--surface-subtle);
  color: var(--text-primary);
}

.tab-btn.active {
  background: var(--brand-navy);
  color: #ffffff;
}

.tab-warn-icon {
  color: #f59e0b;
}

.tab-indicator {
  font-size: 0.65rem;
  font-weight: 700;
  padding: 0.1rem 0.35rem;
  border-radius: var(--radius-sm);
}

.tab-pass {
  background: rgba(16, 185, 129, 0.2);
  color: #10b981;
}

.tab-btn.active .tab-pass {
  background: #10b981;
  color: #ffffff;
}

.tab-fail {
  background: rgba(239, 68, 68, 0.2);
  color: #ef4444;
}

.tab-btn.active .tab-fail {
  background: #ef4444;
  color: #ffffff;
}

/* Pane Body */
.editor-pane-body {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
}

.tab-pane-content {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  animation: fadeIn 200ms ease;
}

.pane-section-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
}

.pane-section-header h3 {
  font-family: var(--font-heading);
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--text-primary);
}

.pane-section-header p {
  font-size: 0.82rem;
  color: var(--text-muted);
}

.pane-actions-group {
  display: flex;
  align-items: center;
  gap: 0.65rem;
}

/* Form Cards */
.form-card {
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  padding: 1.35rem;
  box-shadow: var(--shadow-sm);
}

.form-section-title {
  font-family: var(--font-heading);
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--brand-navy);
  margin-bottom: 1.15rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--border-subtle);
}

.form-grid-3 {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.15rem;
}

.form-grid-2 {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 1.15rem;
}

.form-grid-1 {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.form-field {
  display: flex;
  flex-direction: column;
  gap: 0.35rem;
}

.form-field label {
  font-size: 0.78rem;
  font-weight: 600;
  color: var(--text-secondary);
}

.form-field input, .form-field select, .form-field textarea {
  padding: 0.55rem 0.75rem;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-medium);
  background: var(--surface-card);
  color: var(--text-primary);
  font-size: 0.84rem;
  transition: all var(--transition-fast);
}

.form-field input:focus, .form-field select:focus, .form-field textarea:focus {
  outline: none;
  border-color: var(--brand-navy);
  box-shadow: 0 0 0 3px rgba(15, 43, 72, 0.1);
}

.field-hint {
  font-size: 0.7rem;
  color: var(--text-muted);
}

.n-display-box {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.5rem 0.75rem;
  background: var(--surface-subtle);
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-subtle);
}

.n-val {
  font-family: var(--font-mono);
  font-size: 1.05rem;
  color: var(--brand-navy);
}

.n-status {
  font-size: 0.74rem;
  font-weight: 700;
}

/* Alert Boxes */
.alert-box {
  padding: 0.85rem 1.15rem;
  border-radius: var(--radius-md);
  display: flex;
  align-items: center;
  gap: 0.85rem;
  font-size: 0.84rem;
}

.alert-danger {
  background: #fef2f2;
  border: 1px solid #fecaca;
  color: #991b1b;
}

/* ================= ZERO CARD & WEIGHING PERFORMANCE ================= */
.zero-settings-card {
  background: #f8fafc;
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-md);
  padding: 0.95rem 1.25rem;
  display: flex;
  flex-direction: column;
  gap: 0.65rem;
}

.zero-card-title {
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-size: 0.82rem;
  color: var(--brand-navy);
}

.zero-fields-row {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  flex-wrap: wrap;
}

.inline-field {
  flex-direction: row;
  align-items: center;
  gap: 0.5rem;
}

.inline-field input {
  width: 90px;
}

/* Weighing Table Inputs */
.table-input {
  width: 100%;
  padding: 0.35rem 0.5rem;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-medium);
  background: var(--surface-card);
  font-size: 0.8rem;
  font-family: var(--font-mono);
  text-align: right;
}

.table-input-select {
  padding: 0.35rem 0.45rem;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-medium);
  background: var(--surface-card);
  font-size: 0.78rem;
  font-weight: 600;
}

.mono-cell {
  font-family: var(--font-mono);
  font-size: 0.8rem;
}

.btn-trash-row {
  color: var(--text-muted);
  padding: 0.25rem;
  border-radius: var(--radius-sm);
}

.btn-trash-row:hover {
  color: var(--color-fail);
  background: #fee2e2;
}

.row-failed {
  background: #fff5f5 !important;
}

.weighing-summary-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.95rem 1.25rem;
  background: #f8fafc;
  border-top: 1px solid var(--border-medium);
  flex-wrap: wrap;
  gap: 1rem;
}

.footer-metric {
  display: flex;
  align-items: center;
  gap: 0.45rem;
  font-size: 0.82rem;
  color: var(--text-secondary);
}

.footer-metric strong {
  font-family: var(--font-mono);
  color: var(--brand-navy);
}

/* ================= INTERACTIVE ERROR CURVE COMPONENT ================= */
.error-curve-card {
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  padding: 1.25rem;
  box-shadow: var(--shadow-sm);
}

.error-curve-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 0.75rem;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.card-title {
  font-family: var(--font-heading);
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--text-primary);
}

.card-subtitle {
  font-size: 0.75rem;
  color: var(--text-muted);
}

.curve-legend {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.legend-item {
  display: flex;
  align-items: center;
  gap: 0.4rem;
  font-size: 0.76rem;
  font-weight: 600;
  color: var(--text-secondary);
}

.legend-swatch {
  width: 14px;
  height: 10px;
  border-radius: 2px;
}

.corridor-swatch {
  background: rgba(16, 185, 129, 0.4);
  border: 1px dashed #059669;
}

.inc-swatch {
  background: #0284c7;
}

.dec-swatch {
  background: #8b5cf6;
}

.svg-container {
  width: 100%;
  overflow-x: auto;
}

.error-curve-svg {
  width: 100%;
  height: auto;
  min-width: 600px;
}

.axis-tick-text {
  font-family: var(--font-mono);
  font-size: 9px;
  fill: #64748b;
}

.axis-title {
  font-size: 10px;
  font-weight: 700;
  fill: #334155;
  text-transform: uppercase;
  letter-spacing: 0.04em;
}

.curve-point {
  cursor: pointer;
  transition: r 150ms ease;
}

.curve-point:hover {
  r: 8;
}

.curve-tooltip-box {
  margin-top: 0.75rem;
  background: #f8fafc;
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-md);
  padding: 0.75rem 1rem;
  animation: fadeIn 150ms ease;
}

.tooltip-header {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  margin-bottom: 0.5rem;
}

.tooltip-step {
  font-size: 0.8rem;
  font-weight: 700;
  color: var(--text-primary);
}

.tooltip-metrics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 0.6rem;
  font-size: 0.78rem;
}

.t-label {
  color: var(--text-muted);
  margin-right: 0.35rem;
}

.t-val {
  font-family: var(--font-mono);
}

.curve-hint {
  margin-top: 0.5rem;
  font-size: 0.75rem;
  color: var(--text-muted);
  font-style: italic;
}

/* ================= ECCENTRICITY PLATFORM DIAGRAM ================= */
.eccentricity-card {
  background: var(--surface-card);
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-lg);
  padding: 1.25rem;
  box-shadow: var(--shadow-sm);
}

.ecc-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1.15rem;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.ecc-summary-badge {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.ecc-stat {
  font-size: 0.8rem;
  color: var(--text-secondary);
}

.ecc-body-grid {
  display: grid;
  grid-template-columns: 1fr 340px;
  gap: 1.5rem;
  align-items: center;
}

@media (max-width: 900px) {
  .ecc-body-grid {
    grid-template-columns: 1fr;
  }
}

.receptor-visual-wrapper {
  background: #f1f5f9;
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-md);
  padding: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 320px;
}

/* Rectangular Platform */
.rect-platform {
  width: 380px;
  height: 250px;
  background: #ffffff;
  border: 3px solid #94a3b8;
  border-radius: 8px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
  position: relative;
  padding: 10px;
}

.platform-border {
  width: 100%;
  height: 100%;
  border: 1px dashed #cbd5e1;
  position: relative;
}

.corner-node {
  position: absolute;
  padding: 0.35rem 0.65rem;
  border-radius: var(--radius-sm);
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 0.7rem;
  font-weight: 700;
  box-shadow: var(--shadow-md);
  transition: all var(--transition-fast);
  cursor: pointer;
  background: #ffffff;
  border: 2px solid var(--border-medium);
}

.corner-node:hover {
  transform: scale(1.08);
  z-index: 10;
}

.node-pass {
  border-color: #10b981;
  color: #065f46;
}

.node-fail {
  border-color: #ef4444;
  color: #991b1b;
  background: #fef2f2;
}

.node-selected {
  outline: 3px solid var(--brand-navy);
  transform: scale(1.08);
  z-index: 15;
}

.node-icon {
  font-size: 0.85rem;
}

.node-ec {
  font-family: var(--font-mono);
  font-size: 0.68rem;
}

.pos-center {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.pos-front-left {
  bottom: 12px;
  left: 12px;
}

.pos-back-left {
  top: 12px;
  left: 12px;
}

.pos-back-right {
  top: 12px;
  right: 12px;
}

.pos-front-right {
  bottom: 12px;
  right: 12px;
}

/* Circular Pan */
.round-pan {
  width: 260px;
  height: 260px;
  border-radius: var(--radius-full);
  background: #ffffff;
  border: 3px solid #94a3b8;
  position: relative;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
}

.pos-round-front {
  bottom: 15px;
  left: 50%;
  transform: translateX(-50%);
}

.pos-round-back {
  top: 15px;
  left: 50%;
  transform: translateX(-50%);
}

.pos-round-left {
  left: 15px;
  top: 50%;
  transform: translateY(-50%);
}

.pos-round-right {
  right: 15px;
  top: 50%;
  transform: translateY(-50%);
}

/* Weighbridge Deck */
.weighbridge-deck {
  width: 100%;
  max-width: 500px;
  display: flex;
  gap: 0.75rem;
}

.weighbridge-section-node {
  flex: 1;
  background: #ffffff;
  border: 2px solid #94a3b8;
  border-radius: var(--radius-sm);
  padding: 1.25rem 0.75rem;
  display: flex;
  flex-direction: column;
  gap: 0.35rem;
  text-align: left;
  transition: all var(--transition-fast);
}

.weighbridge-section-node:hover {
  transform: translateY(-3px);
}

.sec-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.sec-title {
  font-weight: 700;
  font-size: 0.76rem;
}

.sec-val {
  font-family: var(--font-mono);
  font-size: 0.85rem;
  font-weight: 700;
}

.sec-sub {
  font-size: 0.7rem;
  color: var(--text-muted);
}

.ecc-detail-card {
  background: var(--surface-card);
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-md);
  padding: 1.15rem;
  box-shadow: var(--shadow-sm);
}

.detail-card-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 0.85rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--border-subtle);
}

.detail-card-head h5 {
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.detail-grid {
  display: flex;
  flex-direction: column;
  gap: 0.45rem;
}

.detail-row {
  display: flex;
  justify-content: space-between;
  font-size: 0.8rem;
}

.detail-row span {
  color: var(--text-secondary);
}

.detail-row strong {
  font-family: var(--font-mono);
}

.highlight-row {
  padding: 0.35rem 0.5rem;
  background: #f8fafc;
  border-radius: var(--radius-sm);
  font-size: 0.85rem;
}

.detail-clause-note {
  margin-top: 0.85rem;
  padding-top: 0.5rem;
  border-top: 1px dashed var(--border-subtle);
  color: var(--text-muted);
}

/* ================= REPEATABILITY GRID ================= */
.rep-grid-two {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 1.25rem;
}

.rep-series-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1rem;
}

.rep-series-header h5 {
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.rep-series-header p {
  font-size: 0.76rem;
  color: var(--text-muted);
}

.rep-result-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.65rem 0.85rem;
  background: var(--surface-subtle);
  border-radius: var(--radius-sm);
  margin-top: 0.85rem;
  font-size: 0.82rem;
}

/* ================= CERTIFICATE PREVIEW & SIGNOFF ================= */
.certificate-preview-card {
  background: var(--surface-card);
  border: 2px solid var(--brand-navy);
  border-radius: var(--radius-lg);
  padding: 1.75rem;
  box-shadow: var(--shadow-md);
}

.cert-header {
  text-align: center;
  padding-bottom: 1rem;
  border-bottom: 2px solid var(--border-subtle);
  margin-bottom: 1.25rem;
}

.cert-emblem-text h5 {
  font-size: 1.15rem;
  font-weight: 800;
  letter-spacing: 0.08em;
  color: var(--brand-navy);
}

.cert-emblem-text h6 {
  font-size: 0.92rem;
  font-weight: 700;
  color: var(--text-secondary);
}

.cert-emblem-text p {
  font-size: 0.75rem;
  font-weight: 600;
  color: var(--text-muted);
  letter-spacing: 0.05em;
  margin-top: 0.2rem;
}

.cert-type-text {
  display: inline-block;
  margin-top: 0.4rem;
  padding: 0.2rem 0.75rem;
  background: var(--brand-navy);
  color: #ffffff;
  font-size: 0.74rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  border-radius: var(--radius-sm);
}

.cert-meta-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 0.85rem;
  padding: 0.85rem 1rem;
  background: #f8fafc;
  border-radius: var(--radius-md);
  margin-bottom: 1.25rem;
}

.cert-meta-grid div {
  display: flex;
  flex-direction: column;
}

.cert-meta-grid span {
  font-size: 0.72rem;
  color: var(--text-muted);
  text-transform: uppercase;
  font-weight: 600;
}

.cert-meta-grid strong {
  font-size: 0.86rem;
  color: var(--brand-navy);
}

.cert-verdict-banner {
  display: flex;
  align-items: center;
  gap: 1.15rem;
  padding: 1rem 1.25rem;
  border-radius: var(--radius-md);
  margin-bottom: 1rem;
}

.cert-pass {
  background: #ecfdf5;
  border: 1.5px solid #a7f3d0;
  color: #065f46;
}

.cert-fail {
  background: #fef2f2;
  border: 1.5px solid #fecaca;
  color: #991b1b;
}

.cert-verdict-banner h4 {
  font-size: 1.05rem;
  font-weight: 800;
  letter-spacing: 0.02em;
}

.cert-verdict-banner p {
  font-size: 0.8rem;
  margin-top: 0.15rem;
}

.workflow-action-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  padding: 1rem 0;
  border-top: 1px solid var(--border-subtle);
  border-bottom: 1px solid var(--border-subtle);
  margin-top: 1.25rem;
  flex-wrap: wrap;
}

.status-selector-group {
  display: flex;
  align-items: center;
  gap: 0.65rem;
}

.status-selector-group label {
  font-size: 0.85rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.status-dropdown {
  padding: 0.55rem 0.85rem;
  border-radius: var(--radius-sm);
  border: 1.5px solid var(--brand-navy);
  background: var(--surface-card);
  font-weight: 700;
  font-size: 0.85rem;
  color: var(--brand-navy);
}

.export-buttons-group {
  display: flex;
  align-items: center;
  gap: 0.65rem;
}

.verification-hash-footer {
  margin-top: 1rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.74rem;
  color: var(--text-muted);
  flex-wrap: wrap;
}

.hash-code {
  background: #f1f5f9;
  padding: 0.2rem 0.5rem;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border-subtle);
  font-size: 0.72rem;
  color: var(--brand-navy);
  font-weight: 700;
}

/* Audit Timeline */
.audit-timeline {
  display: flex;
  flex-direction: column;
  gap: 0.85rem;
  margin-top: 0.75rem;
}

.audit-entry {
  position: relative;
  padding-left: 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.2rem;
}

.audit-dot {
  position: absolute;
  left: 0;
  top: 5px;
  width: 10px;
  height: 10px;
  border-radius: var(--radius-full);
  background: var(--brand-navy);
}

.audit-entry::before {
  content: '';
  position: absolute;
  left: 4px;
  top: 16px;
  bottom: -10px;
  width: 2px;
  background: var(--border-medium);
}

.audit-entry:last-child::before {
  display: none;
}

.audit-meta {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  font-size: 0.78rem;
}

.audit-time {
  color: var(--text-muted);
}

.audit-user {
  color: var(--text-primary);
}

.audit-action-tag {
  font-size: 0.65rem;
  font-weight: 700;
  background: #f1f5f9;
  padding: 0.1rem 0.35rem;
  border-radius: var(--radius-sm);
}

.audit-desc {
  font-size: 0.8rem;
  color: var(--text-secondary);
}

/* ================= DOCUMENTATION MODAL ================= */
.modal-backdrop {
  position: fixed;
  inset: 0;
  background: var(--surface-overlay);
  backdrop-filter: blur(4px);
  z-index: 100;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1.5rem;
  animation: fadeIn 150ms ease;
}

.doc-modal-container {
  background: var(--surface-card);
  border-radius: var(--radius-lg);
  width: 100%;
  max-width: 950px;
  max-height: 90vh;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-xl);
  overflow: hidden;
}

.doc-modal-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.25rem 1.5rem;
  background: var(--brand-navy);
  color: #ffffff;
}

.doc-modal-title-area {
  display: flex;
  align-items: center;
  gap: 0.85rem;
}

.doc-modal-title-area h3 {
  font-family: var(--font-heading);
  font-size: 1.15rem;
  font-weight: 700;
}

.doc-modal-title-area p {
  font-size: 0.74rem;
  color: #cbd5e1;
}

.btn-close {
  color: #ffffff;
  padding: 0.35rem;
  border-radius: var(--radius-sm);
  transition: background var(--transition-fast);
}

.btn-close:hover {
  background: rgba(255, 255, 255, 0.15);
}

.doc-nav-tabs {
  display: flex;
  background: #f8fafc;
  border-bottom: 1px solid var(--border-subtle);
  padding: 0.45rem 1rem;
  gap: 0.5rem;
  overflow-x: auto;
}

.doc-nav-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0.5rem 0.85rem;
  border-radius: var(--radius-sm);
  font-size: 0.8rem;
  font-weight: 600;
  color: var(--text-secondary);
  transition: all var(--transition-fast);
  white-space: nowrap;
}

.doc-nav-btn:hover {
  background: #e2e8f0;
  color: var(--text-primary);
}

.doc-nav-btn.active {
  background: var(--brand-navy);
  color: #ffffff;
}

.doc-modal-body {
  padding: 1.5rem;
  overflow-y: auto;
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
}

.doc-section h4 {
  font-family: var(--font-heading);
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--brand-navy);
  margin: 1rem 0 0.5rem 0;
}

.doc-section h4:first-child {
  margin-top: 0;
}

.doc-section p {
  font-size: 0.86rem;
  color: var(--text-secondary);
  line-height: 1.6;
  margin-bottom: 0.85rem;
}

.info-callout {
  background: #f0fdf4;
  border-left: 4px solid var(--brand-teal);
  padding: 0.85rem 1rem;
  border-radius: 0 var(--radius-sm) var(--radius-sm) 0;
  font-size: 0.84rem;
  color: #166534;
  margin-bottom: 1rem;
}

.doc-list {
  padding-left: 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  font-size: 0.84rem;
  color: var(--text-secondary);
  margin-bottom: 1rem;
}

.formula-card {
  background: #f8fafc;
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-md);
  padding: 1rem 1.25rem;
  margin-bottom: 1rem;
}

.formula-badge {
  display: inline-block;
  font-size: 0.65rem;
  font-weight: 700;
  background: var(--brand-navy);
  color: #ffffff;
  padding: 0.1rem 0.4rem;
  border-radius: var(--radius-sm);
  margin-bottom: 0.35rem;
}

.formula-card h5 {
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--brand-navy);
  margin-bottom: 0.35rem;
}

.equation-box {
  background: #ffffff;
  border: 1px solid var(--border-medium);
  border-radius: var(--radius-sm);
  padding: 0.65rem 1rem;
  margin: 0.5rem 0;
  font-family: var(--font-mono);
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--brand-navy);
}

.highlight-equation {
  border-color: var(--brand-teal);
  background: #f0fdfa;
}

.doc-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.82rem;
  margin: 0.85rem 0 1.25rem 0;
}

.doc-table th {
  background: var(--brand-navy);
  color: #ffffff;
  padding: 0.6rem 0.85rem;
  text-align: left;
}

.doc-table td {
  padding: 0.6rem 0.85rem;
  border: 1px solid var(--border-subtle);
}

.doc-table tr:nth-child(even) {
  background: #f8fafc;
}

.proc-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 1rem;
}

.proc-card {
  background: #f8fafc;
  border: 1px solid var(--border-subtle);
  border-radius: var(--radius-md);
  padding: 1rem;
}

.proc-card h6 {
  font-size: 0.9rem;
  font-weight: 700;
  color: var(--brand-navy);
  margin-bottom: 0.4rem;
}

.proc-card p {
  font-size: 0.8rem;
  margin-bottom: 0;
}

.doc-modal-footer {
  padding: 0.85rem 1.5rem;
  border-top: 1px solid var(--border-subtle);
  display: flex;
  justify-content: flex-end;
  background: #f8fafc;
}

/* ================= PRINT STYLESHEET ================= */
@media print {
  body {
    background: #ffffff !important;
    color: #000000 !important;
  }

  .navbar-wrapper,
  .editor-top-bar,
  .editor-tabs-bar,
  .pane-actions-group,
  .modal-backdrop,
  .btn-trash-row,
  .workflow-action-bar,
  .search-filter-panel,
  .class-breakdown-bar,
  .kpi-grid {
    display: none !important;
  }

  .main-content-area {
    padding: 0 !important;
    max-width: 100% !important;
  }

  .certificate-preview-card,
  .form-card,
  .error-curve-card {
    border: 1px solid #000000 !important;
    box-shadow: none !important;
    page-break-inside: avoid;
  }
}

/* Animations */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(4px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.spin-animation {
  animation: spin 1s linear infinite;
}

@keyframes slideInRight {
  from {
    transform: translateX(100%);
  }
  to {
    transform: translateX(0);
  }
}

.ai-copilot-drawer {
  animation: slideInRight 0.25s cubic-bezier(0.16, 1, 0.3, 1);
}

.btn-ai-action {
  transition: all 0.2s ease;
}

.btn-ai-action:hover {
  background: linear-gradient(135deg, rgba(79, 70, 229, 0.18) 0%, rgba(124, 58, 237, 0.18) 100%) !important;
  transform: translateY(-1px);
}


```

---

### File 13: `src/App.tsx`
*Path: `src/App.tsx` | Size: 17384 bytes | Main Controller, Persistence & State Management*

```tsx
import React, { useState, useEffect } from 'react';
import type { OIMLTestReport, UserProfile } from './types/oiml';
import { INITIAL_REPORTS, DEFAULT_USERS } from './utils/sampleData';
import { evaluateEntireReport } from './utils/metrologyEngine';
import { Navbar } from './components/Navbar';
import { Dashboard } from './components/Dashboard';
import { ReportEditor } from './components/ReportEditor';
import { DocumentationModal } from './components/DocumentationModal';
import { AISettingsModal } from './components/AISettingsModal';
import { AICopilotDrawer } from './components/AICopilotDrawer';
import { getStoredApiKey } from './utils/aiService';
import saveAs from 'file-saver';
import './App.css';

const STORAGE_KEY = 'OIML_R76_REPORTS_V1';

export const App: React.FC = () => {
  const [reports, setReports] = useState<OIMLTestReport[]>(() => {
    try {
      const saved = localStorage.getItem(STORAGE_KEY);
      if (saved) {
        const parsed = JSON.parse(saved);
        if (Array.isArray(parsed) && parsed.length > 0) {
          return parsed;
        }
      }
    } catch (e) {
      console.warn('Failed to load local reports, falling back to samples', e);
    }
    return INITIAL_REPORTS;
  });

  const [currentView, setCurrentView] = useState<'dashboard' | 'editor'>('dashboard');
  const [selectedReportId, setSelectedReportId] = useState<string | null>(null);
  const [isDocuOpen, setIsDocuOpen] = useState(false);
  const [isAISettingsOpen, setIsAISettingsOpen] = useState(false);
  const [isAICopilotOpen, setIsAICopilotOpen] = useState(false);
  const [hasApiKey, setHasApiKey] = useState(() => Boolean(getStoredApiKey()));
  const [activeUser, setActiveUser] = useState<UserProfile>(DEFAULT_USERS[0]);

  const refreshApiKeyStatus = () => {
    setHasApiKey(Boolean(getStoredApiKey()));
  };

  // Persist reports to localStorage whenever changed
  useEffect(() => {
    try {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(reports));
    } catch (e) {
      console.error('Failed to save reports to localStorage', e);
    }
  }, [reports]);

  const selectedReport = reports.find((r) => r.id === selectedReportId) || reports[0];

  const handleSelectReport = (report: OIMLTestReport) => {
    setSelectedReportId(report.id);
    setCurrentView('editor');
  };

  const handleSaveReport = (updatedReport: OIMLTestReport) => {
    setReports((prev) =>
      prev.map((r) => (r.id === updatedReport.id ? updatedReport : r))
    );
  };

  const handleDeleteReport = (id: string) => {
    setReports((prev) => prev.filter((r) => r.id !== id));
    if (selectedReportId === id) {
      setSelectedReportId(null);
      setCurrentView('dashboard');
    }
  };

  const handleDuplicateReport = (reportToClone: OIMLTestReport) => {
    const newId = `rep-${Date.now().toString(36)}`;
    const newRepNo = `OIML-R76/MCA/2026/${Math.floor(1000 + Math.random() * 9000)}`;
    const cloned: OIMLTestReport = {
      ...JSON.parse(JSON.stringify(reportToClone)),
      id: newId,
      createdAt: new Date().toISOString(),
      updatedAt: new Date().toISOString(),
      status: 'under_evaluation',
      instrument: {
        ...reportToClone.instrument,
        id: `inst-${Date.now().toString(36)}`,
        reportNumber: newRepNo,
        serialNumber: `${reportToClone.instrument.serialNumber}-RETEST`,
      },
      auditTrail: [
        {
          id: `aud-${Date.now()}`,
          timestamp: new Date().toISOString(),
          userName: activeUser.name,
          userRole: activeUser.role,
          action: 'CREATED',
          description: `Duplicated from ${reportToClone.instrument.reportNumber} for re-test evaluation.`,
        },
      ],
    };

    const evaluated = evaluateEntireReport(cloned);
    setReports((prev) => [evaluated, ...prev]);
    setSelectedReportId(evaluated.id);
    setCurrentView('editor');
  };

  const handleNewReport = () => {
    const newId = `rep-${Date.now().toString(36)}`;
    const newRepNo = `OIML-R76/MCA/2026/${Math.floor(1000 + Math.random() * 9000)}`;
    const newAppNo = `IND-LM-MA-2026-${Math.floor(10000 + Math.random() * 90000)}`;

    const templateRaw: OIMLTestReport = {
      id: newId,
      createdAt: new Date().toISOString(),
      updatedAt: new Date().toISOString(),
      status: 'draft',
      overallVerdict: 'COMPLIANT',
      evaluatorRemarks: 'Initial test setup initiated for type evaluation.',
      evaluatorSignature: activeUser.name,
      verificationHash: '',
      auditTrail: [
        {
          id: `aud-${Date.now()}`,
          timestamp: new Date().toISOString(),
          userName: activeUser.name,
          userRole: activeUser.role,
          action: 'CREATED',
          description: 'Initialized new blank evaluation test record.',
        },
      ],
      instrument: {
        id: `inst-${Date.now().toString(36)}`,
        reportNumber: newRepNo,
        applicationNumber: newAppNo,
        manufacturer: 'Precision Weigh Systems Ltd',
        applicant: 'Precision Weigh Systems India Ltd',
        model: 'PWS-30 Model-X',
        serialNumber: `SN-${Date.now().toString().slice(-6)}`,
        yearOfManufacture: 2026,
        deviceType: 'Counter Scale',
        accuracyClass: 'III',
        verificationType: 'initial',
        unit: 'kg',
        maxCapacity: 30,
        minCapacity: 0.1, // 20e
        verificationScaleInterval: 0.005,
        actualScaleInterval: 0.005,
        scaleIntervalCount: 6000,
        isMultiInterval: false,
        tareType: 'subtractive',
        maxTare: 15,
        zeroSettingType: 'semi_automatic',
        indicatorModel: 'PWS Digital Terminal 200',
        loadCellModel: 'Single Point 40kg Cell',
        loadCellCertificateNo: 'R60/2000-NL1-18.01',
        loadCellCount: 1,
        platformDimensions: '300 mm x 250 mm Stainless Steel',
      },
      environment: {
        laboratoryName: 'Regional Reference Standards Laboratory (RRSL)',
        laboratoryAddress: 'Legal Metrology Complex, India',
        nablAccreditationNo: 'NABL-TC-8891-2026',
        oimlIssuingAuthority: 'Ministry of Consumer Affairs, Food & Public Distribution',
        evaluationLocation: 'Testing Lab 1',
        testDate: new Date().toISOString().split('T')[0],
        evaluationStartTime: '10:00 AM',
        evaluationEndTime: '04:00 PM',
        ambientTempStart: 21.0,
        ambientTempEnd: 21.5,
        relativeHumidity: 50,
        barometricPressure: 1013,
        mainsVoltage: 230,
        mainsFrequency: 50.0,
        warmUpTimeMinutes: 30,
        standardWeightsClass: 'F1',
        standardWeightsCertNo: 'RRSL-W-2026-F1-01',
        standardWeightsValidity: '2027-06-30',
        standardWeightsUncertainty: 'U = 0.2 mg to 1.5 mg (k=2)',
      },
      weighingTest: {
        zeroErrorStart: 0,
        zeroErrorEnd: 0,
        rows: [
          { step: 1, direction: 'increasing', nominalLoad: 0.1, indication: 0.1, deltaL: 0.0025, trueIndication: 0.1, error: 0, correctedError: 0, mpe: 0.0025, passed: true },
          { step: 2, direction: 'increasing', nominalLoad: 2.5, indication: 2.5, deltaL: 0.0025, trueIndication: 2.5, error: 0, correctedError: 0, mpe: 0.0025, passed: true },
          { step: 3, direction: 'increasing', nominalLoad: 10.0, indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
          { step: 4, direction: 'increasing', nominalLoad: 15.0, indication: 15.0, deltaL: 0.0025, trueIndication: 15.0, error: 0, correctedError: 0, mpe: 0.0075, passed: true },
          { step: 5, direction: 'increasing', nominalLoad: 30.0, indication: 30.0, deltaL: 0.0025, trueIndication: 30.0, error: 0, correctedError: 0, mpe: 0.0075, passed: true },
          { step: 6, direction: 'decreasing', nominalLoad: 30.0, indication: 30.0, deltaL: 0.0025, trueIndication: 30.0, error: 0, correctedError: 0, mpe: 0.0075, passed: true },
          { step: 7, direction: 'decreasing', nominalLoad: 15.0, indication: 15.0, deltaL: 0.0025, trueIndication: 15.0, error: 0, correctedError: 0, mpe: 0.0075, passed: true },
          { step: 8, direction: 'decreasing', nominalLoad: 0.1, indication: 0.1, deltaL: 0.0025, trueIndication: 0.1, error: 0, correctedError: 0, mpe: 0.0025, passed: true },
        ],
        maxCorrectedError: 0,
        maxMpeRatio: 0,
        hysteresisMax: 0,
        hysteresisPassed: true,
        passed: true,
      },
      repeatabilityTest: {
        runsHalfMax: [
          { runIndex: 1, load: 15.0, indication: 15.0, deltaL: 0.0025, trueIndication: 15.0, error: 0 },
          { runIndex: 2, load: 15.0, indication: 15.0, deltaL: 0.0025, trueIndication: 15.0, error: 0 },
          { runIndex: 3, load: 15.0, indication: 15.0, deltaL: 0.0025, trueIndication: 15.0, error: 0 },
        ],
        runsMax: [
          { runIndex: 1, load: 30.0, indication: 30.0, deltaL: 0.0025, trueIndication: 30.0, error: 0 },
          { runIndex: 2, load: 30.0, indication: 30.0, deltaL: 0.0025, trueIndication: 30.0, error: 0 },
          { runIndex: 3, load: 30.0, indication: 30.0, deltaL: 0.0025, trueIndication: 30.0, error: 0 },
        ],
        halfMaxLoad: 15.0,
        halfMaxDiff: 0,
        halfMaxMpe: 0.0075,
        halfMaxPassed: true,
        maxLoad: 30.0,
        maxDiff: 0,
        maxMpe: 0.0075,
        maxPassed: true,
        passed: true,
      },
      eccentricityTest: {
        testLoad: 10.0,
        receptorType: 'rectangular_4_corners',
        points: [
          { positionKey: 'center', positionLabel: 'Center', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
          { positionKey: 'corner_1', positionLabel: 'Front-Left (Corner 1)', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
          { positionKey: 'corner_2', positionLabel: 'Back-Left (Corner 2)', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
          { positionKey: 'corner_3', positionLabel: 'Back-Right (Corner 3)', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
          { positionKey: 'corner_4', positionLabel: 'Front-Right (Corner 4)', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: 0, mpe: 0.005, passed: true },
        ],
        maxSpread: 0,
        maxMpe: 0.005,
        spreadPassed: true,
        passed: true,
      },
      discriminationTest: {
        checks: [
          { loadLevel: 'Min', baseLoad: 0.1, baseIndication: 0.1, extraLoad: 0.007, newIndication: 0.105, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
          { loadLevel: '0.5 Max', baseLoad: 15.0, baseIndication: 15.0, extraLoad: 0.007, newIndication: 15.005, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
          { loadLevel: 'Max', baseLoad: 30.0, baseIndication: 30.0, extraLoad: 0.007, newIndication: 30.005, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
        ],
        passed: true,
      },
      tareTest: {
        tareApplied: 10.0,
        netTestLoad: 15.0,
        indicatedNet: 15.0,
        deltaL: 0.0025,
        trueNet: 15.0,
        netError: 0,
        netMpe: 0.0075,
        tareBalancingError: 0,
        maxPermissibleTareError: 0.00125,
        passed: true,
      },
      zeroTest: {
        zeroErrorE0: 0,
        maxPermissibleE0: 0.00125,
        zeroSettingPassed: true,
        zeroTrackingRate: 0.001,
        maxZeroTrackingRate: 0.0025,
        zeroTrackingPassed: true,
        passed: true,
      },
      tiltingTest: {
        applicable: false,
        tiltRatio: 'Fixed bench mounting',
        zeroIndicationNoTilt: 0,
        zeroIndicationTilted: 0,
        zeroShift: 0,
        maxPermissibleShift: 0.005,
        passed: true,
      },
      temperatureTest: {
        applicable: false,
        points: [],
        passed: true,
      },
    };

    const evaluated = evaluateEntireReport(templateRaw);
    setReports((prev) => [evaluated, ...prev]);
    setSelectedReportId(evaluated.id);
    setCurrentView('editor');
  };

  const handleExportDatabase = () => {
    const dataStr = JSON.stringify(reports, null, 2);
    const blob = new Blob([dataStr], { type: 'application/json' });
    const filename = `OIML_R76_Repository_Backup_${new Date().toISOString().slice(0, 10)}.json`;
    saveAs(blob, filename);
  };

  const handleImportDatabase = (e: React.ChangeEvent<HTMLInputElement>) => {
    const file = e.target.files?.[0];
    if (!file) return;

    const reader = new FileReader();
    reader.onload = (event) => {
      try {
        const content = event.target?.result as string;
        const parsed = JSON.parse(content);
        if (Array.isArray(parsed) && parsed.length > 0) {
          const reEvaluated = parsed.map((item) => evaluateEntireReport(item));
          setReports(reEvaluated);
          alert(`Successfully imported ${reEvaluated.length} test reports!`);
          setCurrentView('dashboard');
        } else {
          alert('Invalid JSON file format. Expected an array of OIML test reports.');
        }
      } catch (err) {
        alert('Failed to parse JSON file.');
      }
    };
    reader.readAsText(file);
    e.target.value = ''; // reset
  };

  return (
    <div className="app-root">
      <Navbar
        currentView={currentView}
        onNavigate={setCurrentView}
        onNewReport={handleNewReport}
        onOpenDocu={() => setIsDocuOpen(true)}
        onOpenAISettings={() => setIsAISettingsOpen(true)}
        onToggleAICopilot={() => setIsAICopilotOpen((prev) => !prev)}
        hasApiKey={hasApiKey}
        activeUser={activeUser}
        availableUsers={DEFAULT_USERS}
        onSwitchUser={setActiveUser}
        onExportDatabase={handleExportDatabase}
        onImportDatabase={handleImportDatabase}
        totalReportsCount={reports.length}
      />

      <main className="main-content-area">
        {currentView === 'dashboard' ? (
          <Dashboard
            reports={reports}
            onSelectReport={handleSelectReport}
            onNewReport={handleNewReport}
            onDeleteReport={handleDeleteReport}
            onDuplicateReport={handleDuplicateReport}
            onOpenAISettings={() => setIsAISettingsOpen(true)}
            hasApiKey={hasApiKey}
          />
        ) : (
          <ReportEditor
            report={selectedReport}
            onSaveReport={handleSaveReport}
            onBackToDashboard={() => setCurrentView('dashboard')}
            activeUser={activeUser}
            onOpenAISettings={() => setIsAISettingsOpen(true)}
          />
        )}
      </main>

      <DocumentationModal isOpen={isDocuOpen} onClose={() => setIsDocuOpen(false)} />

      <AISettingsModal
        isOpen={isAISettingsOpen}
        onClose={() => setIsAISettingsOpen(false)}
        onKeyUpdated={refreshApiKeyStatus}
      />

      <AICopilotDrawer
        isOpen={isAICopilotOpen}
        onClose={() => setIsAICopilotOpen(false)}
        activeReport={selectedReport}
        onOpenSettings={() => {
          setIsAICopilotOpen(false);
          setIsAISettingsOpen(true);
        }}
        onApplyRemarks={(remarks) => {
          if (selectedReport) {
            const updated = {
              ...selectedReport,
              evaluatorRemarks: remarks,
              auditTrail: [
                ...selectedReport.auditTrail,
                {
                  id: `aud-${Date.now()}`,
                  timestamp: new Date().toISOString(),
                  userName: activeUser.name,
                  userRole: activeUser.role,
                  action: 'UPDATED' as const,
                  description: 'Applied AI-generated findings to evaluator remarks.',
                },
              ],
            };
            handleSaveReport(updated);
          }
        }}
      />

      {/* Persistent Floating Gemma 4 API Key Button */}
      <button
        onClick={() => setIsAISettingsOpen(true)}
        style={{
          position: 'fixed',
          bottom: '24px',
          right: '24px',
          zIndex: 99999,
          background: '#4f46e5',
          color: '#ffffff',
          border: '2px solid #ffffff',
          borderRadius: '50px',
          padding: '12px 20px',
          boxShadow: '0 8px 24px rgba(79, 70, 229, 0.45)',
          cursor: 'pointer',
          fontWeight: 700,
          display: 'flex',
          alignItems: 'center',
          gap: '8px',
          fontSize: '13px',
          transition: 'transform 0.2s, box-shadow 0.2s',
        }}
        onMouseEnter={(e) => (e.currentTarget.style.transform = 'scale(1.05)')}
        onMouseLeave={(e) => (e.currentTarget.style.transform = 'scale(1)')}
      >
        <span style={{ fontSize: '16px' }}>🔑</span>
        <span>{hasApiKey ? 'Gemma 4 API Key Active' : 'Configure Gemma 4 API Key'}</span>
        <span
          style={{
            width: '9px',
            height: '9px',
            borderRadius: '50%',
            backgroundColor: hasApiKey ? '#34d399' : '#fbbf24',
            display: 'inline-block',
            boxShadow: hasApiKey ? '0 0 6px #34d399' : '0 0 6px #fbbf24',
          }}
        />
      </button>
    </div>
  );
};
export default App;

```

---

### File 14: `src/assets/hero.png`
*Path: `src/assets/hero.png` | Size: 13057 bytes | Source File*

> [!NOTE]
> *Binary file (.png). File is included in the project directory.* 

---

### File 15: `src/assets/react.svg`
*Path: `src/assets/react.svg` | Size: 4126 bytes | Source File*

```xml
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--logos" width="35.93" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 228"><path fill="#00D8FF" d="M210.483 73.824a171.49 171.49 0 0 0-8.24-2.597c.465-1.9.893-3.777 1.273-5.621c6.238-30.281 2.16-54.676-11.769-62.708c-13.355-7.7-35.196.329-57.254 19.526a171.23 171.23 0 0 0-6.375 5.848a155.866 155.866 0 0 0-4.241-3.917C100.759 3.829 77.587-4.822 63.673 3.233C50.33 10.957 46.379 33.89 51.995 62.588a170.974 170.974 0 0 0 1.892 8.48c-3.28.932-6.445 1.924-9.474 2.98C17.309 83.498 0 98.307 0 113.668c0 15.865 18.582 31.778 46.812 41.427a145.52 145.52 0 0 0 6.921 2.165a167.467 167.467 0 0 0-2.01 9.138c-5.354 28.2-1.173 50.591 12.134 58.266c13.744 7.926 36.812-.22 59.273-19.855a145.567 145.567 0 0 0 5.342-4.923a168.064 168.064 0 0 0 6.92 6.314c21.758 18.722 43.246 26.282 56.54 18.586c13.731-7.949 18.194-32.003 12.4-61.268a145.016 145.016 0 0 0-1.535-6.842c1.62-.48 3.21-.974 4.76-1.488c29.348-9.723 48.443-25.443 48.443-41.52c0-15.417-17.868-30.326-45.517-39.844Zm-6.365 70.984c-1.4.463-2.836.91-4.3 1.345c-3.24-10.257-7.612-21.163-12.963-32.432c5.106-11 9.31-21.767 12.459-31.957c2.619.758 5.16 1.557 7.61 2.4c23.69 8.156 38.14 20.213 38.14 29.504c0 9.896-15.606 22.743-40.946 31.14Zm-10.514 20.834c2.562 12.94 2.927 24.64 1.23 33.787c-1.524 8.219-4.59 13.698-8.382 15.893c-8.067 4.67-25.32-1.4-43.927-17.412a156.726 156.726 0 0 1-6.437-5.87c7.214-7.889 14.423-17.06 21.459-27.246c12.376-1.098 24.068-2.894 34.671-5.345a134.17 134.17 0 0 1 1.386 6.193ZM87.276 214.515c-7.882 2.783-14.16 2.863-17.955.675c-8.075-4.657-11.432-22.636-6.853-46.752a156.923 156.923 0 0 1 1.869-8.499c10.486 2.32 22.093 3.988 34.498 4.994c7.084 9.967 14.501 19.128 21.976 27.15a134.668 134.668 0 0 1-4.877 4.492c-9.933 8.682-19.886 14.842-28.658 17.94ZM50.35 144.747c-12.483-4.267-22.792-9.812-29.858-15.863c-6.35-5.437-9.555-10.836-9.555-15.216c0-9.322 13.897-21.212 37.076-29.293c2.813-.98 5.757-1.905 8.812-2.773c3.204 10.42 7.406 21.315 12.477 32.332c-5.137 11.18-9.399 22.249-12.634 32.792a134.718 134.718 0 0 1-6.318-1.979Zm12.378-84.26c-4.811-24.587-1.616-43.134 6.425-47.789c8.564-4.958 27.502 2.111 47.463 19.835a144.318 144.318 0 0 1 3.841 3.545c-7.438 7.987-14.787 17.08-21.808 26.988c-12.04 1.116-23.565 2.908-34.161 5.309a160.342 160.342 0 0 1-1.76-7.887Zm110.427 27.268a347.8 347.8 0 0 0-7.785-12.803c8.168 1.033 15.994 2.404 23.343 4.08c-2.206 7.072-4.956 14.465-8.193 22.045a381.151 381.151 0 0 0-7.365-13.322Zm-45.032-43.861c5.044 5.465 10.096 11.566 15.065 18.186a322.04 322.04 0 0 0-30.257-.006c4.974-6.559 10.069-12.652 15.192-18.18ZM82.802 87.83a323.167 323.167 0 0 0-7.227 13.238c-3.184-7.553-5.909-14.98-8.134-22.152c7.304-1.634 15.093-2.97 23.209-3.984a321.524 321.524 0 0 0-7.848 12.897Zm8.081 65.352c-8.385-.936-16.291-2.203-23.593-3.793c2.26-7.3 5.045-14.885 8.298-22.6a321.187 321.187 0 0 0 7.257 13.246c2.594 4.48 5.28 8.868 8.038 13.147Zm37.542 31.03c-5.184-5.592-10.354-11.779-15.403-18.433c4.902.192 9.899.29 14.978.29c5.218 0 10.376-.117 15.453-.343c-4.985 6.774-10.018 12.97-15.028 18.486Zm52.198-57.817c3.422 7.8 6.306 15.345 8.596 22.52c-7.422 1.694-15.436 3.058-23.88 4.071a382.417 382.417 0 0 0 7.859-13.026a347.403 347.403 0 0 0 7.425-13.565Zm-16.898 8.101a358.557 358.557 0 0 1-12.281 19.815a329.4 329.4 0 0 1-23.444.823c-7.967 0-15.716-.248-23.178-.732a310.202 310.202 0 0 1-12.513-19.846h.001a307.41 307.41 0 0 1-10.923-20.627a310.278 310.278 0 0 1 10.89-20.637l-.001.001a307.318 307.318 0 0 1 12.413-19.761c7.613-.576 15.42-.876 23.31-.876H128c7.926 0 15.743.303 23.354.883a329.357 329.357 0 0 1 12.335 19.695a358.489 358.489 0 0 1 11.036 20.54a329.472 329.472 0 0 1-11 20.722Zm22.56-122.124c8.572 4.944 11.906 24.881 6.52 51.026c-.344 1.668-.73 3.367-1.15 5.09c-10.622-2.452-22.155-4.275-34.23-5.408c-7.034-10.017-14.323-19.124-21.64-27.008a160.789 160.789 0 0 1 5.888-5.4c18.9-16.447 36.564-22.941 44.612-18.3ZM128 90.808c12.625 0 22.86 10.235 22.86 22.86s-10.235 22.86-22.86 22.86s-22.86-10.235-22.86-22.86s10.235-22.86 22.86-22.86Z"></path></svg>
```

---

### File 16: `src/assets/vite.svg`
*Path: `src/assets/vite.svg` | Size: 8709 bytes | Source File*

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="77" height="47" fill="none" aria-labelledby="vite-logo-title" viewBox="0 0 77 47"><title id="vite-logo-title">Vite</title><style>.parenthesis{fill:#000}@media (prefers-color-scheme:dark){.parenthesis{fill:#fff}}</style><path fill="#9135ff" d="M40.151 45.71c-.663.844-2.02.374-2.02-.699V34.708a2.26 2.26 0 0 0-2.262-2.262H24.493c-.92 0-1.457-1.04-.92-1.788l7.479-10.471c1.07-1.498 0-3.578-1.842-3.578H15.443c-.92 0-1.456-1.04-.92-1.788l9.696-13.576c.213-.297.556-.474.92-.474h28.894c.92 0 1.456 1.04.92 1.788l-7.48 10.472c-1.07 1.497 0 3.578 1.842 3.578h11.376c.944 0 1.474 1.087.89 1.83L40.153 45.712z"/><mask id="a" width="48" height="47" x="14" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path fill="#000" d="M40.047 45.71c-.663.843-2.02.374-2.02-.699V34.708a2.26 2.26 0 0 0-2.262-2.262H24.389c-.92 0-1.457-1.04-.92-1.788l7.479-10.472c1.07-1.497 0-3.578-1.842-3.578H15.34c-.92 0-1.456-1.04-.92-1.788l9.696-13.575c.213-.297.556-.474.92-.474H53.93c.92 0 1.456 1.04.92 1.788L47.37 13.03c-1.07 1.498 0 3.578 1.842 3.578h11.376c.944 0 1.474 1.088.89 1.831L40.049 45.712z"/></mask><g mask="url(#a)"><g filter="url(#b)"><ellipse cx="5.508" cy="14.704" fill="#eee6ff" rx="5.508" ry="14.704" transform="rotate(269.814 20.96 11.29)scale(-1 1)"/></g><g filter="url(#c)"><ellipse cx="10.399" cy="29.851" fill="#eee6ff" rx="10.399" ry="29.851" transform="rotate(89.814 -16.902 -8.275)scale(1 -1)"/></g><g filter="url(#d)"><ellipse cx="5.508" cy="30.487" fill="#8900ff" rx="5.508" ry="30.487" transform="rotate(89.814 -19.197 -7.127)scale(1 -1)"/></g><g filter="url(#e)"><ellipse cx="5.508" cy="30.599" fill="#8900ff" rx="5.508" ry="30.599" transform="rotate(89.814 -25.928 4.177)scale(1 -1)"/></g><g filter="url(#f)"><ellipse cx="5.508" cy="30.599" fill="#8900ff" rx="5.508" ry="30.599" transform="rotate(89.814 -25.738 5.52)scale(1 -1)"/></g><g filter="url(#g)"><ellipse cx="14.072" cy="22.078" fill="#eee6ff" rx="14.072" ry="22.078" transform="rotate(93.35 31.245 55.578)scale(-1 1)"/></g><g filter="url(#h)"><ellipse cx="3.47" cy="21.501" fill="#8900ff" rx="3.47" ry="21.501" transform="rotate(89.009 35.419 55.202)scale(-1 1)"/></g><g filter="url(#i)"><ellipse cx="3.47" cy="21.501" fill="#8900ff" rx="3.47" ry="21.501" transform="rotate(89.009 35.419 55.202)scale(-1 1)"/></g><g filter="url(#j)"><ellipse cx="14.592" cy="9.743" fill="#8900ff" rx="4.407" ry="29.108" transform="rotate(39.51 14.592 9.743)"/></g><g filter="url(#k)"><ellipse cx="61.728" cy="-5.321" fill="#8900ff" rx="4.407" ry="29.108" transform="rotate(37.892 61.728 -5.32)"/></g><g filter="url(#l)"><ellipse cx="55.618" cy="7.104" fill="#00c2ff" rx="5.971" ry="9.665" transform="rotate(37.892 55.618 7.104)"/></g><g filter="url(#m)"><ellipse cx="12.326" cy="39.103" fill="#8900ff" rx="4.407" ry="29.108" transform="rotate(37.892 12.326 39.103)"/></g><g filter="url(#n)"><ellipse cx="12.326" cy="39.103" fill="#8900ff" rx="4.407" ry="29.108" transform="rotate(37.892 12.326 39.103)"/></g><g filter="url(#o)"><ellipse cx="49.857" cy="30.678" fill="#8900ff" rx="4.407" ry="29.108" transform="rotate(37.892 49.857 30.678)"/></g><g filter="url(#p)"><ellipse cx="52.623" cy="33.171" fill="#00c2ff" rx="5.971" ry="15.297" transform="rotate(37.892 52.623 33.17)"/></g></g><path d="M6.919 0c-9.198 13.166-9.252 33.575 0 46.789h6.215c-9.25-13.214-9.196-33.623 0-46.789zm62.424 0h-6.215c9.198 13.166 9.252 33.575 0 46.789h6.215c9.25-13.214 9.196-33.623 0-46.789" class="parenthesis"/><defs><filter id="b" width="60.045" height="41.654" x="-5.564" y="16.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="7.659"/></filter><filter id="c" width="90.34" height="51.437" x="-40.407" y="-6.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="7.659"/></filter><filter id="d" width="79.355" height="29.4" x="-35.435" y="2.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="e" width="79.579" height="29.4" x="-30.84" y="20.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="f" width="79.579" height="29.4" x="-29.307" y="21.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="g" width="74.749" height="58.852" x="29.961" y="-17.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="7.659"/></filter><filter id="h" width="61.377" height="25.362" x="37.754" y="3.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="i" width="61.377" height="25.362" x="37.754" y="3.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="j" width="56.045" height="63.649" x="-13.43" y="-22.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="k" width="54.814" height="64.646" x="34.321" y="-37.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="l" width="33.541" height="35.313" x="38.847" y="-10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="m" width="54.814" height="64.646" x="-15.081" y="6.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="n" width="54.814" height="64.646" x="-15.081" y="6.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="o" width="54.814" height="64.646" x="22.45" y="-1.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter><filter id="p" width="39.409" height="43.623" x="32.919" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2002_17286" stdDeviation="4.596"/></filter></defs></svg>

```

---

### File 17: `src/components/AICopilotDrawer.tsx`
*Path: `src/components/AICopilotDrawer.tsx` | Size: 19766 bytes | Context-Aware Metrology AI Copilot Chat Drawer*

```tsx
import React, { useState, useEffect, useRef } from 'react';
import {
  X,
  Send,
  Sparkles,
  Bot,
  User,
  Copy,
  Check,
  FileText,
  AlertCircle,
  HelpCircle,
  RotateCcw,
  Key,
} from 'lucide-react';
import type { OIMLTestReport } from '../types/oiml';
import {
  getStoredApiKey,
  getStoredModel,
  AVAILABLE_MODELS,
  chatWithGemmaMetrology,
  generateEvaluatorRemarksWithGemma,
  diagnoseInstrumentFailureWithGemma,
  type ChatMessage,
} from '../utils/aiService';

interface AICopilotDrawerProps {
  isOpen: boolean;
  onClose: () => void;
  activeReport?: OIMLTestReport;
  onOpenSettings: () => void;
  onApplyRemarks?: (remarks: string) => void;
}

export const AICopilotDrawer: React.FC<AICopilotDrawerProps> = ({
  isOpen,
  onClose,
  activeReport,
  onOpenSettings,
  onApplyRemarks,
}) => {
  const [messages, setMessages] = useState<ChatMessage[]>([]);
  const [inputValue, setInputValue] = useState('');
  const [loading, setLoading] = useState(false);
  const [copiedIndex, setCopiedIndex] = useState<number | null>(null);
  const [appliedIndex, setAppliedIndex] = useState<number | null>(null);
  const messagesEndRef = useRef<HTMLDivElement>(null);

  const hasApiKey = Boolean(getStoredApiKey());
  const selectedModelId = getStoredModel();
  const currentModelName =
    AVAILABLE_MODELS.find((m) => m.id === selectedModelId)?.name || 'Gemma 4';

  // Initialize greeting when opened
  useEffect(() => {
    if (isOpen && messages.length === 0) {
      const instrumentLabel = activeReport
        ? `${activeReport.instrument.model} (Class ${activeReport.instrument.accuracyClass}, ${activeReport.instrument.maxCapacity} ${activeReport.instrument.unit})`
        : 'your active weighing instrument';

      setMessages([
        {
          role: 'assistant',
          content: `👋 Hello! I am your **OIML R 76 Metrology AI Copilot** powered by **${currentModelName}**.\n\nI have loaded the test data for **${instrumentLabel}**.\n\nYou can ask me to draft evaluator findings, verify Table 6 MPE limits, diagnose corner load cell errors, or explain any OIML R 76 clause.`,
        },
      ]);
    }
  }, [isOpen, activeReport, currentModelName, messages.length]);

  // Scroll to bottom on new messages
  useEffect(() => {
    if (isOpen) {
      messagesEndRef.current?.scrollIntoView({ behavior: 'smooth' });
    }
  }, [messages, isOpen, loading]);

  if (!isOpen) return null;

  const handleSendMessage = async (textToSend?: string) => {
    const text = (textToSend || inputValue).trim();
    if (!text || loading) return;

    if (!hasApiKey) {
      onOpenSettings();
      return;
    }

    const newMessages: ChatMessage[] = [...messages, { role: 'user', content: text }];
    setMessages(newMessages);
    setInputValue('');
    setLoading(true);

    try {
      const reply = await chatWithGemmaMetrology(newMessages, activeReport);
      setMessages([...newMessages, { role: 'assistant', content: reply }]);
    } catch (err: any) {
      setMessages([
        ...newMessages,
        {
          role: 'assistant',
          content: `⚠️ **Gemma AI Error**: ${err.message || 'Failed to generate response. Please check your API key or model.'}`,
        },
      ]);
    } finally {
      setLoading(false);
    }
  };

  const handleDraftRemarks = async () => {
    if (!activeReport) return;
    if (!hasApiKey) {
      onOpenSettings();
      return;
    }

    const userPrompt = 'Draft comprehensive OIML R 76-2 Type Evaluation findings and remarks for this instrument.';
    const newMessages: ChatMessage[] = [...messages, { role: 'user', content: userPrompt }];
    setMessages(newMessages);
    setLoading(true);

    try {
      const remarks = await generateEvaluatorRemarksWithGemma(activeReport);
      setMessages([...newMessages, { role: 'assistant', content: remarks }]);
    } catch (err: any) {
      setMessages([
        ...newMessages,
        {
          role: 'assistant',
          content: `⚠️ **Gemma AI Error**: ${err.message}`,
        },
      ]);
    } finally {
      setLoading(false);
    }
  };

  const handleDiagnoseFailures = async () => {
    if (!activeReport) return;
    if (!hasApiKey) {
      onOpenSettings();
      return;
    }

    const userPrompt = 'Diagnose any metrological anomalies, corner load imbalances, or tolerance risks for this instrument.';
    const newMessages: ChatMessage[] = [...messages, { role: 'user', content: userPrompt }];
    setMessages(newMessages);
    setLoading(true);

    try {
      const diagnosis = await diagnoseInstrumentFailureWithGemma(activeReport);
      setMessages([...newMessages, { role: 'assistant', content: diagnosis }]);
    } catch (err: any) {
      setMessages([
        ...newMessages,
        {
          role: 'assistant',
          content: `⚠️ **Gemma AI Error**: ${err.message}`,
        },
      ]);
    } finally {
      setLoading(false);
    }
  };

  const handleCopyMessage = (text: string, index: number) => {
    navigator.clipboard.writeText(text);
    setCopiedIndex(index);
    setTimeout(() => setCopiedIndex(null), 2000);
  };

  const handleApplyToReport = (text: string, index: number) => {
    if (onApplyRemarks) {
      onApplyRemarks(text);
      setAppliedIndex(index);
      setTimeout(() => setAppliedIndex(null), 2500);
    }
  };

  const handleResetChat = () => {
    setMessages([]);
  };

  return (
    <aside
      className="ai-copilot-drawer"
      style={{
        position: 'fixed',
        top: 0,
        right: 0,
        bottom: 0,
        width: '460px',
        maxWidth: '100vw',
        backgroundColor: 'var(--bg-surface, #ffffff)',
        borderLeft: '1px solid var(--border-color)',
        boxShadow: '-4px 0 24px rgba(0, 0, 0, 0.12)',
        zIndex: 1000,
        display: 'flex',
        flexDirection: 'column',
      }}
    >
      {/* Drawer Header */}
      <div
        style={{
          padding: '16px 20px',
          borderBottom: '1px solid var(--border-color)',
          display: 'flex',
          alignItems: 'center',
          justifyContent: 'space-between',
          background: 'linear-gradient(to right, #f8fafc, #eff6ff)',
        }}
      >
        <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
          <div
            style={{
              width: '32px',
              height: '32px',
              borderRadius: '8px',
              background: 'linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%)',
              color: '#ffffff',
              display: 'flex',
              alignItems: 'center',
              justifyContent: 'center',
            }}
          >
            <Sparkles size={18} />
          </div>
          <div>
            <div style={{ display: 'flex', alignItems: 'center', gap: '6px' }}>
              <h3 style={{ margin: 0, fontSize: '1rem', fontWeight: 700 }}>
                Metrology AI Copilot
              </h3>
              <span
                style={{
                  fontSize: '0.68rem',
                  padding: '2px 6px',
                  borderRadius: '4px',
                  backgroundColor: '#ede9fe',
                  color: '#6d28d9',
                  fontWeight: 600,
                }}
              >
                {currentModelName}
              </span>
            </div>
            <span style={{ fontSize: '0.74rem', color: 'var(--text-muted)' }}>
              OIML R 76-1:2006 & Legal Metrology Act Advisor
            </span>
          </div>
        </div>

        <div style={{ display: 'flex', alignItems: 'center', gap: '4px' }}>
          <button
            className="btn-icon"
            onClick={handleResetChat}
            title="Reset conversation"
            style={{ padding: '6px' }}
          >
            <RotateCcw size={16} />
          </button>
          <button
            className="btn-icon"
            onClick={onClose}
            title="Close drawer"
            style={{ padding: '6px' }}
          >
            <X size={18} />
          </button>
        </div>
      </div>

      {/* Active Instrument Context Bar */}
      {activeReport && (
        <div
          style={{
            padding: '8px 16px',
            backgroundColor: '#f1f5f9',
            borderBottom: '1px solid var(--border-color)',
            fontSize: '0.75rem',
            display: 'flex',
            alignItems: 'center',
            justifyContent: 'space-between',
          }}
        >
          <span style={{ display: 'flex', alignItems: 'center', gap: '6px', color: 'var(--text-secondary)' }}>
            <FileText size={13} style={{ color: 'var(--color-primary)' }} />
            Active: <strong>{activeReport.instrument.model}</strong> (Class {activeReport.instrument.accuracyClass})
          </span>
          <span
            style={{
              padding: '2px 6px',
              borderRadius: '4px',
              fontSize: '0.7rem',
              fontWeight: 700,
              backgroundColor: activeReport.overallVerdict === 'COMPLIANT' ? '#ecfdf5' : '#fef2f2',
              color: activeReport.overallVerdict === 'COMPLIANT' ? '#059669' : '#dc2626',
            }}
          >
            {activeReport.overallVerdict}
          </span>
        </div>
      )}

      {/* Missing Key Banner */}
      {!hasApiKey && (
        <div
          style={{
            padding: '12px 16px',
            backgroundColor: '#fffbeb',
            borderBottom: '1px solid #fde68a',
            display: 'flex',
            alignItems: 'center',
            justifyContent: 'space-between',
            gap: '8px',
          }}
        >
          <div style={{ display: 'flex', alignItems: 'center', gap: '8px', fontSize: '0.8rem', color: '#92400e' }}>
            <Key size={16} style={{ color: '#d97706', flexShrink: 0 }} />
            <span>API Key needed to enable Gemma 4</span>
          </div>
          <button
            onClick={onOpenSettings}
            style={{
              padding: '4px 10px',
              fontSize: '0.75rem',
              fontWeight: 600,
              backgroundColor: '#d97706',
              color: '#ffffff',
              border: 'none',
              borderRadius: '4px',
              cursor: 'pointer',
            }}
          >
            Enter Key
          </button>
        </div>
      )}

      {/* Quick Action Chips */}
      {activeReport && (
        <div
          style={{
            padding: '8px 16px',
            display: 'flex',
            gap: '6px',
            overflowX: 'auto',
            borderBottom: '1px solid var(--border-color)',
            backgroundColor: 'var(--bg-card, #f8fafc)',
          }}
        >
          <button
            onClick={handleDraftRemarks}
            disabled={loading}
            style={{
              fontSize: '0.72rem',
              padding: '4px 10px',
              borderRadius: '14px',
              border: '1px solid #cbd5e1',
              backgroundColor: '#ffffff',
              cursor: 'pointer',
              whiteSpace: 'nowrap',
              display: 'inline-flex',
              alignItems: 'center',
              gap: '4px',
              color: '#334155',
              fontWeight: 500,
            }}
          >
            <Sparkles size={12} style={{ color: '#7c3aed' }} />
            Draft Official Remarks
          </button>
          <button
            onClick={handleDiagnoseFailures}
            disabled={loading}
            style={{
              fontSize: '0.72rem',
              padding: '4px 10px',
              borderRadius: '14px',
              border: '1px solid #cbd5e1',
              backgroundColor: '#ffffff',
              cursor: 'pointer',
              whiteSpace: 'nowrap',
              display: 'inline-flex',
              alignItems: 'center',
              gap: '4px',
              color: '#334155',
              fontWeight: 500,
            }}
          >
            <AlertCircle size={12} style={{ color: '#dc2626' }} />
            Diagnose Anomalies
          </button>
          <button
            onClick={() => handleSendMessage('Explain OIML R 76 Table 6 MPE limits and how step boundaries apply to this scale.')}
            disabled={loading}
            style={{
              fontSize: '0.72rem',
              padding: '4px 10px',
              borderRadius: '14px',
              border: '1px solid #cbd5e1',
              backgroundColor: '#ffffff',
              cursor: 'pointer',
              whiteSpace: 'nowrap',
              display: 'inline-flex',
              alignItems: 'center',
              gap: '4px',
              color: '#334155',
              fontWeight: 500,
            }}
          >
            <HelpCircle size={12} style={{ color: '#0284c7' }} />
            Table 6 MPE
          </button>
        </div>
      )}

      {/* Messages Scroll Area */}
      <div
        style={{
          flex: 1,
          overflowY: 'auto',
          padding: '16px',
          display: 'flex',
          flexDirection: 'column',
          gap: '14px',
        }}
      >
        {messages.map((msg, index) => {
          const isUser = msg.role === 'user';
          return (
            <div
              key={index}
              style={{
                display: 'flex',
                gap: '10px',
                alignItems: 'flex-start',
                flexDirection: isUser ? 'row-reverse' : 'row',
              }}
            >
              <div
                style={{
                  width: '28px',
                  height: '28px',
                  borderRadius: '50%',
                  display: 'flex',
                  alignItems: 'center',
                  justifyContent: 'center',
                  flexShrink: 0,
                  backgroundColor: isUser ? 'var(--color-primary)' : '#ede9fe',
                  color: isUser ? '#ffffff' : '#6d28d9',
                }}
              >
                {isUser ? <User size={15} /> : <Bot size={15} />}
              </div>

              <div
                style={{
                  maxWidth: '84%',
                  borderRadius: isUser ? '14px 14px 2px 14px' : '14px 14px 14px 2px',
                  padding: '10px 14px',
                  fontSize: '0.86rem',
                  lineHeight: '1.45',
                  backgroundColor: isUser ? 'var(--color-primary)' : 'var(--bg-card, #f8fafc)',
                  color: isUser ? '#ffffff' : 'var(--text-primary)',
                  border: isUser ? 'none' : '1px solid var(--border-color)',
                  whiteSpace: 'pre-wrap',
                  position: 'relative',
                }}
              >
                {msg.content}

                {!isUser && (
                  <div
                    style={{
                      marginTop: '8px',
                      paddingTop: '6px',
                      borderTop: '1px solid #e2e8f0',
                      display: 'flex',
                      alignItems: 'center',
                      gap: '8px',
                    }}
                  >
                    <button
                      onClick={() => handleCopyMessage(msg.content, index)}
                      style={{
                        background: 'none',
                        border: 'none',
                        padding: '2px 6px',
                        cursor: 'pointer',
                        display: 'inline-flex',
                        alignItems: 'center',
                        gap: '4px',
                        fontSize: '0.72rem',
                        color: 'var(--text-muted)',
                      }}
                      title="Copy response"
                    >
                      {copiedIndex === index ? <Check size={12} color="#10b981" /> : <Copy size={12} />}
                      <span>{copiedIndex === index ? 'Copied!' : 'Copy'}</span>
                    </button>

                    {onApplyRemarks && (
                      <button
                        onClick={() => handleApplyToReport(msg.content, index)}
                        style={{
                          background: 'none',
                          border: 'none',
                          padding: '2px 6px',
                          cursor: 'pointer',
                          display: 'inline-flex',
                          alignItems: 'center',
                          gap: '4px',
                          fontSize: '0.72rem',
                          color: '#4f46e5',
                          fontWeight: 600,
                        }}
                        title="Insert this into the report evaluator remarks"
                      >
                        {appliedIndex === index ? <Check size={12} color="#10b981" /> : <FileText size={12} />}
                        <span>{appliedIndex === index ? 'Inserted into Remarks!' : 'Apply to Remarks'}</span>
                      </button>
                    )}
                  </div>
                )}
              </div>
            </div>
          );
        })}

        {loading && (
          <div style={{ display: 'flex', gap: '10px', alignItems: 'center' }}>
            <div
              style={{
                width: '28px',
                height: '28px',
                borderRadius: '50%',
                backgroundColor: '#ede9fe',
                color: '#6d28d9',
                display: 'flex',
                alignItems: 'center',
                justifyContent: 'center',
              }}
            >
              <Bot size={15} />
            </div>
            <div
              style={{
                backgroundColor: '#f8fafc',
                border: '1px solid var(--border-color)',
                borderRadius: '14px 14px 14px 2px',
                padding: '10px 14px',
                fontSize: '0.84rem',
                color: 'var(--text-muted)',
                display: 'flex',
                alignItems: 'center',
                gap: '8px',
              }}
            >
              <Sparkles size={15} className="spin-animation" style={{ color: '#7c3aed' }} />
              <span>Gemma 4 is analyzing metrological data...</span>
            </div>
          </div>
        )}

        <div ref={messagesEndRef} />
      </div>

      {/* Drawer Input Box */}
      <div
        style={{
          padding: '12px 16px',
          borderTop: '1px solid var(--border-color)',
          backgroundColor: 'var(--bg-surface, #ffffff)',
        }}
      >
        <form
          onSubmit={(e) => {
            e.preventDefault();
            handleSendMessage();
          }}
          style={{ display: 'flex', gap: '8px', alignItems: 'center' }}
        >
          <input
            type="text"
            value={inputValue}
            onChange={(e) => setInputValue(e.target.value)}
            placeholder={hasApiKey ? 'Ask Gemma 4 anything about OIML R 76...' : 'Configure API key first...'}
            disabled={loading}
            style={{
              flex: 1,
              padding: '10px 14px',
              fontSize: '0.88rem',
              borderRadius: '8px',
              border: '1px solid var(--border-color)',
              backgroundColor: 'var(--bg-input, #ffffff)',
              color: 'var(--text-primary)',
            }}
          />
          <button
            type="submit"
            className="btn-primary"
            disabled={loading || !inputValue.trim()}
            style={{
              padding: '10px 14px',
              borderRadius: '8px',
              display: 'inline-flex',
              alignItems: 'center',
              justifyContent: 'center',
            }}
            title="Send query"
          >
            <Send size={16} />
          </button>
        </form>
      </div>
    </aside>
  );
};

```

---

### File 18: `src/components/AISettingsModal.tsx`
*Path: `src/components/AISettingsModal.tsx` | Size: 14766 bytes | Gemma 4 API Key Management & Connection Tester Modal*

```tsx
import React, { useState, useEffect } from 'react';
import {
  X,
  Key,
  Cpu,
  CheckCircle2,
  AlertTriangle,
  ExternalLink,
  ShieldCheck,
  Eye,
  EyeOff,
  Sparkles,
  RefreshCw,
  Trash2,
} from 'lucide-react';
import {
  AVAILABLE_MODELS,
  getStoredApiKey,
  setStoredApiKey,
  getStoredModel,
  setStoredModel,
  testGemmaConnection,
} from '../utils/aiService';

interface AISettingsModalProps {
  isOpen: boolean;
  onClose: () => void;
  onKeyUpdated: () => void;
}

export const AISettingsModal: React.FC<AISettingsModalProps> = ({
  isOpen,
  onClose,
  onKeyUpdated,
}) => {
  const [apiKey, setApiKey] = useState('');
  const [showKey, setShowKey] = useState(false);
  const [selectedModel, setSelectedModel] = useState('gemma-4-31b-it');
  const [testing, setTesting] = useState(false);
  const [testResult, setTestResult] = useState<{
    success: boolean;
    message: string;
  } | null>(null);
  const [saveSuccess, setSaveSuccess] = useState(false);

  useEffect(() => {
    if (isOpen) {
      setApiKey(getStoredApiKey());
      setSelectedModel(getStoredModel());
      setTestResult(null);
      setSaveSuccess(false);
    }
  }, [isOpen]);

  if (!isOpen) return null;

  const handleSave = () => {
    setStoredApiKey(apiKey);
    setStoredModel(selectedModel);
    setSaveSuccess(true);
    onKeyUpdated();
    setTimeout(() => {
      setSaveSuccess(false);
      onClose();
    }, 900);
  };

  const handleClear = () => {
    setStoredApiKey('');
    setApiKey('');
    setTestResult(null);
    onKeyUpdated();
  };

  const handleTestConnection = async () => {
    if (!apiKey.trim()) {
      setTestResult({
        success: false,
        message: 'Please enter an API key first before testing.',
      });
      return;
    }
    setTesting(true);
    setTestResult(null);
    try {
      const res = await testGemmaConnection(apiKey, selectedModel);
      setTestResult(res);
    } catch (err: any) {
      setTestResult({
        success: false,
        message: err.message || 'Connection test failed',
      });
    } finally {
      setTesting(false);
    }
  };

  return (
    <div className="modal-backdrop" onClick={onClose}>
      <div
        className="modal-container ai-settings-modal"
        onClick={(e) => e.stopPropagation()}
        style={{ maxWidth: '640px' }}
      >
        {/* Modal Header */}
        <div className="modal-header">
          <div className="modal-title-box">
            <div
              style={{
                display: 'inline-flex',
                alignItems: 'center',
                justifyContent: 'center',
                width: '36px',
                height: '36px',
                borderRadius: '8px',
                background: 'linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%)',
                color: '#ffffff',
                marginRight: '12px',
              }}
            >
              <Sparkles size={20} />
            </div>
            <div>
              <h2 style={{ margin: 0, fontSize: '1.25rem', fontWeight: 700 }}>
                Gemma 4 & Gemini AI Integration
              </h2>
              <p style={{ margin: '2px 0 0', fontSize: '0.82rem', color: 'var(--text-muted)' }}>
                Configure your API key for automated OIML R 76 evaluation & report remarks
              </p>
            </div>
          </div>
          <button className="btn-icon" onClick={onClose} title="Close">
            <X size={20} />
          </button>
        </div>

        {/* Modal Content */}
        <div className="modal-body" style={{ padding: '24px' }}>
          {/* Key Input Section */}
          <div style={{ marginBottom: '20px' }}>
            <label
              style={{
                display: 'flex',
                alignItems: 'center',
                justifyContent: 'space-between',
                fontSize: '0.88rem',
                fontWeight: 600,
                color: 'var(--text-primary)',
                marginBottom: '8px',
              }}
            >
              <span style={{ display: 'flex', alignItems: 'center', gap: '6px' }}>
                <Key size={16} style={{ color: 'var(--color-primary)' }} />
                Gemma / Gemini API Key
              </span>
              <a
                href="https://aistudio.google.com/app/apikey"
                target="_blank"
                rel="noreferrer"
                style={{
                  fontSize: '0.8rem',
                  color: 'var(--color-primary)',
                  display: 'inline-flex',
                  alignItems: 'center',
                  gap: '4px',
                  textDecoration: 'none',
                }}
              >
                Get API key from Google AI Studio <ExternalLink size={12} />
              </a>
            </label>

            <div style={{ position: 'relative', display: 'flex', alignItems: 'center' }}>
              <input
                type={showKey ? 'text' : 'password'}
                value={apiKey}
                onChange={(e) => setApiKey(e.target.value)}
                placeholder="AIzaSy..."
                style={{
                  width: '100%',
                  padding: '10px 42px 10px 14px',
                  fontSize: '0.92rem',
                  fontFamily: 'monospace',
                  borderRadius: '8px',
                  border: '1px solid var(--border-color)',
                  backgroundColor: 'var(--bg-input, #ffffff)',
                  color: 'var(--text-primary)',
                }}
              />
              <button
                type="button"
                onClick={() => setShowKey(!showKey)}
                style={{
                  position: 'absolute',
                  right: '10px',
                  background: 'none',
                  border: 'none',
                  cursor: 'pointer',
                  color: 'var(--text-muted)',
                  padding: '4px',
                }}
                title={showKey ? 'Hide key' : 'Show key'}
              >
                {showKey ? <EyeOff size={18} /> : <Eye size={18} />}
              </button>
            </div>
            <p style={{ margin: '6px 0 0', fontSize: '0.78rem', color: 'var(--text-muted)' }}>
              Supports Google AI Studio keys for Gemma 4 (31B / 26B) and Gemini models.
            </p>
          </div>

          {/* Model Selection */}
          <div style={{ marginBottom: '22px' }}>
            <label
              style={{
                display: 'flex',
                alignItems: 'center',
                gap: '6px',
                fontSize: '0.88rem',
                fontWeight: 600,
                color: 'var(--text-primary)',
                marginBottom: '8px',
              }}
            >
              <Cpu size={16} style={{ color: 'var(--color-primary)' }} />
              Active AI Model
            </label>

            <div style={{ display: 'grid', gridTemplateColumns: '1fr', gap: '8px' }}>
              {AVAILABLE_MODELS.map((model) => {
                const isSelected = selectedModel === model.id;
                return (
                  <div
                    key={model.id}
                    onClick={() => setSelectedModel(model.id)}
                    style={{
                      display: 'flex',
                      alignItems: 'flex-start',
                      padding: '12px 14px',
                      borderRadius: '8px',
                      border: `1.5px solid ${isSelected ? 'var(--color-primary)' : 'var(--border-color)'}`,
                      backgroundColor: isSelected ? 'var(--bg-primary-soft, #eff6ff)' : 'var(--bg-surface, #ffffff)',
                      cursor: 'pointer',
                      transition: 'all 0.15s ease',
                    }}
                  >
                    <input
                      type="radio"
                      name="aiModel"
                      checked={isSelected}
                      onChange={() => setSelectedModel(model.id)}
                      style={{ marginTop: '3px', marginRight: '10px', cursor: 'pointer' }}
                    />
                    <div style={{ flex: 1 }}>
                      <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
                        <span style={{ fontWeight: 600, fontSize: '0.92rem', color: 'var(--text-primary)' }}>
                          {model.name}
                        </span>
                        {model.recommended && (
                          <span
                            style={{
                              fontSize: '0.7rem',
                              fontWeight: 700,
                              backgroundColor: '#10b981',
                              color: '#ffffff',
                              padding: '2px 6px',
                              borderRadius: '4px',
                              letterSpacing: '0.02em',
                            }}
                          >
                            RECOMMENDED
                          </span>
                        )}
                        <span
                          style={{
                            fontSize: '0.72rem',
                            padding: '2px 6px',
                            borderRadius: '4px',
                            backgroundColor: model.family === 'gemma' ? '#ede9fe' : '#e0f2fe',
                            color: model.family === 'gemma' ? '#6d28d9' : '#0369a1',
                            fontWeight: 600,
                          }}
                        >
                          {model.family === 'gemma' ? 'Gemma Open Weights' : 'Gemini Cloud'}
                        </span>
                      </div>
                      <p style={{ margin: '3px 0 0', fontSize: '0.8rem', color: 'var(--text-muted)' }}>
                        {model.description}
                      </p>
                    </div>
                  </div>
                );
              })}
            </div>
          </div>

          {/* Test Connection Button & Result */}
          <div style={{ marginBottom: '20px' }}>
            <div style={{ display: 'flex', gap: '10px' }}>
              <button
                type="button"
                className="btn-secondary"
                onClick={handleTestConnection}
                disabled={testing || !apiKey.trim()}
                style={{
                  display: 'inline-flex',
                  alignItems: 'center',
                  gap: '6px',
                  padding: '8px 14px',
                  fontSize: '0.86rem',
                }}
              >
                <RefreshCw size={15} className={testing ? 'spin-animation' : ''} />
                <span>{testing ? 'Testing Connection...' : 'Test API Key'}</span>
              </button>

              {apiKey.trim() && (
                <button
                  type="button"
                  className="btn-ghost"
                  onClick={handleClear}
                  style={{
                    display: 'inline-flex',
                    alignItems: 'center',
                    gap: '6px',
                    padding: '8px 12px',
                    fontSize: '0.86rem',
                    color: '#ef4444',
                  }}
                  title="Clear API key from this browser"
                >
                  <Trash2 size={15} />
                  <span>Remove Key</span>
                </button>
              )}
            </div>

            {testResult && (
              <div
                style={{
                  marginTop: '12px',
                  padding: '12px 14px',
                  borderRadius: '8px',
                  display: 'flex',
                  alignItems: 'flex-start',
                  gap: '10px',
                  backgroundColor: testResult.success ? '#ecfdf5' : '#fef2f2',
                  border: `1px solid ${testResult.success ? '#10b981' : '#f87171'}`,
                  color: testResult.success ? '#065f46' : '#991b1b',
                  fontSize: '0.85rem',
                }}
              >
                {testResult.success ? (
                  <CheckCircle2 size={18} style={{ color: '#10b981', flexShrink: 0, marginTop: '2px' }} />
                ) : (
                  <AlertTriangle size={18} style={{ color: '#ef4444', flexShrink: 0, marginTop: '2px' }} />
                )}
                <div>
                  <div style={{ fontWeight: 600 }}>
                    {testResult.success ? 'Gemma 4 Connected Successfully!' : 'Connection Failed'}
                  </div>
                  <div style={{ marginTop: '2px', wordBreak: 'break-word', opacity: 0.9 }}>
                    {testResult.message}
                  </div>
                </div>
              </div>
            )}
          </div>

          {/* Privacy & Security Guarantee */}
          <div
            style={{
              padding: '12px 14px',
              borderRadius: '8px',
              backgroundColor: 'var(--bg-card, #f8fafc)',
              border: '1px solid var(--border-color)',
              display: 'flex',
              gap: '10px',
              alignItems: 'flex-start',
              fontSize: '0.8rem',
              color: 'var(--text-muted)',
            }}
          >
            <ShieldCheck size={18} style={{ color: '#10b981', flexShrink: 0, marginTop: '1px' }} />
            <div>
              <strong style={{ color: 'var(--text-primary)' }}>Client-Side Privacy Guarantee:</strong> Your
              API key is securely stored in this browser&apos;s local storage and used directly for Google Generative AI
              metrological analysis. It is never logged or transmitted to any server.
            </div>
          </div>
        </div>

        {/* Modal Footer */}
        <div
          className="modal-footer"
          style={{
            padding: '16px 24px',
            borderTop: '1px solid var(--border-color)',
            display: 'flex',
            justifyContent: 'space-between',
            alignItems: 'center',
          }}
        >
          <div style={{ fontSize: '0.82rem', color: saveSuccess ? '#10b981' : 'var(--text-muted)' }}>
            {saveSuccess ? '✓ Settings saved successfully!' : 'Changes will take effect immediately'}
          </div>
          <div style={{ display: 'flex', gap: '10px' }}>
            <button className="btn-secondary" onClick={onClose}>
              Cancel
            </button>
            <button className="btn-primary" onClick={handleSave} style={{ display: 'inline-flex', alignItems: 'center', gap: '6px' }}>
              <Sparkles size={16} />
              <span>Save AI Settings</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  );
};

```

---

### File 19: `src/components/Dashboard.tsx`
*Path: `src/components/Dashboard.tsx` | Size: 17290 bytes | Repository Hub, KPI Cards & Accuracy Class Filters*

```tsx
import React, { useState } from 'react';
import type { OIMLTestReport } from '../types/oiml';
import { exportReportToPDF } from '../utils/pdfExport';
import { exportReportToDocx } from '../utils/docxExport';
import {
  Search,
  CheckCircle,
  XCircle,
  Clock,
  AlertTriangle,
  Copy,
  Trash2,
  Eye,
  FileDown,
  FileText,
  Scale,
  Key,
  Sparkles,
} from 'lucide-react';

interface DashboardProps {
  reports: OIMLTestReport[];
  onSelectReport: (report: OIMLTestReport) => void;
  onNewReport: () => void;
  onDeleteReport: (id: string) => void;
  onDuplicateReport: (report: OIMLTestReport) => void;
  onOpenAISettings?: () => void;
  hasApiKey?: boolean;
}

export const Dashboard: React.FC<DashboardProps> = ({
  reports,
  onSelectReport,
  onNewReport,
  onDeleteReport,
  onDuplicateReport,
  onOpenAISettings,
  hasApiKey = false,
}) => {
  const [searchTerm, setSearchTerm] = useState('');
  const [classFilter, setClassFilter] = useState<string>('ALL');
  const [statusFilter, setStatusFilter] = useState<string>('ALL');

  // Metrics
  const total = reports.length;
  const approvedCount = reports.filter((r) => r.status === 'approved' && r.overallVerdict === 'COMPLIANT').length;
  const pendingCount = reports.filter((r) => r.status === 'pending_approval' || r.status === 'under_evaluation').length;
  const rejectedCount = reports.filter((r) => r.status === 'rejected' || r.overallVerdict === 'NON_COMPLIANT').length;
  const complianceRate = total > 0 ? Math.round((approvedCount / total) * 100) : 0;

  // Filtered reports
  const filteredReports = reports.filter((r) => {
    const q = searchTerm.toLowerCase();
    const matchesSearch =
      r.instrument.reportNumber.toLowerCase().includes(q) ||
      r.instrument.model.toLowerCase().includes(q) ||
      r.instrument.manufacturer.toLowerCase().includes(q) ||
      r.instrument.serialNumber.toLowerCase().includes(q) ||
      r.instrument.applicant.toLowerCase().includes(q);

    const matchesClass = classFilter === 'ALL' || r.instrument.accuracyClass === classFilter;
    const matchesStatus = statusFilter === 'ALL' || r.status === statusFilter;

    return matchesSearch && matchesClass && matchesStatus;
  });

  return (
    <div className="dashboard-wrapper">
      {/* KPI Cards Row */}
      <div className="kpi-grid">
        <div className="kpi-card">
          <div className="kpi-icon-wrapper kpi-primary">
            <Scale size={24} />
          </div>
          <div className="kpi-content">
            <span className="kpi-label">Total Type Evaluations</span>
            <span className="kpi-value">{total}</span>
            <span className="kpi-sub">Registered NAWI instruments</span>
          </div>
        </div>

        <div className="kpi-card">
          <div className="kpi-icon-wrapper kpi-success">
            <CheckCircle size={24} />
          </div>
          <div className="kpi-content">
            <span className="kpi-label">Pattern Approval Rate</span>
            <span className="kpi-value">{complianceRate}%</span>
            <span className="kpi-sub">{approvedCount} approved certified</span>
          </div>
        </div>

        <div className="kpi-card">
          <div className="kpi-icon-wrapper kpi-warning">
            <Clock size={24} />
          </div>
          <div className="kpi-content">
            <span className="kpi-label">In-Progress / Pending</span>
            <span className="kpi-value">{pendingCount}</span>
            <span className="kpi-sub">Awaiting laboratory sign-off</span>
          </div>
        </div>

        <div className="kpi-card">
          <div className="kpi-icon-wrapper kpi-danger">
            <AlertTriangle size={24} />
          </div>
          <div className="kpi-content">
            <span className="kpi-label">Non-Compliant / Rejected</span>
            <span className="kpi-value">{rejectedCount}</span>
            <span className="kpi-sub">MPE or corner spread exceeded</span>
          </div>
        </div>
      </div>

      {/* Class distribution indicators */}
      <div className="class-breakdown-bar">
        <span className="class-bar-title">Accuracy Class Portfolio:</span>
        <div className="class-pill-group">
          {(['I', 'II', 'III', 'IIII'] as const).map((cls) => {
            const count = reports.filter((r) => r.instrument.accuracyClass === cls).length;
            return (
              <button
                key={cls}
                className={`class-filter-pill ${classFilter === cls ? 'active' : ''}`}
                onClick={() => setClassFilter(classFilter === cls ? 'ALL' : cls)}
              >
                <span>Class {cls}</span>
                <span className="pill-count">{count}</span>
              </button>
            );
          })}
        </div>
      </div>

      {/* Gemma 4 AI Key & Assistant Banner */}
      {onOpenAISettings && (
        <div
          style={{
            display: 'flex',
            justifyContent: 'space-between',
            alignItems: 'center',
            background: 'linear-gradient(135deg, #f8faff 0%, #eef2ff 100%)',
            border: '1px solid #c7d2fe',
            borderRadius: '12px',
            padding: '14px 20px',
            marginBottom: '20px',
            boxShadow: '0 2px 8px rgba(79, 70, 229, 0.05)',
          }}
        >
          <div style={{ display: 'flex', alignItems: 'center', gap: '14px' }}>
            <div style={{ background: '#4f46e5', padding: '10px', borderRadius: '10px', color: 'white', display: 'flex' }}>
              <Sparkles size={20} />
            </div>
            <div>
              <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
                <span style={{ fontWeight: 700, fontSize: '14px', color: '#1e1b4b' }}>
                  Gemma 4 AI Assistant & Vision OCR
                </span>
                <span
                  style={{
                    fontSize: '11px',
                    padding: '2px 8px',
                    borderRadius: '12px',
                    fontWeight: 600,
                    background: hasApiKey ? '#d1fae5' : '#fef3c7',
                    color: hasApiKey ? '#065f46' : '#92400e',
                  }}
                >
                  {hasApiKey ? '● Gemma 4 API Key Connected' : '○ No API Key Configured'}
                </span>
              </div>
              <p style={{ margin: '3px 0 0 0', fontSize: '12px', color: '#4338ca' }}>
                Enter your Gemma 4 or Google AI Studio key to enable automatic nameplate OCR, clause lookups, and test evaluations.
              </p>
            </div>
          </div>
          <button
            onClick={onOpenAISettings}
            style={{
              background: '#4f46e5',
              color: 'white',
              border: 'none',
              padding: '9px 18px',
              borderRadius: '8px',
              fontWeight: 600,
              fontSize: '13px',
              cursor: 'pointer',
              display: 'flex',
              alignItems: 'center',
              gap: '6px',
              boxShadow: '0 2px 6px rgba(79, 70, 229, 0.3)',
            }}
          >
            <Key size={15} />
            <span>{hasApiKey ? 'Configure Gemma 4 Key' : 'Enter Gemma 4 API Key'}</span>
          </button>
        </div>
      )}

      {/* Search and Filter Bar */}
      <div className="search-filter-panel">
        <div className="search-input-box">
          <Search size={18} className="search-icon" />
          <input
            type="text"
            placeholder="Search by Report Number, Manufacturer, Model, Serial No, or Applicant..."
            value={searchTerm}
            onChange={(e) => setSearchTerm(e.target.value)}
            className="search-input"
          />
          {searchTerm && (
            <button className="search-clear" onClick={() => setSearchTerm('')}>
              ✕
            </button>
          )}
        </div>

        <div className="filter-dropdowns">
          <div className="filter-group">
            <label>Status:</label>
            <select
              value={statusFilter}
              onChange={(e) => setStatusFilter(e.target.value)}
              className="filter-select"
            >
              <option value="ALL">All Statuses</option>
              <option value="approved">Approved</option>
              <option value="pending_approval">Pending Approval</option>
              <option value="under_evaluation">Under Evaluation</option>
              <option value="rejected">Rejected</option>
              <option value="draft">Draft</option>
            </select>
          </div>

          <div className="filter-group">
            <label>Accuracy Class:</label>
            <select
              value={classFilter}
              onChange={(e) => setClassFilter(e.target.value)}
              className="filter-select"
            >
              <option value="ALL">All Classes</option>
              <option value="I">Class I (Special)</option>
              <option value="II">Class II (High)</option>
              <option value="III">Class III (Medium)</option>
              <option value="IIII">Class IIII (Ordinary)</option>
            </select>
          </div>

          {onOpenAISettings && (
            <button
              onClick={onOpenAISettings}
              style={{
                display: 'flex',
                alignItems: 'center',
                gap: '6px',
                background: hasApiKey ? '#ecfdf5' : '#eff6ff',
                color: hasApiKey ? '#065f46' : '#1e40af',
                border: `1px solid ${hasApiKey ? '#a7f3d0' : '#bfdbfe'}`,
                fontWeight: 600,
                padding: '8px 14px',
                borderRadius: '6px',
                cursor: 'pointer',
                fontSize: '13px',
                whiteSpace: 'nowrap',
              }}
            >
              <Key size={14} style={{ color: hasApiKey ? '#10b981' : '#3b82f6' }} />
              <span>{hasApiKey ? 'Gemma 4 Key' : 'API Key'}</span>
            </button>
          )}

          <button className="btn btn-primary" onClick={onNewReport}>
            + New Evaluation
          </button>
        </div>
      </div>

      {/* Reports Table */}
      <div className="reports-table-card">
        <div className="table-header-info">
          <h4>Test Reports & Type Evaluations Repository</h4>
          <span className="results-count">
            Showing {filteredReports.length} of {total} records
          </span>
        </div>

        {filteredReports.length === 0 ? (
          <div className="empty-state">
            <Scale size={48} className="empty-icon" />
            <h5>No test reports match your search criteria</h5>
            <p>Try clearing your search query or adjusting the class/status filters.</p>
            <button
              className="btn btn-secondary"
              onClick={() => {
                setSearchTerm('');
                setClassFilter('ALL');
                setStatusFilter('ALL');
              }}
            >
              Reset Filters
            </button>
          </div>
        ) : (
          <div className="table-responsive">
            <table className="data-table">
              <thead>
                <tr>
                  <th>Report No / Date</th>
                  <th>Instrument & Model</th>
                  <th>Class / Capacity</th>
                  <th>Scale Interval</th>
                  <th>Test Lab</th>
                  <th>Conformance</th>
                  <th>Status</th>
                  <th style={{ textAlign: 'center' }}>Actions</th>
                </tr>
              </thead>
              <tbody>
                {filteredReports.map((report) => {
                  const isCompliant = report.overallVerdict === 'COMPLIANT';
                  return (
                    <tr key={report.id} className="report-row">
                      {/* Report Number & Date */}
                      <td>
                        <div className="report-id-cell">
                          <strong className="report-number-text">{report.instrument.reportNumber}</strong>
                          <span className="report-date-text">{report.environment.testDate}</span>
                        </div>
                      </td>

                      {/* Manufacturer & Model */}
                      <td>
                        <div className="inst-meta-cell">
                          <span className="inst-model">{report.instrument.model}</span>
                          <span className="inst-mfg">{report.instrument.manufacturer}</span>
                          <span className="inst-sn">S/N: {report.instrument.serialNumber}</span>
                        </div>
                      </td>

                      {/* Accuracy Class & Max */}
                      <td>
                        <div className="class-cap-cell">
                          <span className={`class-badge class-${report.instrument.accuracyClass}`}>
                            Class {report.instrument.accuracyClass}
                          </span>
                          <span className="cap-text">
                            Max: {report.instrument.maxCapacity} {report.instrument.unit}
                          </span>
                        </div>
                      </td>

                      {/* Scale Interval & n */}
                      <td>
                        <div className="interval-cell">
                          <span>e = {report.instrument.verificationScaleInterval} {report.instrument.unit}</span>
                          <span className="n-count">n = {report.instrument.scaleIntervalCount.toLocaleString()}</span>
                        </div>
                      </td>

                      {/* Lab Location */}
                      <td>
                        <div className="lab-cell" title={report.environment.laboratoryName}>
                          <span className="lab-name">{report.environment.laboratoryName}</span>
                          <span className="lab-nabl">{report.environment.nablAccreditationNo}</span>
                        </div>
                      </td>

                      {/* Verdict */}
                      <td>
                        <span className={`badge ${isCompliant ? 'badge-pass' : 'badge-fail'}`}>
                          {isCompliant ? <CheckCircle size={13} /> : <XCircle size={13} />}
                          <span>{report.overallVerdict}</span>
                        </span>
                      </td>

                      {/* Status */}
                      <td>
                        <span className={`status-pill status-${report.status}`}>
                          {report.status.replace('_', ' ').toUpperCase()}
                        </span>
                      </td>

                      {/* Actions */}
                      <td>
                        <div className="action-buttons-group">
                          <button
                            className="btn-action btn-edit"
                            onClick={() => onSelectReport(report)}
                            title="Open in Test Workbench"
                          >
                            <Eye size={16} />
                            <span>Inspect</span>
                          </button>

                          <button
                            className="btn-action"
                            onClick={() => exportReportToPDF(report)}
                            title="Generate Official OIML R 76-2 PDF Report"
                          >
                            <FileDown size={15} />
                            <span>PDF</span>
                          </button>

                          <button
                            className="btn-action"
                            onClick={() => exportReportToDocx(report)}
                            title="Generate Word (.docx) Editable Report"
                          >
                            <FileText size={15} />
                            <span>Word</span>
                          </button>

                          <button
                            className="btn-action"
                            onClick={() => onDuplicateReport(report)}
                            title="Duplicate as new evaluation"
                          >
                            <Copy size={15} />
                          </button>

                          <button
                            className="btn-action btn-danger-action"
                            onClick={() => {
                              if (window.confirm(`Delete report ${report.instrument.reportNumber}?`)) {
                                onDeleteReport(report.id);
                              }
                            }}
                            title="Delete Report"
                          >
                            <Trash2 size={15} />
                          </button>
                        </div>
                      </td>
                    </tr>
                  );
                })}
              </tbody>
            </table>
          </div>
        )}
      </div>
    </div>
  );
};

```

---

### File 20: `src/components/DocumentationModal.tsx`
*Path: `src/components/DocumentationModal.tsx` | Size: 15812 bytes | OIML R 76-1 Reference Handbook & Formulas*

```tsx
import React, { useState } from 'react';
import { X, BookOpen, Calculator, ShieldCheck, Scale, Cpu, CheckCircle2 } from 'lucide-react';

interface DocumentationModalProps {
  isOpen: boolean;
  onClose: () => void;
}

export const DocumentationModal: React.FC<DocumentationModalProps> = ({ isOpen, onClose }) => {
  const [activeTab, setActiveTab] = useState<'overview' | 'formulas' | 'classes' | 'procedures' | 'architecture'>('overview');

  if (!isOpen) return null;

  return (
    <div className="modal-backdrop">
      <div className="doc-modal-container">
        <div className="doc-modal-header">
          <div className="doc-modal-title-area">
            <BookOpen className="header-icon" size={24} />
            <div>
              <h3>OIML R 76 & Legal Metrology Technical Documentation</h3>
              <p>Type Evaluation Methodology, Mathematical Formulations & Regulatory Framework</p>
            </div>
          </div>
          <button className="btn-close" onClick={onClose} aria-label="Close Documentation">
            <X size={20} />
          </button>
        </div>

        {/* Tab Navigation */}
        <div className="doc-nav-tabs">
          <button
            className={`doc-nav-btn ${activeTab === 'overview' ? 'active' : ''}`}
            onClick={() => setActiveTab('overview')}
          >
            <ShieldCheck size={16} /> Regulatory Context
          </button>
          <button
            className={`doc-nav-btn ${activeTab === 'formulas' ? 'active' : ''}`}
            onClick={() => setActiveTab('formulas')}
          >
            <Calculator size={16} /> Metrological Formulas
          </button>
          <button
            className={`doc-nav-btn ${activeTab === 'classes' ? 'active' : ''}`}
            onClick={() => setActiveTab('classes')}
          >
            <Scale size={16} /> Accuracy Classes & MPE
          </button>
          <button
            className={`doc-nav-btn ${activeTab === 'procedures' ? 'active' : ''}`}
            onClick={() => setActiveTab('procedures')}
          >
            <CheckCircle2 size={16} /> Test Procedures (R 76-1)
          </button>
          <button
            className={`doc-nav-btn ${activeTab === 'architecture' ? 'active' : ''}`}
            onClick={() => setActiveTab('architecture')}
          >
            <Cpu size={16} /> Software Architecture
          </button>
        </div>

        {/* Modal Body */}
        <div className="doc-modal-body">
          {activeTab === 'overview' && (
            <div className="doc-section">
              <h4>1. Statutory & Metrological Mandate</h4>
              <p>
                In India, under the <strong>Legal Metrology Act, 2009</strong> and the <strong>Legal Metrology (General) Rules, 2011</strong> (read with the Seventh Schedule), any Non-Automatic Weighing Instrument (NAWI) intended for commercial transactions, health/safety, or legal verification must undergo rigorous <strong>Model Approval (Type Evaluation)</strong>.
              </p>
              <div className="info-callout">
                <strong>OIML International Alignment:</strong> India is a full member state of the International Organization of Legal Metrology (OIML) and an OIML Issuing Authority under the OIML-CS (Certification System). The national technical standards for NAWIs are harmonized with <strong>OIML Recommendation R 76-1:2006</strong> (Technical & Metrological Requirements) and <strong>OIML R 76-2:2007</strong> (Pattern Evaluation Test Report Format).
              </div>

              <h4>Key Metrological Definitions (OIML R 76-1 Clause 2)</h4>
              <ul className="doc-list">
                <li>
                  <strong>Non-Automatic Weighing Instrument (NAWI):</strong> An instrument that requires the intervention of an operator during the weighing process (e.g. to deposit or remove loads or obtain indications).
                </li>
                <li>
                  <strong>Verification Scale Interval (e):</strong> Value, expressed in units of mass, used for the classification and verification of an instrument.
                </li>
                <li>
                  <strong>Actual Scale Interval (d):</strong> Value, expressed in units of mass, of the difference between the values corresponding to two consecutive scale marks or digital indications (d ≤ e).
                </li>
                <li>
                  <strong>Number of Verification Scale Intervals (n):</strong> Quotient of the maximum capacity and the verification scale interval: n = Max / e.
                </li>
                <li>
                  <strong>Maximum Permissible Error (MPE):</strong> Maximum difference, legally permitted by specifications, between the indication of an instrument and the corresponding true value as determined by reference standard weights.
                </li>
              </ul>
            </div>
          )}

          {activeTab === 'formulas' && (
            <div className="doc-section">
              <h4>2. Mathematical Calculations & Metrological Formulations</h4>

              <div className="formula-card">
                <span className="formula-badge">Annex A.4.4.3</span>
                <h5>True Indication before Rounding (Turning Points Method)</h5>
                <p>
                  Digital instruments round values to the nearest scale interval. To determine the true indication before rounding (P), small fractional weights ΔL (typically 0.1e) are added until the displayed indication unambiguously switches to I + e:
                </p>
                <div className="equation-box">
                  <code>P = I + 0.5e - ΔL</code>
                </div>
                <small>Where I is displayed indication, e is verification interval, and ΔL is additional fractional load applied.</small>
              </div>

              <div className="formula-card">
                <span className="formula-badge">Annex A.4.4.3</span>
                <h5>Intrinsic Error (E) and Corrected Error (Ec)</h5>
                <p>
                  The intrinsic error before rounding is calculated against the applied standard load (L):
                </p>
                <div className="equation-box">
                  <code>E = P - L = I + 0.5e - ΔL - L</code>
                </div>
                <p>
                  To eliminate initial zero tare or residual zero drift, the corrected error (Ec) is computed by subtracting the error determined at zero load (E0):
                </p>
                <div className="equation-box highlight-equation">
                  <code>Ec = E - E0</code>
                </div>
              </div>

              <div className="formula-card">
                <span className="formula-badge">Clause 3.5.1</span>
                <h5>Permissible Error Boundary Evaluation</h5>
                <p>An instrument complies with the weighing performance requirements if, at every tested load:</p>
                <div className="equation-box">
                  <code>|Ec| ≤ MPE(L, e, Class)</code>
                </div>
              </div>

              <div className="formula-card">
                <span className="formula-badge">Clause 3.6.1</span>
                <h5>Repeatability Evaluation</h5>
                <p>For series of weighings at approx. 50% Max and 100% Max, the maximum difference between any two runs:</p>
                <div className="equation-box">
                  <code>ΔI = I_max - I_min ≤ |MPE|</code>
                </div>
              </div>
            </div>
          )}

          {activeTab === 'classes' && (
            <div className="doc-section">
              <h4>3. Accuracy Classes & Maximum Permissible Error (Table 6)</h4>
              <p>OIML R 76-1 categorizes non-automatic weighing instruments into four accuracy classes:</p>

              <table className="doc-table">
                <thead>
                  <tr>
                    <th>Class</th>
                    <th>Classification</th>
                    <th>Verification Interval (e)</th>
                    <th>Min Capacity (Min)</th>
                    <th>Interval Count Range (n)</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>Class I</strong></td>
                    <td>Special Accuracy</td>
                    <td>e ≥ 0.001 g</td>
                    <td>100e</td>
                    <td>n ≥ 50,000 (no upper limit)</td>
                  </tr>
                  <tr>
                    <td><strong>Class II</strong></td>
                    <td>High Accuracy</td>
                    <td>0.001 g ≤ e ≤ 0.05 g or e ≥ 0.1 g</td>
                    <td>20e or 50e</td>
                    <td>100 ≤ n ≤ 100,000</td>
                  </tr>
                  <tr>
                    <td><strong>Class III</strong></td>
                    <td>Medium Accuracy</td>
                    <td>0.1 g ≤ e ≤ 2 g or e ≥ 5 g</td>
                    <td>20e</td>
                    <td>500 ≤ n ≤ 10,000</td>
                  </tr>
                  <tr>
                    <td><strong>Class IIII</strong></td>
                    <td>Ordinary Accuracy</td>
                    <td>e ≥ 5 g</td>
                    <td>10e</td>
                    <td>100 ≤ n ≤ 1,000</td>
                  </tr>
                </tbody>
              </table>

              <h4>OIML Table 6: Maximum Permissible Errors on Initial Verification</h4>
              <table className="doc-table">
                <thead>
                  <tr>
                    <th>MPE Limit</th>
                    <th>Class I</th>
                    <th>Class II</th>
                    <th>Class III</th>
                    <th>Class IIII</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>± 0.5 e</strong></td>
                    <td>0 ≤ m ≤ 50,000 e</td>
                    <td>0 ≤ m ≤ 5,000 e</td>
                    <td>0 ≤ m ≤ 500 e</td>
                    <td>0 ≤ m ≤ 50 e</td>
                  </tr>
                  <tr>
                    <td><strong>± 1.0 e</strong></td>
                    <td>50,000 e &lt; m ≤ 200,000 e</td>
                    <td>5,000 e &lt; m ≤ 20,000 e</td>
                    <td>500 e &lt; m ≤ 2,000 e</td>
                    <td>50 e &lt; m ≤ 200 e</td>
                  </tr>
                  <tr>
                    <td><strong>± 1.5 e</strong></td>
                    <td>m &gt; 200,000 e</td>
                    <td>20,000 e &lt; m ≤ 100,000 e</td>
                    <td>2,000 e &lt; m ≤ 10,000 e</td>
                    <td>200 e &lt; m ≤ 1,000 e</td>
                  </tr>
                </tbody>
              </table>
              <small>Note: For in-service verification, MPE is doubled as per Clause 3.5.2.</small>
            </div>
          )}

          {activeTab === 'procedures' && (
            <div className="doc-section">
              <h4>4. Mandatory Type Evaluation Test Procedures (OIML R 76-1)</h4>
              <div className="proc-grid">
                <div className="proc-card">
                  <h6>1. Weighing Performance Test (Annex A.4.4)</h6>
                  <p>
                    Loads applied in increasing order from zero/Min up to Max capacity in at least 5 to 10 increments, including change-of-MPE thresholds (500e, 2000e), followed by unloading in reverse order. Hysteresis between loading and unloading at same load must remain within |MPE|.
                  </p>
                </div>
                <div className="proc-card">
                  <h6>2. Repeatability Test (Clause 3.6.1 & Annex A.4.10)</h6>
                  <p>
                    Identical test loads applied 3 to 10 consecutive times at approx. 50% Max and 100% Max. The spread between maximum and minimum indication must not exceed |MPE| for that load.
                  </p>
                </div>
                <div className="proc-card">
                  <h6>3. Eccentricity / Corner Loading (Clause 3.6.2 & Annex A.4.7)</h6>
                  <p>
                    A test load equal to approx. 1/3 Max is placed sequentially on the center and four peripheral quadrants/corners (or support sections for weighbridges). Each corner error and the maximum spread between any two locations must not exceed MPE.
                  </p>
                </div>
                <div className="proc-card">
                  <h6>4. Discrimination Test (Clause 3.8 & Annex A.4.8)</h6>
                  <p>
                    Performed at Min, 0.5 Max, and Max. With instrument at rest, gently depositing an extra load equal to 1.4d must cause an unequivocal change of display indication of at least 1d.
                  </p>
                </div>
                <div className="proc-card">
                  <h6>5. Zero-Setting & Zero-Tracking (Clause 4.5 & Annex A.4.2)</h6>
                  <p>
                    Zero-setting error E0 must not exceed ± 0.25e. The zero-tracking speed must be controlled such that it does not exceed 0.5d per second.
                  </p>
                </div>
                <div className="proc-card">
                  <h6>6. Tare Mechanism Evaluation (Clause 4.6)</h6>
                  <p>
                    Verification that the tare balancing device error is within ± 0.25e, and net weighing conforms to the MPE table for the applied net load.
                  </p>
                </div>
              </div>
            </div>
          )}

          {activeTab === 'architecture' && (
            <div className="doc-section">
              <h4>5. Software Architecture & Deployment Framework</h4>
              <p>
                The OIML R 76 Test Report Generator is engineered as a zero-latency, high-reliability web and desktop application adhering to statutory Legal Metrology requirements:
              </p>
              <ul className="doc-list">
                <li>
                  <strong>Frontend Core:</strong> React 19 + TypeScript with strict typings for metrological models, scale classes, and test procedures.
                </li>
                <li>
                  <strong>Styling:</strong> Vanilla CSS Design System with high-contrast neutral surfaces, deep navy/teal legal metrology brand accents, and accessible semantic status indicators.
                </li>
                <li>
                  <strong>Metrology Calculation Engine:</strong> Pure mathematical engine decoupled from UI, running client-side floating-point safe arithmetic with full unit testing capability.
                </li>
                <li>
                  <strong>Report Export Engines:</strong> Native client-side PDF synthesis with <code>jspdf</code> / <code>jspdf-autotable</code> and editable Word documents with <code>docx</code>.
                </li>
                <li>
                  <strong>Tamper-Evident Hash:</strong> Cryptographic token generated from critical report payload to guarantee immutability and authenticity during inter-agency verification.
                </li>
                <li>
                  <strong>Persistence & Portability:</strong> Local storage / IndexedDB repository with complete JSON database export and import capability for air-gapped calibration vans and regional laboratories.
                </li>
              </ul>
            </div>
          )}
        </div>

        <div className="doc-modal-footer">
          <button className="btn btn-primary" onClick={onClose}>
            Got it, Return to Workspace
          </button>
        </div>
      </div>
    </div>
  );
};

```

---

### File 21: `src/components/EccentricityDiagram.tsx`
*Path: `src/components/EccentricityDiagram.tsx` | Size: 8224 bytes | Platform Eccentricity Visual Receptor with Corner Nodes*

```tsx
import React, { useState } from 'react';
import type { EccentricityTestResult, EccentricityPoint } from '../types/oiml';

interface EccentricityDiagramProps {
  test: EccentricityTestResult;
  unit: string;
}

export const EccentricityDiagram: React.FC<EccentricityDiagramProps> = ({ test, unit }) => {
  const [selectedPoint, setSelectedPoint] = useState<EccentricityPoint | null>(
    test.points[0] || null
  );

  const isRectangular = test.receptorType === 'rectangular_4_corners';
  const isRound = test.receptorType === 'round_4_points';
  const isWeighbridge = test.receptorType === 'weighbridge_sections';

  return (
    <div className="eccentricity-card">
      <div className="ecc-header">
        <div>
          <h4 className="card-title">Load Receptor Schematic & Eccentricity Layout</h4>
          <p className="card-subtitle">
            OIML R 76-1 Clause 3.6.2 & Annex A.4.7 | Test Load: {test.testLoad} {unit} (~ 1/3 Max)
          </p>
        </div>
        <div className="ecc-summary-badge">
          <span className={`badge ${test.passed ? 'badge-pass' : 'badge-fail'}`}>
            {test.passed ? 'PASS: CORNER SPREAD COMPLIANT' : 'FAIL: ECCENTRICITY EXCEEDED'}
          </span>
          <span className="ecc-stat">
            Max Spread: <strong>{test.maxSpread} {unit}</strong> (Limit: ±{test.maxMpe} {unit})
          </span>
        </div>
      </div>

      <div className="ecc-body-grid">
        {/* Visual Receptor Canvas */}
        <div className="receptor-visual-wrapper">
          {isRectangular && (
            <div className="platform-receptor rect-platform">
              <div className="platform-border">
                {/* 4 Corners and Center */}
                {test.points.map((pt) => {
                  let posClass = 'pos-center';
                  if (pt.positionKey === 'corner_1') posClass = 'pos-front-left';
                  if (pt.positionKey === 'corner_2') posClass = 'pos-back-left';
                  if (pt.positionKey === 'corner_3') posClass = 'pos-back-right';
                  if (pt.positionKey === 'corner_4') posClass = 'pos-front-right';

                  const isSel = selectedPoint?.positionKey === pt.positionKey;

                  return (
                    <button
                      key={pt.positionKey}
                      className={`corner-node ${posClass} ${pt.passed ? 'node-pass' : 'node-fail'} ${
                        isSel ? 'node-selected' : ''
                      }`}
                      onClick={() => setSelectedPoint(pt)}
                      title={`${pt.positionLabel}: Ec = ${pt.correctedError} ${unit}`}
                    >
                      <span className="node-icon">{pt.passed ? '✓' : '✕'}</span>
                      <span className="node-name">{pt.positionKey.replace('_', ' ')}</span>
                      <span className="node-ec">{pt.correctedError >= 0 ? '+' : ''}{pt.correctedError} {unit}</span>
                    </button>
                  );
                })}
              </div>
            </div>
          )}

          {isRound && (
            <div className="platform-receptor round-platform">
              <div className="round-pan">
                {test.points.map((pt) => {
                  let posClass = 'pos-center';
                  if (pt.positionKey === 'corner_1') posClass = 'pos-round-front';
                  if (pt.positionKey === 'corner_2') posClass = 'pos-round-left';
                  if (pt.positionKey === 'corner_3') posClass = 'pos-round-back';
                  if (pt.positionKey === 'corner_4') posClass = 'pos-round-right';

                  const isSel = selectedPoint?.positionKey === pt.positionKey;

                  return (
                    <button
                      key={pt.positionKey}
                      className={`corner-node ${posClass} ${pt.passed ? 'node-pass' : 'node-fail'} ${
                        isSel ? 'node-selected' : ''
                      }`}
                      onClick={() => setSelectedPoint(pt)}
                    >
                      <span className="node-icon">{pt.passed ? '✓' : '✕'}</span>
                      <span className="node-name">{pt.positionLabel}</span>
                      <span className="node-ec">{pt.correctedError >= 0 ? '+' : ''}{pt.correctedError} {unit}</span>
                    </button>
                  );
                })}
              </div>
            </div>
          )}

          {isWeighbridge && (
            <div className="platform-receptor weighbridge-platform">
              <div className="weighbridge-deck">
                {test.points.map((pt) => {
                  const isSel = selectedPoint?.positionKey === pt.positionKey;
                  return (
                    <button
                      key={pt.positionKey}
                      className={`weighbridge-section-node ${pt.passed ? 'node-pass' : 'node-fail'} ${
                        isSel ? 'node-selected' : ''
                      }`}
                      onClick={() => setSelectedPoint(pt)}
                    >
                      <div className="sec-header">
                        <span className="sec-title">{pt.positionLabel}</span>
                        <span className="node-icon">{pt.passed ? '✓' : '✕'}</span>
                      </div>
                      <div className="sec-val">Ec: {pt.correctedError >= 0 ? '+' : ''}{pt.correctedError} {unit}</div>
                      <div className="sec-sub">MPE: ±{pt.mpe} {unit}</div>
                    </button>
                  );
                })}
              </div>
            </div>
          )}
        </div>

        {/* Selected Position Detail Card */}
        <div className="ecc-details-panel">
          {selectedPoint ? (
            <div className="ecc-detail-card">
              <div className="detail-card-head">
                <h5>{selectedPoint.positionLabel}</h5>
                <span className={`badge ${selectedPoint.passed ? 'badge-pass' : 'badge-fail'}`}>
                  {selectedPoint.passed ? 'COMPLIANT' : 'EXCEEDED'}
                </span>
              </div>
              <div className="detail-grid">
                <div className="detail-row">
                  <span>Applied Test Load:</span>
                  <strong>{test.testLoad} {unit}</strong>
                </div>
                <div className="detail-row">
                  <span>Instrument Indication (I):</span>
                  <strong>{selectedPoint.indication} {unit}</strong>
                </div>
                <div className="detail-row">
                  <span>Turning Point Load (ΔL):</span>
                  <strong>{selectedPoint.deltaL} {unit}</strong>
                </div>
                <div className="detail-row">
                  <span>True Indication (P):</span>
                  <strong>{selectedPoint.trueIndication} {unit}</strong>
                </div>
                <div className="detail-row">
                  <span>Calculated Error (E):</span>
                  <strong>{selectedPoint.error >= 0 ? '+' : ''}{selectedPoint.error} {unit}</strong>
                </div>
                <div className="detail-row highlight-row">
                  <span>Corrected Error (Ec):</span>
                  <strong className={selectedPoint.passed ? 'text-success' : 'text-danger'}>
                    {selectedPoint.correctedError >= 0 ? '+' : ''}{selectedPoint.correctedError} {unit}
                  </strong>
                </div>
                <div className="detail-row">
                  <span>Permissible MPE:</span>
                  <strong>±{selectedPoint.mpe} {unit}</strong>
                </div>
              </div>
              <div className="detail-clause-note">
                <small>
                  Clause 3.6.2.1: The errors on the indicated load at any position shall not exceed the maximum permissible error for that load.
                </small>
              </div>
            </div>
          ) : (
            <div className="ecc-hint">Click on any corner or section node on the left diagram to view metrological analysis.</div>
          )}
        </div>
      </div>
    </div>
  );
};

```

---

### File 22: `src/components/InteractiveErrorCurve.tsx`
*Path: `src/components/InteractiveErrorCurve.tsx` | Size: 11245 bytes | Interactive SVG Error Curve with MPE Corridor*

```tsx
import React, { useState } from 'react';
import type { WeighingTestRow } from '../types/oiml';

interface InteractiveErrorCurveProps {
  rows: WeighingTestRow[];
  e: number;
  unit: string;
  maxCapacity: number;
  zeroErrorE0: number;
}

export const InteractiveErrorCurve: React.FC<InteractiveErrorCurveProps> = ({
  rows,
  e,
  unit,
  maxCapacity,
  zeroErrorE0,
}) => {
  const [hoveredPoint, setHoveredPoint] = useState<WeighingTestRow | null>(null);

  if (rows.length === 0) {
    return (
      <div className="error-curve-empty">
        <p>No weighing test points recorded yet. Enter test observations to view the real-time metrological error curve.</p>
      </div>
    );
  }

  // Sort increasing rows by load for plotting
  const incRows = [...rows.filter((r) => r.direction === 'increasing')].sort((a, b) => a.nominalLoad - b.nominalLoad);
  const decRows = [...rows.filter((r) => r.direction === 'decreasing')].sort((a, b) => a.nominalLoad - b.nominalLoad);

  // SVG dimensions
  const width = 760;
  const height = 320;
  const padding = { top: 30, right: 40, bottom: 45, left: 65 };
  const plotWidth = width - padding.left - padding.right;
  const plotHeight = height - padding.top - padding.bottom;

  // Max X is maxCapacity or max load in rows
  const maxLoad = Math.max(maxCapacity, ...rows.map((r) => r.nominalLoad), 1);

  // Find max absolute error and MPE for Y scale
  const allYValues = rows.flatMap((r) => [r.correctedError, r.mpe, -r.mpe]);
  const maxY = Math.max(...allYValues.map((v) => Math.abs(v)), e * 2, 0.001);
  const yDomain = maxY * 1.25; // 25% margin

  // Coordinate mappers
  const mapX = (load: number) => padding.left + (load / maxLoad) * plotWidth;
  const mapY = (val: number) => padding.top + (plotHeight / 2) - (val / yDomain) * (plotHeight / 2);

  // Generate MPE envelope corridor path
  const mpeStepPoints: { load: number; mpe: number }[] = [];
  const sortedLoads = Array.from(new Set([0, ...rows.map((r) => r.nominalLoad), maxCapacity])).sort((a, b) => a - b);

  sortedLoads.forEach((load) => {
    const matchingRow = rows.find((r) => r.nominalLoad === load);
    const mpeVal = matchingRow ? matchingRow.mpe : rows[0]?.mpe || e;
    mpeStepPoints.push({ load, mpe: mpeVal });
  });

  const upperMpePath = mpeStepPoints
    .map((pt, i) => `${i === 0 ? 'M' : 'L'} ${mapX(pt.load)} ${mapY(pt.mpe)}`)
    .join(' ');

  const lowerMpePath = mpeStepPoints
    .map((pt, i) => `${i === 0 ? 'M' : 'L'} ${mapX(pt.load)} ${mapY(-pt.mpe)}`)
    .join(' ');

  // Shaded corridor polygon
  const corridorPolygon =
    upperMpePath +
    ' ' +
    [...mpeStepPoints]
      .reverse()
      .map((pt) => `L ${mapX(pt.load)} ${mapY(-pt.mpe)}`)
      .join(' ') +
    ' Z';

  // Increasing curve line
  const incCurvePath = incRows
    .map((r, i) => `${i === 0 ? 'M' : 'L'} ${mapX(r.nominalLoad)} ${mapY(r.correctedError)}`)
    .join(' ');

  // Decreasing curve line
  const decCurvePath = decRows
    .map((r, i) => `${i === 0 ? 'M' : 'L'} ${mapX(r.nominalLoad)} ${mapY(r.correctedError)}`)
    .join(' ');

  // Y Axis ticks
  const yTicks = [
    yDomain,
    yDomain / 2,
    0,
    -yDomain / 2,
    -yDomain,
  ];

  // X Axis ticks
  const xTicks = [
    0,
    maxLoad * 0.25,
    maxLoad * 0.5,
    maxLoad * 0.75,
    maxLoad,
  ];

  return (
    <div className="error-curve-card">
      <div className="error-curve-header">
        <div>
          <h4 className="card-title">Metrological Error Curve: Ec vs Load</h4>
          <p className="card-subtitle">
            OIML R 76-1 Annex A.4.4.3 | Zero Correction E0 = {zeroErrorE0} {unit} | Shaded zone represents the Permissible Corridor [-MPE, +MPE]
          </p>
        </div>
        <div className="curve-legend">
          <span className="legend-item">
            <span className="legend-swatch corridor-swatch"></span> MPE Corridor (±)
          </span>
          <span className="legend-item">
            <span className="legend-swatch inc-swatch"></span> Loading (▲)
          </span>
          <span className="legend-item">
            <span className="legend-swatch dec-swatch"></span> Unloading (▼)
          </span>
        </div>
      </div>

      <div className="svg-container">
        <svg viewBox={`0 0 ${width} ${height}`} className="error-curve-svg">
          <defs>
            <linearGradient id="mpeCorridorGradient" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stopColor="#10b981" stopOpacity="0.18" />
              <stop offset="50%" stopColor="#10b981" stopOpacity="0.08" />
              <stop offset="100%" stopColor="#10b981" stopOpacity="0.18" />
            </linearGradient>
          </defs>

          {/* Grid lines */}
          {yTicks.map((tickVal, i) => (
            <g key={`y-grid-${i}`}>
              <line
                x1={padding.left}
                y1={mapY(tickVal)}
                x2={width - padding.right}
                y2={mapY(tickVal)}
                stroke="#e2e8f0"
                strokeDasharray={tickVal === 0 ? '0' : '3,3'}
                strokeWidth={tickVal === 0 ? 1.5 : 1}
              />
              <text
                x={padding.left - 8}
                y={mapY(tickVal) + 4}
                textAnchor="end"
                className="axis-tick-text"
              >
                {tickVal >= 0 ? `+${tickVal.toFixed(3)}` : tickVal.toFixed(3)}
              </text>
            </g>
          ))}

          {/* X Axis ticks */}
          {xTicks.map((xVal, i) => (
            <g key={`x-grid-${i}`}>
              <line
                x1={mapX(xVal)}
                y1={padding.top}
                x2={mapX(xVal)}
                y2={height - padding.bottom}
                stroke="#e2e8f0"
                strokeDasharray="3,3"
                strokeWidth={1}
              />
              <text
                x={mapX(xVal)}
                y={height - padding.bottom + 18}
                textAnchor="middle"
                className="axis-tick-text"
              >
                {xVal.toLocaleString()} {unit}
              </text>
            </g>
          ))}

          {/* Zero Reference Line */}
          <line
            x1={padding.left}
            y1={mapY(0)}
            x2={width - padding.right}
            y2={mapY(0)}
            stroke="#64748b"
            strokeWidth={1.5}
          />

          {/* MPE Corridor Shading */}
          <path d={corridorPolygon} fill="url(#mpeCorridorGradient)" />

          {/* MPE Boundary Lines */}
          <path d={upperMpePath} fill="none" stroke="#059669" strokeWidth={1.5} strokeDasharray="4,2" />
          <path d={lowerMpePath} fill="none" stroke="#059669" strokeWidth={1.5} strokeDasharray="4,2" />

          {/* Loading Curve (Increasing) */}
          {incCurvePath && (
            <path
              d={incCurvePath}
              fill="none"
              stroke="#0284c7"
              strokeWidth={2.5}
              strokeLinecap="round"
              strokeLinejoin="round"
            />
          )}

          {/* Unloading Curve (Decreasing) */}
          {decCurvePath && (
            <path
              d={decCurvePath}
              fill="none"
              stroke="#8b5cf6"
              strokeWidth={2}
              strokeDasharray="4,3"
              strokeLinecap="round"
              strokeLinejoin="round"
            />
          )}

          {/* Data Points */}
          {rows.map((row, idx) => {
            const cx = mapX(row.nominalLoad);
            const cy = mapY(row.correctedError);
            const isHovered = hoveredPoint === row;
            const isPass = row.passed;
            const isInc = row.direction === 'increasing';

            return (
              <g
                key={`point-${idx}`}
                className="curve-point-group"
                onMouseEnter={() => setHoveredPoint(row)}
                onMouseLeave={() => setHoveredPoint(null)}
              >
                <circle
                  cx={cx}
                  cy={cy}
                  r={isHovered ? 7 : 4.5}
                  fill={isPass ? (isInc ? '#0284c7' : '#8b5cf6') : '#dc2626'}
                  stroke="#ffffff"
                  strokeWidth={2}
                  className="curve-point"
                />
                {!isPass && (
                  <circle
                    cx={cx}
                    cy={cy}
                    r={9}
                    fill="none"
                    stroke="#dc2626"
                    strokeWidth={1.5}
                    strokeDasharray="2,2"
                  />
                )}
              </g>
            );
          })}

          {/* Axis Titles */}
          <text
            x={width / 2}
            y={height - 8}
            textAnchor="middle"
            className="axis-title"
          >
            Nominal Load L ({unit})
          </text>
          <text
            x={-height / 2}
            y={16}
            transform="rotate(-90)"
            textAnchor="middle"
            className="axis-title"
          >
            Corrected Error Ec ({unit})
          </text>
        </svg>
      </div>

      {/* Tooltip Box */}
      {hoveredPoint ? (
        <div className="curve-tooltip-box">
          <div className="tooltip-header">
            <span className={`badge ${hoveredPoint.passed ? 'badge-pass' : 'badge-fail'}`}>
              {hoveredPoint.passed ? 'PASS' : 'FAIL'}
            </span>
            <span className="tooltip-step">
              Step #{hoveredPoint.step} ({hoveredPoint.direction === 'increasing' ? 'Increasing ▲' : 'Decreasing ▼'})
            </span>
          </div>
          <div className="tooltip-metrics">
            <div>
              <span className="t-label">Nominal Load (L):</span>
              <strong className="t-val">{hoveredPoint.nominalLoad} {unit}</strong>
            </div>
            <div>
              <span className="t-label">Indication (I):</span>
              <strong className="t-val">{hoveredPoint.indication} {unit}</strong>
            </div>
            <div>
              <span className="t-label">Turning P (ΔL={hoveredPoint.deltaL}):</span>
              <strong className="t-val">{hoveredPoint.trueIndication} {unit}</strong>
            </div>
            <div>
              <span className="t-label">Intrinsic Error (E):</span>
              <strong className="t-val">{hoveredPoint.error >= 0 ? '+' : ''}{hoveredPoint.error} {unit}</strong>
            </div>
            <div>
              <span className="t-label">Corrected Error (Ec):</span>
              <strong className={`t-val ${hoveredPoint.passed ? 'text-success' : 'text-danger'}`}>
                {hoveredPoint.correctedError >= 0 ? '+' : ''}{hoveredPoint.correctedError} {unit}
              </strong>
            </div>
            <div>
              <span className="t-label">Permissible MPE:</span>
              <strong className="t-val">±{hoveredPoint.mpe} {unit}</strong>
            </div>
          </div>
        </div>
      ) : (
        <div className="curve-hint">
          <span>💡 Hover over any test node to inspect turning point ΔL, true indication P, and MPE compliance.</span>
        </div>
      )}
    </div>
  );
};

```

---

### File 23: `src/components/Navbar.tsx`
*Path: `src/components/Navbar.tsx` | Size: 6025 bytes | Header with Indian Emblem, Role Switcher & AI Status*

```tsx
import React from 'react';
import type { UserProfile } from '../types/oiml';
import {
  Scale,
  PlusCircle,
  LayoutDashboard,
  BookOpen,
  UserCheck,
  Download,
  Upload,
  Sparkles,
  Key,
} from 'lucide-react';

interface NavbarProps {
  currentView: 'dashboard' | 'editor';
  onNavigate: (view: 'dashboard' | 'editor') => void;
  onNewReport: () => void;
  onOpenDocu: () => void;
  onOpenAISettings: () => void;
  onToggleAICopilot: () => void;
  hasApiKey: boolean;
  activeUser: UserProfile;
  availableUsers: UserProfile[];
  onSwitchUser: (user: UserProfile) => void;
  onExportDatabase: () => void;
  onImportDatabase: (event: React.ChangeEvent<HTMLInputElement>) => void;
  totalReportsCount: number;
}

export const Navbar: React.FC<NavbarProps> = ({
  currentView,
  onNavigate,
  onNewReport,
  onOpenDocu,
  onOpenAISettings,
  onToggleAICopilot,
  hasApiKey,
  activeUser,
  availableUsers,
  onSwitchUser,
  onExportDatabase,
  onImportDatabase,
  totalReportsCount,
}) => {
  return (
    <header className="navbar-wrapper">
      {/* Tricolor India accent strip */}
      <div className="tricolor-strip">
        <span className="strip-saffron"></span>
        <span className="strip-white"></span>
        <span className="strip-green"></span>
      </div>

      <div className="navbar-container">
        {/* Brand & Department identity */}
        <div className="navbar-brand-section" onClick={() => onNavigate('dashboard')} style={{ cursor: 'pointer' }}>
          <div className="brand-logo-box">
            <Scale size={24} className="brand-icon" />
          </div>
          <div className="brand-text-box">
            <div className="brand-title-row">
              <span className="brand-ministry">Ministry of Consumer Affairs, Food & Public Distribution</span>
              <span className="brand-badge-oiml">OIML R 76-2</span>
            </div>
            <h1 className="brand-app-name">
              NAWI Test Report Generator & Repository
            </h1>
            <span className="brand-sub">Directorate of Legal Metrology | Type Evaluation System</span>
          </div>
        </div>

        {/* Central Navigation buttons */}
        <div className="navbar-actions-section">
          <button
            className={`nav-action-btn ${currentView === 'dashboard' ? 'active' : ''}`}
            onClick={() => onNavigate('dashboard')}
          >
            <LayoutDashboard size={17} />
            <span>Dashboard ({totalReportsCount})</span>
          </button>

          <button className="nav-action-btn btn-new-report" onClick={onNewReport}>
            <PlusCircle size={17} />
            <span>New Evaluation</span>
          </button>

          <button className="nav-action-btn" onClick={onOpenDocu}>
            <BookOpen size={17} />
            <span>OIML Handbook</span>
          </button>

          <button
            className="nav-action-btn btn-ai-action"
            onClick={onToggleAICopilot}
            title="Open OIML Metrology AI Copilot"
            style={{
              background: 'linear-gradient(135deg, rgba(79, 70, 229, 0.1) 0%, rgba(124, 58, 237, 0.1) 100%)',
              border: '1px solid rgba(124, 58, 237, 0.3)',
              color: '#6d28d9',
              fontWeight: 600,
            }}
          >
            <Sparkles size={16} style={{ color: '#7c3aed' }} />
            <span>AI Copilot</span>
          </button>

          <button
            className="nav-action-btn btn-ghost"
            onClick={onOpenAISettings}
            title={hasApiKey ? 'Gemma 4 API Key Active (Click to configure)' : 'Gemma 4 API Key Missing (Click to enter)'}
            style={{ display: 'inline-flex', alignItems: 'center', gap: '6px' }}
          >
            <Key size={15} style={{ color: hasApiKey ? '#10b981' : '#f59e0b' }} />
            <span>AI Key</span>
            <span
              style={{
                width: '7px',
                height: '7px',
                borderRadius: '50%',
                backgroundColor: hasApiKey ? '#10b981' : '#f59e0b',
                display: 'inline-block',
              }}
            />
          </button>

          <button className="nav-action-btn btn-ghost" onClick={onExportDatabase} title="Backup All Reports as JSON">
            <Download size={16} />
            <span>Backup</span>
          </button>

          <label className="nav-action-btn btn-ghost file-upload-label" title="Restore Reports from JSON">
            <Upload size={16} />
            <span>Restore</span>
            <input type="file" accept=".json" onChange={onImportDatabase} style={{ display: 'none' }} />
          </label>
        </div>

        {/* User Role Switcher */}
        <div className="navbar-user-section">
          <div className="user-profile-badge">
            <div className="user-avatar">
              <UserCheck size={18} />
            </div>
            <div className="user-info-text">
              <div className="user-name-role">
                <span className="user-name">{activeUser.name}</span>
                <span className={`role-pill role-${activeUser.role}`}>
                  {activeUser.role.replace('_', ' ').toUpperCase()}
                </span>
              </div>
              <span className="user-designation">{activeUser.designation}</span>
            </div>

            {/* Profile Dropdown */}
            <select
              className="user-select-hidden"
              value={activeUser.id}
              onChange={(e) => {
                const selected = availableUsers.find((u) => u.id === e.target.value);
                if (selected) onSwitchUser(selected);
              }}
              title="Switch Evaluator Profile"
            >
              {availableUsers.map((u) => (
                <option key={u.id} value={u.id}>
                  {u.name} ({u.role.replace('_', ' ')})
                </option>
              ))}
            </select>
          </div>
        </div>
      </div>
    </header>
  );
};

```

---

### File 24: `src/components/ReportEditor.tsx`
*Path: `src/components/ReportEditor.tsx` | Size: 87438 bytes | 7-Tab Testing Workbench & OIML Evaluation Form*

```tsx
import React, { useState } from 'react';
import type {
  OIMLTestReport,
  UserProfile,
  AccuracyClass,
  VerificationType,
  ScaleUnit,
  WeighingTestRow,
} from '../types/oiml';
import {
  evaluateEntireReport,
  validateScaleIntervalCount,
  calculateMPE,
  roundMetrology,
} from '../utils/metrologyEngine';
import { exportReportToPDF } from '../utils/pdfExport';
import { exportReportToDocx } from '../utils/docxExport';
import { InteractiveErrorCurve } from './InteractiveErrorCurve';
import { EccentricityDiagram } from './EccentricityDiagram';
import {
  Save,
  ArrowLeft,
  FileDown,
  FileText,
  Printer,
  CheckCircle2,
  XCircle,
  AlertTriangle,
  Scale,
  Thermometer,
  Activity,
  RotateCcw,
  Compass,
  Sliders,
  Award,
  Plus,
  Trash2,
  Sparkles,
  Bot,
  AlertCircle,
  Check,
  Copy,
} from 'lucide-react';
import {
  generateEvaluatorRemarksWithGemma,
  diagnoseInstrumentFailureWithGemma,
  getStoredApiKey,
  getStoredModel,
  AVAILABLE_MODELS,
} from '../utils/aiService';

interface ReportEditorProps {
  report: OIMLTestReport;
  onSaveReport: (report: OIMLTestReport) => void;
  onBackToDashboard: () => void;
  activeUser: UserProfile;
  onOpenAISettings?: () => void;
}

export const ReportEditor: React.FC<ReportEditorProps> = ({
  report: initialReport,
  onSaveReport,
  onBackToDashboard,
  activeUser,
  onOpenAISettings,
}) => {
  const [report, setReport] = useState<OIMLTestReport>(initialReport);
  const [activeTab, setActiveTab] = useState<
    'specs' | 'env' | 'weighing' | 'repeatability' | 'eccentricity' | 'aux' | 'signoff'
  >('specs');
  const [saveToast, setSaveToast] = useState(false);

  // AI Assistant states
  const [aiLoading, setAiLoading] = useState(false);
  const [aiLoadingText, setAiLoadingText] = useState('');
  const [aiResult, setAiResult] = useState<{ type: 'remarks' | 'diagnostics'; text: string } | null>(null);
  const [aiError, setAiError] = useState<string | null>(null);
  const [aiCopied, setAiCopied] = useState(false);

  // Recalculates and updates local state
  const handleUpdate = (updatedReport: OIMLTestReport) => {
    const evaluated = evaluateEntireReport(updatedReport);
    setReport(evaluated);
  };

  const handleManualSave = () => {
    // Append audit log entry if updated
    const updated = {
      ...report,
      auditTrail: [
        ...report.auditTrail,
        {
          id: `aud-${Date.now()}`,
          timestamp: new Date().toISOString(),
          userName: activeUser.name,
          userRole: activeUser.role,
          action: 'UPDATED' as const,
          description: `Updated test observations from ${activeTab.toUpperCase()} section.`,
        },
      ],
    };
    const finalReport = evaluateEntireReport(updated);
    setReport(finalReport);
    onSaveReport(finalReport);
    setSaveToast(true);
    setTimeout(() => setSaveToast(false), 2500);
  };

  // Helper for instrument spec changes
  const updateInstrument = (fields: Partial<typeof report.instrument>) => {
    const updatedInst = { ...report.instrument, ...fields };
    // Auto update n
    if (updatedInst.verificationScaleInterval > 0) {
      updatedInst.scaleIntervalCount = Math.round(
        updatedInst.maxCapacity / updatedInst.verificationScaleInterval
      );
    }
    // Auto update minCapacity (20e for class III/II, 100e for class I, 10e for class IIII)
    if (fields.accuracyClass || fields.verificationScaleInterval) {
      let minMultiplier = 20;
      if (updatedInst.accuracyClass === 'I') minMultiplier = 100;
      if (updatedInst.accuracyClass === 'IIII') minMultiplier = 10;
      updatedInst.minCapacity = roundMetrology(minMultiplier * updatedInst.verificationScaleInterval, 6);
    }

    handleUpdate({
      ...report,
      instrument: updatedInst,
    });
  };

  // Helper for environmental conditions
  const updateEnv = (fields: Partial<typeof report.environment>) => {
    handleUpdate({
      ...report,
      environment: { ...report.environment, ...fields },
    });
  };

  // Validation of n
  const intervalValidation = validateScaleIntervalCount(
    report.instrument.accuracyClass,
    report.instrument.verificationScaleInterval,
    report.instrument.scaleIntervalCount
  );

  // Quick auto-populate standard load steps
  const autoPopulateStandardWeighingSteps = () => {
    const { maxCapacity, verificationScaleInterval: e, accuracyClass, verificationType } = report.instrument;
    const min = report.instrument.minCapacity;
    const stepLoads = Array.from(
      new Set([
        min,
        roundMetrology(500 * e, 4),
        roundMetrology(1000 * e, 4),
        roundMetrology(2000 * e, 4),
        roundMetrology(0.5 * maxCapacity, 4),
        roundMetrology(0.75 * maxCapacity, 4),
        maxCapacity,
      ])
    )
      .filter((l) => l <= maxCapacity && l >= min)
      .sort((a, b) => a - b);

    let stepNum = 1;
    const newRows: WeighingTestRow[] = [];

    // Increasing runs
    stepLoads.forEach((load) => {
      newRows.push({
        step: stepNum++,
        direction: 'increasing',
        nominalLoad: load,
        indication: load,
        deltaL: roundMetrology(0.5 * e, 6),
        trueIndication: load,
        error: 0,
        correctedError: 0,
        mpe: calculateMPE(load, e, accuracyClass, verificationType),
        passed: true,
      });
    });

    // Decreasing runs
    [...stepLoads].reverse().forEach((load) => {
      newRows.push({
        step: stepNum++,
        direction: 'decreasing',
        nominalLoad: load,
        indication: load,
        deltaL: roundMetrology(0.5 * e, 6),
        trueIndication: load,
        error: 0,
        correctedError: 0,
        mpe: calculateMPE(load, e, accuracyClass, verificationType),
        passed: true,
      });
    });

    handleUpdate({
      ...report,
      weighingTest: {
        ...report.weighingTest,
        rows: newRows,
      },
    });
  };

  return (
    <div className="report-editor-wrapper">
      {/* Top Action Header */}
      <div className="editor-top-bar">
        <div className="top-bar-left">
          <button className="btn btn-secondary btn-icon-text" onClick={onBackToDashboard}>
            <ArrowLeft size={16} />
            <span>Dashboard</span>
          </button>

          <div className="report-title-meta">
            <div className="rep-number-badge">
              <span className="rep-num">{report.instrument.reportNumber}</span>
              <span className={`status-pill status-${report.status}`}>
                {report.status.replace('_', ' ').toUpperCase()}
              </span>
            </div>
            <span className="rep-desc">
              {report.instrument.manufacturer} — {report.instrument.model} (Class {report.instrument.accuracyClass})
            </span>
          </div>
        </div>

        <div className="top-bar-right">
          {/* Verdict indicator */}
          <div className={`verdict-pill ${report.overallVerdict === 'COMPLIANT' ? 'verdict-pass' : 'verdict-fail'}`}>
            {report.overallVerdict === 'COMPLIANT' ? (
              <>
                <CheckCircle2 size={16} />
                <span>OIML R 76-1 COMPLIANT</span>
              </>
            ) : (
              <>
                <XCircle size={16} />
                <span>NON-COMPLIANT</span>
              </>
            )}
          </div>

          <button className="btn btn-secondary" onClick={() => exportReportToPDF(report)} title="Generate PDF">
            <FileDown size={16} />
            <span>PDF</span>
          </button>

          <button className="btn btn-secondary" onClick={() => exportReportToDocx(report)} title="Generate Word (.docx)">
            <FileText size={16} />
            <span>Word</span>
          </button>

          <button className="btn btn-secondary" onClick={() => window.print()} title="Print Preview">
            <Printer size={16} />
          </button>

          <button className="btn btn-primary" onClick={handleManualSave}>
            <Save size={16} />
            <span>Save Test Data</span>
          </button>
        </div>
      </div>

      {saveToast && (
        <div className="save-toast-banner">
          <CheckCircle2 size={16} />
          <span>Test observations and metrological evaluations saved successfully!</span>
        </div>
      )}

      {/* 7 Master Tabs */}
      <div className="editor-tabs-bar">
        <button
          className={`tab-btn ${activeTab === 'specs' ? 'active' : ''}`}
          onClick={() => setActiveTab('specs')}
        >
          <Scale size={16} />
          <span>1. Specifications</span>
          {!intervalValidation.valid && <AlertTriangle size={14} className="tab-warn-icon" />}
        </button>

        <button
          className={`tab-btn ${activeTab === 'env' ? 'active' : ''}`}
          onClick={() => setActiveTab('env')}
        >
          <Thermometer size={16} />
          <span>2. Environmental & Lab</span>
        </button>

        <button
          className={`tab-btn ${activeTab === 'weighing' ? 'active' : ''}`}
          onClick={() => setActiveTab('weighing')}
        >
          <Activity size={16} />
          <span>3. Weighing Test</span>
          <span className={`tab-indicator ${report.weighingTest.passed ? 'tab-pass' : 'tab-fail'}`}>
            {report.weighingTest.passed ? 'PASS' : 'FAIL'}
          </span>
        </button>

        <button
          className={`tab-btn ${activeTab === 'repeatability' ? 'active' : ''}`}
          onClick={() => setActiveTab('repeatability')}
        >
          <RotateCcw size={16} />
          <span>4. Repeatability</span>
          <span className={`tab-indicator ${report.repeatabilityTest.passed ? 'tab-pass' : 'tab-fail'}`}>
            {report.repeatabilityTest.passed ? 'PASS' : 'FAIL'}
          </span>
        </button>

        <button
          className={`tab-btn ${activeTab === 'eccentricity' ? 'active' : ''}`}
          onClick={() => setActiveTab('eccentricity')}
        >
          <Compass size={16} />
          <span>5. Corner Eccentricity</span>
          <span className={`tab-indicator ${report.eccentricityTest.passed ? 'tab-pass' : 'tab-fail'}`}>
            {report.eccentricityTest.passed ? 'PASS' : 'FAIL'}
          </span>
        </button>

        <button
          className={`tab-btn ${activeTab === 'aux' ? 'active' : ''}`}
          onClick={() => setActiveTab('aux')}
        >
          <Sliders size={16} />
          <span>6. Discrimination & Aux</span>
          <span className={`tab-indicator ${report.discriminationTest.passed ? 'tab-pass' : 'tab-fail'}`}>
            {report.discriminationTest.passed ? 'PASS' : 'FAIL'}
          </span>
        </button>

        <button
          className={`tab-btn ${activeTab === 'signoff' ? 'active' : ''}`}
          onClick={() => setActiveTab('signoff')}
        >
          <Award size={16} />
          <span>7. Sign-off & Certificate</span>
        </button>
      </div>

      {/* Tab Content Panes */}
      <div className="editor-pane-body">
        {/* ================= TAB 1: SPECIFICATIONS ================= */}
        {activeTab === 'specs' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Instrument Identification & Metrological Specifications</h3>
                <p>OIML R 76-1:2006 Clause 2 & Table 3 Scale Classification Parameters</p>
              </div>
            </div>

            {/* Validation Banner if n is out of range */}
            {!intervalValidation.valid && (
              <div className="alert-box alert-danger">
                <AlertTriangle size={20} />
                <div>
                  <strong>OIML R 76-1 Table 3 Violation:</strong> {intervalValidation.reason}
                </div>
              </div>
            )}

            <div className="form-card">
              <h4 className="form-section-title">A. Identification & Application Details</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Report Number (OIML R 76-2):</label>
                  <input
                    type="text"
                    value={report.instrument.reportNumber}
                    onChange={(e) => updateInstrument({ reportNumber: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Model Approval Application Ref:</label>
                  <input
                    type="text"
                    value={report.instrument.applicationNumber}
                    onChange={(e) => updateInstrument({ applicationNumber: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Manufacturer Name:</label>
                  <input
                    type="text"
                    value={report.instrument.manufacturer}
                    onChange={(e) => updateInstrument({ manufacturer: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Applicant / Submitter:</label>
                  <input
                    type="text"
                    value={report.instrument.applicant}
                    onChange={(e) => updateInstrument({ applicant: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Instrument Model / Type Designation:</label>
                  <input
                    type="text"
                    value={report.instrument.model}
                    onChange={(e) => updateInstrument({ model: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Serial Number:</label>
                  <input
                    type="text"
                    value={report.instrument.serialNumber}
                    onChange={(e) => updateInstrument({ serialNumber: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Year of Manufacture:</label>
                  <input
                    type="number"
                    value={report.instrument.yearOfManufacture}
                    onChange={(e) => updateInstrument({ yearOfManufacture: parseInt(e.target.value) || 2026 })}
                  />
                </div>

                <div className="form-field">
                  <label>Device Category:</label>
                  <select
                    value={report.instrument.deviceType}
                    onChange={(e) => updateInstrument({ deviceType: e.target.value as any })}
                  >
                    <option value="Counter Scale">Counter Scale (Retail/Commercial)</option>
                    <option value="Bench Scale">Bench Scale</option>
                    <option value="Platform Scale">Platform Scale</option>
                    <option value="Weighbridge">Heavy Weighbridge (Road/Rail)</option>
                    <option value="Precision Balance">Precision Balance</option>
                    <option value="Crane Scale">Crane Scale</option>
                    <option value="Hopper Scale">Hopper Scale</option>
                    <option value="Axle Weigher">Axle Weigher</option>
                  </select>
                </div>

                <div className="form-field">
                  <label>Evaluation Verification Stage:</label>
                  <select
                    value={report.instrument.verificationType}
                    onChange={(e) => updateInstrument({ verificationType: e.target.value as VerificationType })}
                  >
                    <option value="initial">Initial Verification (Pattern Approval)</option>
                    <option value="subsequent">Subsequent Verification</option>
                    <option value="in_service">In-Service Inspection (2x MPE)</option>
                  </select>
                </div>
              </div>
            </div>

            <div className="form-card">
              <h4 className="form-section-title">B. Metrological Parameters & Scale Intervals</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Accuracy Class (OIML R 76-1):</label>
                  <select
                    value={report.instrument.accuracyClass}
                    onChange={(e) => updateInstrument({ accuracyClass: e.target.value as AccuracyClass })}
                  >
                    <option value="I">Class I (Special Accuracy)</option>
                    <option value="II">Class II (High Accuracy)</option>
                    <option value="III">Class III (Medium Accuracy)</option>
                    <option value="IIII">Class IIII (Ordinary Accuracy)</option>
                  </select>
                </div>

                <div className="form-field">
                  <label>Measurement Unit:</label>
                  <select
                    value={report.instrument.unit}
                    onChange={(e) => updateInstrument({ unit: e.target.value as ScaleUnit })}
                  >
                    <option value="kg">kg (Kilograms)</option>
                    <option value="g">g (Grams)</option>
                    <option value="t">t (Metric Tonnes)</option>
                    <option value="mg">mg (Milligrams)</option>
                  </select>
                </div>

                <div className="form-field">
                  <label>Maximum Capacity (Max):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.instrument.maxCapacity}
                    onChange={(e) => updateInstrument({ maxCapacity: parseFloat(e.target.value) || 0 })}
                  />
                </div>

                <div className="form-field">
                  <label>Verification Scale Interval (e):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.instrument.verificationScaleInterval}
                    onChange={(e) => updateInstrument({ verificationScaleInterval: parseFloat(e.target.value) || 0 })}
                  />
                </div>

                <div className="form-field">
                  <label>Actual Scale Interval (d):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.instrument.actualScaleInterval}
                    onChange={(e) => updateInstrument({ actualScaleInterval: parseFloat(e.target.value) || 0 })}
                  />
                </div>

                <div className="form-field">
                  <label>Minimum Capacity (Min):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.instrument.minCapacity}
                    onChange={(e) => updateInstrument({ minCapacity: parseFloat(e.target.value) || 0 })}
                  />
                  <small className="field-hint">Auto: {report.instrument.accuracyClass === 'I' ? '100e' : report.instrument.accuracyClass === 'IIII' ? '10e' : '20e'}</small>
                </div>

                <div className="form-field">
                  <label>Calculated Scale Intervals (n = Max / e):</label>
                  <div className="n-display-box">
                    <strong className="n-val">{report.instrument.scaleIntervalCount.toLocaleString()}</strong>
                    <span className={`n-status ${intervalValidation.valid ? 'text-success' : 'text-danger'}`}>
                      {intervalValidation.valid ? '✓ Compliant with Table 3' : '✕ Out of Table 3 Bounds'}
                    </span>
                  </div>
                  <small className="field-hint">Permissible: {intervalValidation.minN.toLocaleString()} ≤ n ≤ {intervalValidation.maxN.toLocaleString()}</small>
                </div>

                <div className="form-field">
                  <label>Tare Device Mechanism:</label>
                  <select
                    value={report.instrument.tareType}
                    onChange={(e) => updateInstrument({ tareType: e.target.value as any })}
                  >
                    <option value="subtractive">Subtractive Tare (T = -Max)</option>
                    <option value="additive">Additive Tare</option>
                    <option value="tare_balance">Tare Balancing</option>
                    <option value="preset_tare">Preset Tare</option>
                    <option value="none">No Tare</option>
                  </select>
                </div>

                <div className="form-field">
                  <label>Maximum Tare (T_max):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.instrument.maxTare}
                    onChange={(e) => updateInstrument({ maxTare: parseFloat(e.target.value) || 0 })}
                  />
                </div>
              </div>
            </div>

            <div className="form-card">
              <h4 className="form-section-title">C. Construction & Sensor Specifications</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Digital Indicator Terminal Model:</label>
                  <input
                    type="text"
                    value={report.instrument.indicatorModel}
                    onChange={(e) => updateInstrument({ indicatorModel: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Load Cell Transducer Model:</label>
                  <input
                    type="text"
                    value={report.instrument.loadCellModel}
                    onChange={(e) => updateInstrument({ loadCellModel: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Load Cell OIML R 60 Certificate No:</label>
                  <input
                    type="text"
                    value={report.instrument.loadCellCertificateNo}
                    onChange={(e) => updateInstrument({ loadCellCertificateNo: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Number of Load Cells (m):</label>
                  <input
                    type="number"
                    value={report.instrument.loadCellCount}
                    onChange={(e) => updateInstrument({ loadCellCount: parseInt(e.target.value) || 1 })}
                  />
                </div>

                <div className="form-field">
                  <label>Load Receptor Platform Dimensions:</label>
                  <input
                    type="text"
                    value={report.instrument.platformDimensions}
                    onChange={(e) => updateInstrument({ platformDimensions: e.target.value })}
                    placeholder="e.g. 500 mm x 500 mm or 18 m x 3 m"
                  />
                </div>

                <div className="form-field">
                  <label>Zero Setting Mechanism:</label>
                  <select
                    value={report.instrument.zeroSettingType}
                    onChange={(e) => updateInstrument({ zeroSettingType: e.target.value as any })}
                  >
                    <option value="semi_automatic">Semi-Automatic (Push Button)</option>
                    <option value="automatic">Automatic Zero-Setting</option>
                    <option value="initial_zero">Initial Zero-Setting</option>
                    <option value="zero_tracking">Zero-Tracking Device</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ================= TAB 2: ENVIRONMENTAL & LAB ================= */}
        {activeTab === 'env' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Testing Laboratory & Environmental Conditions</h3>
                <p>OIML R 76-1 Clause 3.9 & Annex A.5 Influence Factors Baseline</p>
              </div>
            </div>

            <div className="form-card">
              <h4 className="form-section-title">A. Testing Facility & Authority</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Testing Laboratory Name:</label>
                  <input
                    type="text"
                    value={report.environment.laboratoryName}
                    onChange={(e) => updateEnv({ laboratoryName: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Laboratory Postal Address:</label>
                  <input
                    type="text"
                    value={report.environment.laboratoryAddress}
                    onChange={(e) => updateEnv({ laboratoryAddress: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>NABL Accreditation Certificate No:</label>
                  <input
                    type="text"
                    value={report.environment.nablAccreditationNo}
                    onChange={(e) => updateEnv({ nablAccreditationNo: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>OIML Issuing Authority:</label>
                  <input
                    type="text"
                    value={report.environment.oimlIssuingAuthority}
                    onChange={(e) => updateEnv({ oimlIssuingAuthority: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Testing Bay / Chamber Location:</label>
                  <input
                    type="text"
                    value={report.environment.evaluationLocation}
                    onChange={(e) => updateEnv({ evaluationLocation: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Date of Evaluation:</label>
                  <input
                    type="date"
                    value={report.environment.testDate}
                    onChange={(e) => updateEnv({ testDate: e.target.value })}
                  />
                </div>
              </div>
            </div>

            <div className="form-card">
              <h4 className="form-section-title">B. Ambient Environmental Measurements</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Ambient Temperature at Start (°C):</label>
                  <input
                    type="number"
                    step="0.1"
                    value={report.environment.ambientTempStart}
                    onChange={(e) => updateEnv({ ambientTempStart: parseFloat(e.target.value) || 20 })}
                  />
                </div>

                <div className="form-field">
                  <label>Ambient Temperature at End (°C):</label>
                  <input
                    type="number"
                    step="0.1"
                    value={report.environment.ambientTempEnd}
                    onChange={(e) => updateEnv({ ambientTempEnd: parseFloat(e.target.value) || 20 })}
                  />
                </div>

                <div className="form-field">
                  <label>Relative Humidity (% RH):</label>
                  <input
                    type="number"
                    value={report.environment.relativeHumidity}
                    onChange={(e) => updateEnv({ relativeHumidity: parseInt(e.target.value) || 50 })}
                  />
                </div>

                <div className="form-field">
                  <label>Barometric Pressure (hPa):</label>
                  <input
                    type="number"
                    value={report.environment.barometricPressure}
                    onChange={(e) => updateEnv({ barometricPressure: parseInt(e.target.value) || 1013 })}
                  />
                </div>

                <div className="form-field">
                  <label>Mains Supply Voltage (V AC):</label>
                  <input
                    type="number"
                    value={report.environment.mainsVoltage}
                    onChange={(e) => updateEnv({ mainsVoltage: parseInt(e.target.value) || 230 })}
                  />
                </div>

                <div className="form-field">
                  <label>Mains Frequency (Hz):</label>
                  <input
                    type="number"
                    step="0.1"
                    value={report.environment.mainsFrequency}
                    onChange={(e) => updateEnv({ mainsFrequency: parseFloat(e.target.value) || 50.0 })}
                  />
                </div>

                <div className="form-field">
                  <label>Warm-up Time (minutes):</label>
                  <input
                    type="number"
                    value={report.environment.warmUpTimeMinutes}
                    onChange={(e) => updateEnv({ warmUpTimeMinutes: parseInt(e.target.value) || 30 })}
                  />
                </div>
              </div>
            </div>

            <div className="form-card">
              <h4 className="form-section-title">C. Calibration Standard Test Weights Used</h4>
              <div className="form-grid-3">
                <div className="form-field">
                  <label>Standard Weights Accuracy Class (OIML R 111):</label>
                  <select
                    value={report.environment.standardWeightsClass}
                    onChange={(e) => updateEnv({ standardWeightsClass: e.target.value as any })}
                  >
                    <option value="E1">Class E1 (Ultra-precision standards)</option>
                    <option value="E2">Class E2 (High accuracy laboratory)</option>
                    <option value="F1">Class F1 (High precision industrial)</option>
                    <option value="F2">Class F2 (Commercial & industrial verification)</option>
                    <option value="M1">Class M1 (Platform & weighbridge test blocks)</option>
                    <option value="M2">Class M2 (Heavy field verification)</option>
                  </select>
                </div>

                <div className="form-field">
                  <label>Weights Calibration Certificate No:</label>
                  <input
                    type="text"
                    value={report.environment.standardWeightsCertNo}
                    onChange={(e) => updateEnv({ standardWeightsCertNo: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Certificate Validity Date:</label>
                  <input
                    type="date"
                    value={report.environment.standardWeightsValidity}
                    onChange={(e) => updateEnv({ standardWeightsValidity: e.target.value })}
                  />
                </div>

                <div className="form-field">
                  <label>Expanded Measurement Uncertainty (U, k=2):</label>
                  <input
                    type="text"
                    value={report.environment.standardWeightsUncertainty}
                    onChange={(e) => updateEnv({ standardWeightsUncertainty: e.target.value })}
                    placeholder="e.g. U = 0.05 mg to 0.2 mg"
                  />
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ================= TAB 3: WEIGHING PERFORMANCE TEST ================= */}
        {activeTab === 'weighing' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Weighing Performance Test (Annex A.4.4 & Table 6)</h3>
                <p>Turning Point True Indication before Rounding: P = I + 0.5e - ΔL | Ec = E - E0</p>
              </div>

              <div className="pane-actions-group">
                <button
                  className="btn btn-secondary btn-icon-text"
                  onClick={autoPopulateStandardWeighingSteps}
                  title="Auto-fill standard test load steps"
                >
                  <Sparkles size={16} />
                  <span>Auto-Populate Standard Steps</span>
                </button>

                <button
                  className="btn btn-primary btn-icon-text"
                  onClick={() => {
                    const stepNum = report.weighingTest.rows.length + 1;
                    const e = report.instrument.verificationScaleInterval;
                    const newRow: WeighingTestRow = {
                      step: stepNum,
                      direction: 'increasing',
                      nominalLoad: report.instrument.minCapacity,
                      indication: report.instrument.minCapacity,
                      deltaL: roundMetrology(0.5 * e, 6),
                      trueIndication: report.instrument.minCapacity,
                      error: 0,
                      correctedError: 0,
                      mpe: calculateMPE(report.instrument.minCapacity, e, report.instrument.accuracyClass, report.instrument.verificationType),
                      passed: true,
                    };
                    handleUpdate({
                      ...report,
                      weighingTest: {
                        ...report.weighingTest,
                        rows: [...report.weighingTest.rows, newRow],
                      },
                    });
                  }}
                >
                  <Plus size={16} />
                  <span>Add Load Row</span>
                </button>
              </div>
            </div>

            {/* Zero Error Settings Card */}
            <div className="zero-settings-card">
              <div className="zero-card-title">
                <strong>Zero Error Determination (Clause 4.5.2 & A.4.2):</strong>
                <span>Maximum permissible zero error: ±{roundMetrology(0.25 * report.instrument.verificationScaleInterval, 6)} {report.instrument.unit} (0.25e)</span>
              </div>
              <div className="zero-fields-row">
                <div className="form-field inline-field">
                  <label>Zero Error at Start (E0):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.weighingTest.zeroErrorStart}
                    onChange={(e) => {
                      const val = parseFloat(e.target.value) || 0;
                      handleUpdate({
                        ...report,
                        weighingTest: { ...report.weighingTest, zeroErrorStart: val },
                      });
                    }}
                  />
                  <span>{report.instrument.unit}</span>
                </div>

                <div className="form-field inline-field">
                  <label>Zero Error at End (E0'):</label>
                  <input
                    type="number"
                    step="any"
                    value={report.weighingTest.zeroErrorEnd}
                    onChange={(e) => {
                      const val = parseFloat(e.target.value) || 0;
                      handleUpdate({
                        ...report,
                        weighingTest: { ...report.weighingTest, zeroErrorEnd: val },
                      });
                    }}
                  />
                  <span>{report.instrument.unit}</span>
                </div>

                <div className="zero-eval-badge">
                  <span className={`badge ${Math.abs(report.weighingTest.zeroErrorStart) <= 0.25 * report.instrument.verificationScaleInterval ? 'badge-pass' : 'badge-fail'}`}>
                    {Math.abs(report.weighingTest.zeroErrorStart) <= 0.25 * report.instrument.verificationScaleInterval ? '✓ E0 ≤ 0.25e' : '✕ E0 Exceeds 0.25e'}
                  </span>
                </div>
              </div>
            </div>

            {/* Live Metrological Error Curve Chart */}
            <InteractiveErrorCurve
              rows={report.weighingTest.rows}
              e={report.instrument.verificationScaleInterval}
              unit={report.instrument.unit}
              maxCapacity={report.instrument.maxCapacity}
              zeroErrorE0={report.weighingTest.zeroErrorStart}
            />

            {/* Weighing Test Table */}
            <div className="weighing-table-card">
              <div className="table-responsive">
                <table className="data-table">
                  <thead>
                    <tr>
                      <th style={{ width: 45 }}>#</th>
                      <th style={{ width: 110 }}>Direction</th>
                      <th>Nominal Load L ({report.instrument.unit})</th>
                      <th>Indication I ({report.instrument.unit})</th>
                      <th>Turning ΔL ({report.instrument.unit})</th>
                      <th>True P ({report.instrument.unit})</th>
                      <th>Intrinsic Err E</th>
                      <th>Corrected Ec</th>
                      <th>MPE (±)</th>
                      <th>Status</th>
                      <th style={{ width: 50 }}>Del</th>
                    </tr>
                  </thead>
                  <tbody>
                    {report.weighingTest.rows.map((row, idx) => (
                      <tr key={`row-${idx}`} className={row.passed ? '' : 'row-failed'}>
                        <td>{row.step}</td>
                        <td>
                          <select
                            value={row.direction}
                            onChange={(e) => {
                              const updatedRows = [...report.weighingTest.rows];
                              updatedRows[idx] = { ...row, direction: e.target.value as any };
                              handleUpdate({
                                ...report,
                                weighingTest: { ...report.weighingTest, rows: updatedRows },
                              });
                            }}
                            className="table-input-select"
                          >
                            <option value="increasing">▲ Increasing</option>
                            <option value="decreasing">▼ Decreasing</option>
                          </select>
                        </td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={row.nominalLoad}
                            onChange={(e) => {
                              const updatedRows = [...report.weighingTest.rows];
                              updatedRows[idx] = { ...row, nominalLoad: parseFloat(e.target.value) || 0 };
                              handleUpdate({
                                ...report,
                                weighingTest: { ...report.weighingTest, rows: updatedRows },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={row.indication}
                            onChange={(e) => {
                              const updatedRows = [...report.weighingTest.rows];
                              updatedRows[idx] = { ...row, indication: parseFloat(e.target.value) || 0 };
                              handleUpdate({
                                ...report,
                                weighingTest: { ...report.weighingTest, rows: updatedRows },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={row.deltaL}
                            onChange={(e) => {
                              const updatedRows = [...report.weighingTest.rows];
                              updatedRows[idx] = { ...row, deltaL: parseFloat(e.target.value) || 0 };
                              handleUpdate({
                                ...report,
                                weighingTest: { ...report.weighingTest, rows: updatedRows },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>
                          <span className="mono-cell">{row.trueIndication}</span>
                        </td>
                        <td>
                          <span className="mono-cell">{row.error >= 0 ? '+' : ''}{row.error}</span>
                        </td>
                        <td>
                          <strong className={`mono-cell ${row.passed ? 'text-success' : 'text-danger'}`}>
                            {row.correctedError >= 0 ? '+' : ''}{row.correctedError}
                          </strong>
                        </td>
                        <td>
                          <span className="mono-cell">±{row.mpe}</span>
                        </td>
                        <td>
                          <span className={`badge ${row.passed ? 'badge-pass' : 'badge-fail'}`}>
                            {row.passed ? 'PASS' : 'FAIL'}
                          </span>
                        </td>
                        <td>
                          <button
                            className="btn-trash-row"
                            onClick={() => {
                              const updatedRows = report.weighingTest.rows.filter((_, i) => i !== idx);
                              handleUpdate({
                                ...report,
                                weighingTest: { ...report.weighingTest, rows: updatedRows },
                              });
                            }}
                            title="Remove row"
                          >
                            <Trash2 size={14} />
                          </button>
                        </td>
                      </tr>
                    ))}
                  </tbody>
                </table>
              </div>

              {/* Weighing Test Summary Metrics */}
              <div className="weighing-summary-footer">
                <div className="footer-metric">
                  <span>Max Corrected Error |Ec|:</span>
                  <strong>{report.weighingTest.maxCorrectedError} {report.instrument.unit}</strong>
                </div>
                <div className="footer-metric">
                  <span>Max Error Ratio (|Ec| / MPE):</span>
                  <strong>{report.weighingTest.maxMpeRatio}</strong>
                </div>
                <div className="footer-metric">
                  <span>Max Hysteresis:</span>
                  <strong>{report.weighingTest.hysteresisMax} {report.instrument.unit}</strong>
                  <span className={`badge ${report.weighingTest.hysteresisPassed ? 'badge-pass' : 'badge-fail'}`}>
                    {report.weighingTest.hysteresisPassed ? 'Pass (≤ MPE)' : 'Fail'}
                  </span>
                </div>
                <div className="footer-metric">
                  <span>Weighing Test Verdict:</span>
                  <span className={`badge ${report.weighingTest.passed ? 'badge-pass' : 'badge-fail'}`}>
                    {report.weighingTest.passed ? 'COMPLIANT' : 'NON-COMPLIANT'}
                  </span>
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ================= TAB 4: REPEATABILITY ================= */}
        {activeTab === 'repeatability' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Repeatability Test (Clause 3.6.1 & Annex A.4.10)</h3>
                <p>Maximum difference between results of identical loads: ΔI = I_max - I_min ≤ |MPE|</p>
              </div>
              <span className={`badge ${report.repeatabilityTest.passed ? 'badge-pass' : 'badge-fail'}`}>
                {report.repeatabilityTest.passed ? 'REPEATABILITY PASSED' : 'REPEATABILITY FAILED'}
              </span>
            </div>

            <div className="rep-grid-two">
              {/* Series 1: ~ 50% Max */}
              <div className="form-card">
                <div className="rep-series-header">
                  <div>
                    <h5>Series 1: Half Maximum Capacity (~ 50% Max)</h5>
                    <p>Load: {report.repeatabilityTest.halfMaxLoad} {report.instrument.unit} | MPE: ±{report.repeatabilityTest.halfMaxMpe} {report.instrument.unit}</p>
                  </div>
                  <span className={`badge ${report.repeatabilityTest.halfMaxPassed ? 'badge-pass' : 'badge-fail'}`}>
                    {report.repeatabilityTest.halfMaxPassed ? 'PASS' : 'FAIL'}
                  </span>
                </div>

                <table className="data-table">
                  <thead>
                    <tr>
                      <th>Run #</th>
                      <th>Applied Load</th>
                      <th>Indication (I)</th>
                      <th>Turning ΔL</th>
                      <th>True P</th>
                    </tr>
                  </thead>
                  <tbody>
                    {report.repeatabilityTest.runsHalfMax.map((run, i) => (
                      <tr key={`half-run-${i}`}>
                        <td>Run {run.runIndex}</td>
                        <td>{run.load} {report.instrument.unit}</td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={run.indication}
                            onChange={(e) => {
                              const updatedRuns = [...report.repeatabilityTest.runsHalfMax];
                              const newInd = parseFloat(e.target.value) || 0;
                              updatedRuns[i] = { ...run, indication: newInd };
                              handleUpdate({
                                ...report,
                                repeatabilityTest: { ...report.repeatabilityTest, runsHalfMax: updatedRuns },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={run.deltaL}
                            onChange={(e) => {
                              const updatedRuns = [...report.repeatabilityTest.runsHalfMax];
                              const newDelta = parseFloat(e.target.value) || 0;
                              updatedRuns[i] = { ...run, deltaL: newDelta };
                              handleUpdate({
                                ...report,
                                repeatabilityTest: { ...report.repeatabilityTest, runsHalfMax: updatedRuns },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>{roundMetrology(run.indication + 0.5 * report.instrument.verificationScaleInterval - run.deltaL, 6)}</td>
                      </tr>
                    ))}
                  </tbody>
                </table>

                <div className="rep-result-bar">
                  <span>Spread (I_max - I_min): <strong>{report.repeatabilityTest.halfMaxDiff} {report.instrument.unit}</strong></span>
                  <span>Tolerance Limit: <strong>≤ {report.repeatabilityTest.halfMaxMpe} {report.instrument.unit}</strong></span>
                </div>
              </div>

              {/* Series 2: ~ 100% Max */}
              <div className="form-card">
                <div className="rep-series-header">
                  <div>
                    <h5>Series 2: Maximum Capacity (~ 100% Max)</h5>
                    <p>Load: {report.repeatabilityTest.maxLoad} {report.instrument.unit} | MPE: ±{report.repeatabilityTest.maxMpe} {report.instrument.unit}</p>
                  </div>
                  <span className={`badge ${report.repeatabilityTest.maxPassed ? 'badge-pass' : 'badge-fail'}`}>
                    {report.repeatabilityTest.maxPassed ? 'PASS' : 'FAIL'}
                  </span>
                </div>

                <table className="data-table">
                  <thead>
                    <tr>
                      <th>Run #</th>
                      <th>Applied Load</th>
                      <th>Indication (I)</th>
                      <th>Turning ΔL</th>
                      <th>True P</th>
                    </tr>
                  </thead>
                  <tbody>
                    {report.repeatabilityTest.runsMax.map((run, i) => (
                      <tr key={`max-run-${i}`}>
                        <td>Run {run.runIndex}</td>
                        <td>{run.load} {report.instrument.unit}</td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={run.indication}
                            onChange={(e) => {
                              const updatedRuns = [...report.repeatabilityTest.runsMax];
                              const newInd = parseFloat(e.target.value) || 0;
                              updatedRuns[i] = { ...run, indication: newInd };
                              handleUpdate({
                                ...report,
                                repeatabilityTest: { ...report.repeatabilityTest, runsMax: updatedRuns },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>
                          <input
                            type="number"
                            step="any"
                            value={run.deltaL}
                            onChange={(e) => {
                              const updatedRuns = [...report.repeatabilityTest.runsMax];
                              const newDelta = parseFloat(e.target.value) || 0;
                              updatedRuns[i] = { ...run, deltaL: newDelta };
                              handleUpdate({
                                ...report,
                                repeatabilityTest: { ...report.repeatabilityTest, runsMax: updatedRuns },
                              });
                            }}
                            className="table-input"
                          />
                        </td>
                        <td>{roundMetrology(run.indication + 0.5 * report.instrument.verificationScaleInterval - run.deltaL, 6)}</td>
                      </tr>
                    ))}
                  </tbody>
                </table>

                <div className="rep-result-bar">
                  <span>Spread (I_max - I_min): <strong>{report.repeatabilityTest.maxDiff} {report.instrument.unit}</strong></span>
                  <span>Tolerance Limit: <strong>≤ {report.repeatabilityTest.maxMpe} {report.instrument.unit}</strong></span>
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ================= TAB 5: CORNER ECCENTRICITY ================= */}
        {activeTab === 'eccentricity' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Eccentricity / Corner Loading Test (Clause 3.6.2 & Annex A.4.7)</h3>
                <p>Corner Loading Error |Ec| ≤ MPE & Maximum Spread between any two positions ≤ MPE</p>
              </div>
            </div>

            {/* Receptor Type selector */}
            <div className="form-card inline-flex-card">
              <div className="form-field">
                <label>Load Receptor Shape & Configuration:</label>
                <select
                  value={report.eccentricityTest.receptorType}
                  onChange={(e) => {
                    handleUpdate({
                      ...report,
                      eccentricityTest: {
                        ...report.eccentricityTest,
                        receptorType: e.target.value as any,
                      },
                    });
                  }}
                >
                  <option value="rectangular_4_corners">Rectangular Pan / Platform (4 Corners + Center)</option>
                  <option value="round_4_points">Circular Pan (4 Quadrants + Center)</option>
                  <option value="weighbridge_sections">Weighbridge Deck (Support Axle Sections)</option>
                </select>
              </div>

              <div className="form-field">
                <label>Applied Test Load (~ 1/3 Max):</label>
                <input
                  type="number"
                  step="any"
                  value={report.eccentricityTest.testLoad}
                  onChange={(e) => {
                    const newLoad = parseFloat(e.target.value) || 0;
                    handleUpdate({
                      ...report,
                      eccentricityTest: { ...report.eccentricityTest, testLoad: newLoad },
                    });
                  }}
                />
              </div>
            </div>

            {/* Visual Platform Schematic & Corner Inspector */}
            <EccentricityDiagram test={report.eccentricityTest} unit={report.instrument.unit} />

            {/* Data Entry Table */}
            <div className="form-card" style={{ marginTop: '1.25rem' }}>
              <h4 className="form-section-title">Eccentricity Position Readings</h4>
              <table className="data-table">
                <thead>
                  <tr>
                    <th>Location / Point</th>
                    <th>Indication (I)</th>
                    <th>Turning ΔL</th>
                    <th>True P</th>
                    <th>Corrected Ec</th>
                    <th>MPE (±)</th>
                    <th>Status</th>
                  </tr>
                </thead>
                <tbody>
                  {report.eccentricityTest.points.map((pt, i) => (
                    <tr key={pt.positionKey} className={pt.passed ? '' : 'row-failed'}>
                      <td><strong>{pt.positionLabel}</strong></td>
                      <td>
                        <input
                          type="number"
                          step="any"
                          value={pt.indication}
                          onChange={(e) => {
                            const updated = [...report.eccentricityTest.points];
                            updated[i] = { ...pt, indication: parseFloat(e.target.value) || 0 };
                            handleUpdate({
                              ...report,
                              eccentricityTest: { ...report.eccentricityTest, points: updated },
                            });
                          }}
                          className="table-input"
                        />
                      </td>
                      <td>
                        <input
                          type="number"
                          step="any"
                          value={pt.deltaL}
                          onChange={(e) => {
                            const updated = [...report.eccentricityTest.points];
                            updated[i] = { ...pt, deltaL: parseFloat(e.target.value) || 0 };
                            handleUpdate({
                              ...report,
                              eccentricityTest: { ...report.eccentricityTest, points: updated },
                            });
                          }}
                          className="table-input"
                        />
                      </td>
                      <td>{pt.trueIndication} {report.instrument.unit}</td>
                      <td>
                        <strong className={pt.passed ? 'text-success' : 'text-danger'}>
                          {pt.correctedError >= 0 ? '+' : ''}{pt.correctedError} {report.instrument.unit}
                        </strong>
                      </td>
                      <td>±{pt.mpe} {report.instrument.unit}</td>
                      <td>
                        <span className={`badge ${pt.passed ? 'badge-pass' : 'badge-fail'}`}>
                          {pt.passed ? 'PASS' : 'FAIL'}
                        </span>
                      </td>
                    </tr>
                  ))}
                </tbody>
              </table>
            </div>
          </div>
        )}

        {/* ================= TAB 6: DISCRIMINATION & AUX TESTS ================= */}
        {activeTab === 'aux' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Discrimination, Zero Stability & Tare Evaluation</h3>
                <p>OIML R 76-1 Clauses 3.8 (Discrimination), 4.5 (Zero-setting), 4.6 (Tare), 3.9 (Tilting)</p>
              </div>
            </div>

            {/* Discrimination Card */}
            <div className="form-card">
              <div className="rep-series-header">
                <div>
                  <h5>1. Discrimination Test (Clause 3.8 & Annex A.4.8)</h5>
                  <p>When extra load equal to 1.4d is added to the loaded scale, indication must increase by at least 1d.</p>
                </div>
                <span className={`badge ${report.discriminationTest.passed ? 'badge-pass' : 'badge-fail'}`}>
                  {report.discriminationTest.passed ? 'DISCRIMINATION PASSED' : 'FAILED'}
                </span>
              </div>

              <table className="data-table">
                <thead>
                  <tr>
                    <th>Test Load Level</th>
                    <th>Base Load</th>
                    <th>Base Indication</th>
                    <th>Extra Load (1.4d)</th>
                    <th>New Indication</th>
                    <th>Observed Change</th>
                    <th>Required (≥ 1d)</th>
                    <th>Status</th>
                  </tr>
                </thead>
                <tbody>
                  {report.discriminationTest.checks.map((chk, i) => (
                    <tr key={chk.loadLevel}>
                      <td><strong>{chk.loadLevel}</strong></td>
                      <td>{chk.baseLoad} {report.instrument.unit}</td>
                      <td>{chk.baseIndication} {report.instrument.unit}</td>
                      <td>{chk.extraLoad} {report.instrument.unit}</td>
                      <td>
                        <input
                          type="number"
                          step="any"
                          value={chk.newIndication}
                          onChange={(e) => {
                            const updated = [...report.discriminationTest.checks];
                            updated[i] = { ...chk, newIndication: parseFloat(e.target.value) || 0 };
                            handleUpdate({
                              ...report,
                              discriminationTest: { ...report.discriminationTest, checks: updated },
                            });
                          }}
                          className="table-input"
                        />
                      </td>
                      <td><strong>{chk.indicationChange} {report.instrument.unit}</strong></td>
                      <td>≥ {chk.minimumRequiredChange} {report.instrument.unit}</td>
                      <td>
                        <span className={`badge ${chk.passed ? 'badge-pass' : 'badge-fail'}`}>
                          {chk.passed ? 'PASS' : 'FAIL'}
                        </span>
                      </td>
                    </tr>
                  ))}
                </tbody>
              </table>
            </div>

            {/* Zero and Tare grid */}
            <div className="rep-grid-two">
              {/* Zero setting test */}
              <div className="form-card">
                <h5 className="form-section-title">2. Zero Setting & Zero Tracking (Clause 4.5)</h5>
                <div className="form-grid-1">
                  <div className="form-field">
                    <label>Zero Setting Error (E0):</label>
                    <input
                      type="number"
                      step="any"
                      value={report.zeroTest.zeroErrorE0}
                      onChange={(e) => {
                        handleUpdate({
                          ...report,
                          zeroTest: { ...report.zeroTest, zeroErrorE0: parseFloat(e.target.value) || 0 },
                        });
                      }}
                    />
                    <small className="field-hint">Max Permissible E0: ±{report.zeroTest.maxPermissibleE0} {report.instrument.unit} (0.25e)</small>
                  </div>

                  <div className="form-field">
                    <label>Zero-Tracking Rate (d / second):</label>
                    <input
                      type="number"
                      step="any"
                      value={report.zeroTest.zeroTrackingRate}
                      onChange={(e) => {
                        handleUpdate({
                          ...report,
                          zeroTest: { ...report.zeroTest, zeroTrackingRate: parseFloat(e.target.value) || 0 },
                        });
                      }}
                    />
                    <small className="field-hint">Max Permissible Zero Tracking: ≤ {report.zeroTest.maxZeroTrackingRate} d/s (0.5d/s)</small>
                  </div>

                  <div className="zero-status-box">
                    <span className={`badge ${report.zeroTest.passed ? 'badge-pass' : 'badge-fail'}`}>
                      {report.zeroTest.passed ? '✓ Zero Devices Compliant' : '✕ Zero Requirements Exceeded'}
                    </span>
                  </div>
                </div>
              </div>

              {/* Tare test */}
              <div className="form-card">
                <h5 className="form-section-title">3. Tare Balancing & Weighing (Clause 4.6)</h5>
                <div className="form-grid-1">
                  <div className="form-field">
                    <label>Tare Applied Load:</label>
                    <input
                      type="number"
                      step="any"
                      value={report.tareTest.tareApplied}
                      onChange={(e) => {
                        handleUpdate({
                          ...report,
                          tareTest: { ...report.tareTest, tareApplied: parseFloat(e.target.value) || 0 },
                        });
                      }}
                    />
                  </div>

                  <div className="form-field">
                    <label>Net Test Load:</label>
                    <input
                      type="number"
                      step="any"
                      value={report.tareTest.netTestLoad}
                      onChange={(e) => {
                        handleUpdate({
                          ...report,
                          tareTest: { ...report.tareTest, netTestLoad: parseFloat(e.target.value) || 0 },
                        });
                      }}
                    />
                  </div>

                  <div className="form-field">
                    <label>Indicated Net Weight:</label>
                    <input
                      type="number"
                      step="any"
                      value={report.tareTest.indicatedNet}
                      onChange={(e) => {
                        handleUpdate({
                          ...report,
                          tareTest: { ...report.tareTest, indicatedNet: parseFloat(e.target.value) || 0 },
                        });
                      }}
                    />
                    <small className="field-hint">Net Error: {report.tareTest.netError} (MPE: ±{report.tareTest.netMpe})</small>
                  </div>

                  <div className="zero-status-box">
                    <span className={`badge ${report.tareTest.passed ? 'badge-pass' : 'badge-fail'}`}>
                      {report.tareTest.passed ? '✓ Tare Performance Compliant' : '✕ Tare Error Exceeded'}
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        )}

        {/* ================= TAB 7: SIGNOFF & CERTIFICATE ================= */}
        {activeTab === 'signoff' && (
          <div className="tab-pane-content">
            <div className="pane-section-header">
              <div>
                <h3>Official Legal Metrology Type Evaluation Sign-Off & Certificate</h3>
                <p>OIML R 76-2 Pattern Evaluation Report Review & Approval Workflow</p>
              </div>
            </div>

            {/* Official Certificate Preview Card */}
            <div className="certificate-preview-card">
              <div className="cert-header">
                <div className="cert-emblem-text">
                  <h5>GOVERNMENT OF INDIA</h5>
                  <h6>MINISTRY OF CONSUMER AFFAIRS, FOOD & PUBLIC DISTRIBUTION</h6>
                  <p>DIRECTORATE OF LEGAL METROLOGY | OIML ISSUING AUTHORITY</p>
                  <span className="cert-type-text">PATTERN EVALUATION REPORT UNDER OIML R 76-2:2007</span>
                </div>
              </div>

              <div className="cert-meta-grid">
                <div>
                  <span>Report Number:</span>
                  <strong>{report.instrument.reportNumber}</strong>
                </div>
                <div>
                  <span>Application Number:</span>
                  <strong>{report.instrument.applicationNumber}</strong>
                </div>
                <div>
                  <span>Instrument Model:</span>
                  <strong>{report.instrument.manufacturer} — {report.instrument.model}</strong>
                </div>
                <div>
                  <span>Class & Capacity:</span>
                  <strong>Class {report.instrument.accuracyClass} | Max: {report.instrument.maxCapacity} {report.instrument.unit} (e = {report.instrument.verificationScaleInterval} {report.instrument.unit})</strong>
                </div>
              </div>

              <div className={`cert-verdict-banner ${report.overallVerdict === 'COMPLIANT' ? 'cert-pass' : 'cert-fail'}`}>
                {report.overallVerdict === 'COMPLIANT' ? (
                  <>
                    <CheckCircle2 size={28} />
                    <div>
                      <h4>METROLOGICALLY COMPLIANT — RECOMMEND PATTERN APPROVAL</h4>
                      <p>Instrument fully satisfies all applicable requirements of OIML Recommendation R 76-1:2006.</p>
                    </div>
                  </>
                ) : (
                  <>
                    <XCircle size={28} />
                    <div>
                      <h4>NON-COMPLIANT — REJECTED FOR MODEL APPROVAL</h4>
                      <p>Instrument failed one or more mandatory accuracy, repeatability, or eccentricity limits.</p>
                    </div>
                  </>
                )}
              </div>

              {/* Gemma 4 Metrology AI Generator */}
              <div
                className="ai-assistant-card"
                style={{
                  marginTop: '1.25rem',
                  padding: '16px 20px',
                  borderRadius: '10px',
                  background: 'linear-gradient(135deg, #f5f3ff 0%, #ede9fe 100%)',
                  border: '1.5px solid #c4b5fd',
                }}
              >
                <div
                  style={{
                    display: 'flex',
                    alignItems: 'center',
                    justifyContent: 'space-between',
                    flexWrap: 'wrap',
                    gap: '12px',
                  }}
                >
                  <div style={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
                    <div
                      style={{
                        width: '36px',
                        height: '36px',
                        borderRadius: '8px',
                        background: 'linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%)',
                        color: '#ffffff',
                        display: 'flex',
                        alignItems: 'center',
                        justifyContent: 'center',
                      }}
                    >
                      <Sparkles size={20} />
                    </div>
                    <div>
                      <h4 style={{ margin: 0, fontSize: '0.98rem', fontWeight: 700, color: '#4c1d95' }}>
                        Gemma 4 Metrology AI Assistant
                      </h4>
                      <p style={{ margin: '2px 0 0', fontSize: '0.8rem', color: '#6d28d9' }}>
                        Auto-draft formal evaluator findings or diagnose failure root causes using active model (
                        {AVAILABLE_MODELS.find((m) => m.id === getStoredModel())?.name || 'Gemma 4'})
                      </p>
                    </div>
                  </div>

                  <div style={{ display: 'flex', gap: '10px', alignItems: 'center' }}>
                    <button
                      type="button"
                      className="btn"
                      disabled={aiLoading}
                      onClick={async () => {
                        const key = getStoredApiKey();
                        if (!key) {
                          if (onOpenAISettings) onOpenAISettings();
                          else setAiError('Please enter your Gemma 4 API key first in AI Settings.');
                          return;
                        }
                        setAiLoading(true);
                        setAiLoadingText('Gemma 4 is synthesizing test observations and calculating OIML R 76 clause compliance...');
                        setAiError(null);
                        try {
                          const text = await generateEvaluatorRemarksWithGemma(report);
                          setAiResult({ type: 'remarks', text });
                        } catch (err: any) {
                          setAiError(err.message || 'Failed to generate remarks with Gemma 4');
                        } finally {
                          setAiLoading(false);
                        }
                      }}
                      style={{
                        backgroundColor: '#7c3aed',
                        color: '#ffffff',
                        fontWeight: 600,
                        fontSize: '0.84rem',
                        display: 'inline-flex',
                        alignItems: 'center',
                        gap: '6px',
                        padding: '8px 14px',
                        borderRadius: '6px',
                        border: 'none',
                        cursor: 'pointer',
                      }}
                    >
                      <Sparkles size={16} />
                      <span>✨ Draft Remarks with Gemma 4</span>
                    </button>

                    <button
                      type="button"
                      className="btn"
                      disabled={aiLoading}
                      onClick={async () => {
                        const key = getStoredApiKey();
                        if (!key) {
                          if (onOpenAISettings) onOpenAISettings();
                          else setAiError('Please enter your Gemma 4 API key first in AI Settings.');
                          return;
                        }
                        setAiLoading(true);
                        setAiLoadingText('Gemma 4 is diagnosing load-cell mechanical & tolerance anomalies...');
                        setAiError(null);
                        try {
                          const text = await diagnoseInstrumentFailureWithGemma(report);
                          setAiResult({ type: 'diagnostics', text });
                        } catch (err: any) {
                          setAiError(err.message || 'Failed to diagnose instrument with Gemma 4');
                        } finally {
                          setAiLoading(false);
                        }
                      }}
                      style={{
                        backgroundColor: '#ffffff',
                        color: '#6d28d9',
                        border: '1px solid #c4b5fd',
                        fontWeight: 600,
                        fontSize: '0.84rem',
                        display: 'inline-flex',
                        alignItems: 'center',
                        gap: '6px',
                        padding: '8px 14px',
                        borderRadius: '6px',
                        cursor: 'pointer',
                      }}
                    >
                      <Activity size={16} />
                      <span>Diagnose Non-Conformities</span>
                    </button>
                  </div>
                </div>

                {/* Loading Banner */}
                {aiLoading && (
                  <div
                    style={{
                      marginTop: '12px',
                      padding: '12px 16px',
                      backgroundColor: '#ffffff',
                      borderRadius: '8px',
                      display: 'flex',
                      alignItems: 'center',
                      gap: '10px',
                      color: '#6d28d9',
                      fontSize: '0.86rem',
                      fontWeight: 500,
                    }}
                  >
                    <Sparkles size={16} className="spin-animation" style={{ color: '#7c3aed' }} />
                    <span>{aiLoadingText}</span>
                  </div>
                )}

                {/* Error Banner */}
                {aiError && (
                  <div
                    style={{
                      marginTop: '12px',
                      padding: '12px 16px',
                      backgroundColor: '#fef2f2',
                      border: '1px solid #f87171',
                      borderRadius: '8px',
                      display: 'flex',
                      alignItems: 'center',
                      justifyContent: 'space-between',
                      gap: '10px',
                      color: '#991b1b',
                      fontSize: '0.86rem',
                    }}
                  >
                    <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
                      <AlertCircle size={18} style={{ color: '#ef4444', flexShrink: 0 }} />
                      <span>{aiError}</span>
                    </div>
                    {onOpenAISettings && (
                      <button
                        onClick={onOpenAISettings}
                        style={{
                          padding: '4px 10px',
                          fontSize: '0.78rem',
                          backgroundColor: '#ef4444',
                          color: '#ffffff',
                          border: 'none',
                          borderRadius: '4px',
                          cursor: 'pointer',
                          fontWeight: 600,
                        }}
                      >
                        Enter API Key
                      </button>
                    )}
                  </div>
                )}

                {/* Result Preview Box */}
                {aiResult && (
                  <div
                    style={{
                      marginTop: '14px',
                      backgroundColor: '#ffffff',
                      border: '1px solid #c4b5fd',
                      borderRadius: '8px',
                      padding: '16px',
                    }}
                  >
                    <div
                      style={{
                        display: 'flex',
                        alignItems: 'center',
                        justifyContent: 'space-between',
                        marginBottom: '10px',
                        borderBottom: '1px solid #f1f5f9',
                        paddingBottom: '8px',
                      }}
                    >
                      <span
                        style={{
                          fontWeight: 700,
                          fontSize: '0.9rem',
                          color: '#4c1d95',
                          display: 'flex',
                          alignItems: 'center',
                          gap: '6px',
                        }}
                      >
                        <Bot size={16} />
                        {aiResult.type === 'remarks'
                          ? 'Draft Evaluator Technical Remarks'
                          : 'Metrological Root Cause Diagnosis'}
                      </span>
                      <div style={{ display: 'flex', gap: '8px' }}>
                        <button
                          type="button"
                          onClick={() => {
                            navigator.clipboard.writeText(aiResult.text);
                            setAiCopied(true);
                            setTimeout(() => setAiCopied(false), 2000);
                          }}
                          style={{
                            padding: '4px 10px',
                            fontSize: '0.78rem',
                            backgroundColor: '#f8fafc',
                            border: '1px solid #cbd5e1',
                            borderRadius: '4px',
                            cursor: 'pointer',
                            display: 'inline-flex',
                            alignItems: 'center',
                            gap: '4px',
                          }}
                        >
                          {aiCopied ? <Check size={12} color="#10b981" /> : <Copy size={12} />}
                          <span>{aiCopied ? 'Copied' : 'Copy'}</span>
                        </button>
                        {aiResult.type === 'remarks' && (
                          <button
                            type="button"
                            onClick={() => {
                              handleUpdate({
                                ...report,
                                evaluatorRemarks: aiResult.text,
                              });
                              setAiResult(null);
                            }}
                            style={{
                              padding: '4px 12px',
                              fontSize: '0.78rem',
                              backgroundColor: '#10b981',
                              color: '#ffffff',
                              border: 'none',
                              borderRadius: '4px',
                              cursor: 'pointer',
                              fontWeight: 600,
                              display: 'inline-flex',
                              alignItems: 'center',
                              gap: '4px',
                            }}
                          >
                            <Check size={14} />
                            <span>Apply to Remarks Field</span>
                          </button>
                        )}
                        <button
                          type="button"
                          onClick={() => setAiResult(null)}
                          style={{
                            padding: '4px 8px',
                            fontSize: '0.78rem',
                            background: 'none',
                            border: 'none',
                            cursor: 'pointer',
                            color: '#94a3b8',
                          }}
                        >
                          Dismiss
                        </button>
                      </div>
                    </div>
                    <div
                      style={{
                        fontSize: '0.84rem',
                        lineHeight: '1.55',
                        color: '#1e293b',
                        whiteSpace: 'pre-wrap',
                        maxHeight: '260px',
                        overflowY: 'auto',
                      }}
                    >
                      {aiResult.text}
                    </div>
                  </div>
                )}
              </div>

              {/* Remarks Form */}
              <div className="form-grid-2" style={{ marginTop: '1.25rem' }}>
                <div className="form-field">
                  <label>Evaluator Findings & Laboratory Remarks:</label>
                  <textarea
                    rows={4}
                    value={report.evaluatorRemarks}
                    onChange={(e) => handleUpdate({ ...report, evaluatorRemarks: e.target.value })}
                  />
                  <small className="field-hint">Signed by: {report.evaluatorSignature || activeUser.name}</small>
                </div>

                <div className="form-field">
                  <label>Approver Review & Endorsement (Director / Approving Officer):</label>
                  <textarea
                    rows={4}
                    value={report.approverRemarks || ''}
                    onChange={(e) => handleUpdate({ ...report, approverRemarks: e.target.value })}
                    placeholder="Enter formal approval endorsement or reasons for rejection..."
                  />
                  <small className="field-hint">Endorsed by: {report.approverSignature || 'Awaiting Director Sign-off'}</small>
                </div>
              </div>

              {/* Status and Role Action Bar */}
              <div className="workflow-action-bar">
                <div className="status-selector-group">
                  <label>Report Workflow Status:</label>
                  <select
                    value={report.status}
                    onChange={(e) => {
                      const newStatus = e.target.value as any;
                      const updated = {
                        ...report,
                        status: newStatus,
                        auditTrail: [
                          ...report.auditTrail,
                          {
                            id: `aud-${Date.now()}`,
                            timestamp: new Date().toISOString(),
                            userName: activeUser.name,
                            userRole: activeUser.role,
                            action: 'STATUS_CHANGED' as const,
                            description: `Status changed to ${newStatus.toUpperCase()}`,
                          },
                        ],
                      };
                      if (newStatus === 'approved') {
                        updated.approverSignature = activeUser.name;
                      }
                      handleUpdate(updated);
                    }}
                    className="status-dropdown"
                  >
                    <option value="draft">Draft (Work in Progress)</option>
                    <option value="under_evaluation">Under Evaluation (Testing)</option>
                    <option value="pending_approval">Pending Director Approval</option>
                    <option value="approved">Approved & Certified</option>
                    <option value="rejected">Rejected (Non-Compliant)</option>
                  </select>
                </div>

                <div className="export-buttons-group">
                  <button className="btn btn-secondary btn-icon-text" onClick={() => exportReportToPDF(report)}>
                    <FileDown size={16} />
                    <span>Download Official PDF</span>
                  </button>

                  <button className="btn btn-secondary btn-icon-text" onClick={() => exportReportToDocx(report)}>
                    <FileText size={16} />
                    <span>Download Word (.docx)</span>
                  </button>

                  <button className="btn btn-secondary btn-icon-text" onClick={() => window.print()}>
                    <Printer size={16} />
                    <span>Print Report</span>
                  </button>
                </div>
              </div>

              {/* Tamper Proof Hash & Integrity verification */}
              <div className="verification-hash-footer">
                <span className="hash-label">Cryptographic Verification Token (SHA-256 Checksum):</span>
                <code className="hash-code">{report.verificationHash}</code>
              </div>
            </div>

            {/* Audit Trail Log */}
            <div className="form-card" style={{ marginTop: '1.25rem' }}>
              <h4 className="form-section-title">Tamper-Evident Audit Trail & History</h4>
              <div className="audit-timeline">
                {report.auditTrail.map((log) => (
                  <div key={log.id} className="audit-entry">
                    <div className="audit-dot"></div>
                    <div className="audit-meta">
                      <span className="audit-time">{new Date(log.timestamp).toLocaleString()}</span>
                      <strong className="audit-user">{log.userName} ({log.userRole.replace('_', ' ')})</strong>
                      <span className="audit-action-tag">{log.action}</span>
                    </div>
                    <div className="audit-desc">{log.description}</div>
                  </div>
                ))}
              </div>
            </div>
          </div>
        )}
      </div>
    </div>
  );
};

```

---

### File 25: `src/index.css`
*Path: `src/index.css` | Size: 2683 bytes | Source File*

```css
:root {
  /* Brand Tokens - Legal Metrology & Precision Engineering */
  --brand-navy: #0f2b48;
  --brand-navy-hover: #153c64;
  --brand-navy-dark: #091c30;
  --brand-teal: #0d9488;
  --brand-teal-light: #ccfbf1;
  --brand-saffron: #f97316;
  --brand-saffron-light: #ffedd5;
  --brand-gold: #eab308;

  /* Surfaces & Canvas */
  --bg-canvas: #f8fafc;
  --surface-card: #ffffff;
  --surface-subtle: #f1f5f9;
  --surface-elevated: #ffffff;
  --surface-overlay: rgba(15, 23, 42, 0.65);

  /* High-Contrast Typography */
  --text-primary: #0f172a;
  --text-secondary: #334155;
  --text-muted: #64748b;
  --text-inverse: #ffffff;

  /* Borders & Dividers */
  --border-subtle: #e2e8f0;
  --border-medium: #cbd5e1;
  --border-strong: #94a3b8;
  --border-focus: #0284c7;

  /* Semantic Status Tokens (paired with distinct iconography and labels) */
  --color-pass: #059669;
  --color-pass-bg: #ecfdf5;
  --color-pass-border: #a7f3d0;
  --color-pass-text: #065f46;

  --color-fail: #dc2626;
  --color-fail-bg: #fef2f2;
  --color-fail-border: #fecaca;
  --color-fail-text: #991b1b;

  --color-warning: #d97706;
  --color-warning-bg: #fffbeb;
  --color-warning-border: #fde68a;
  --color-warning-text: #92400e;

  --color-info: #0284c7;
  --color-info-bg: #f0f9ff;
  --color-info-border: #bae6fd;
  --color-info-text: #075985;

  /* Shadows */
  --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
  --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.08), 0 2px 4px -2px rgba(0, 0, 0, 0.04);
  --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.08), 0 4px 6px -4px rgba(0, 0, 0, 0.04);
  --shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.05);

  /* Radii */
  --radius-sm: 6px;
  --radius-md: 10px;
  --radius-lg: 14px;
  --radius-full: 9999px;

  /* Typography */
  --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  --font-heading: 'Outfit', 'Inter', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;

  /* Transitions */
  --transition-fast: 150ms cubic-bezier(0.4, 0, 0.2, 1);
  --transition-normal: 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

*, *::before, *::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html, body {
  height: 100%;
  font-family: var(--font-sans);
  background-color: var(--bg-canvas);
  color: var(--text-primary);
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  overflow-x: hidden;
}

button, input, select, textarea {
  font-family: inherit;
  font-size: inherit;
}

button {
  cursor: pointer;
  border: none;
  background: none;
}

a {
  color: inherit;
  text-decoration: none;
}

code, pre {
  font-family: var(--font-mono);
}

```

---

### File 26: `src/main.tsx`
*Path: `src/main.tsx` | Size: 230 bytes | Source File*

```tsx
import { StrictMode } from 'react'
import { createRoot } from 'react-dom/client'
import './index.css'
import App from './App.tsx'

createRoot(document.getElementById('root')!).render(
  <StrictMode>
    <App />
  </StrictMode>,
)

```

---

### File 27: `src/types/oiml.ts`
*Path: `src/types/oiml.ts` | Size: 6802 bytes | TypeScript Type Definitions & OIML R 76 Schema*

```typescript
export type AccuracyClass = 'I' | 'II' | 'III' | 'IIII';

export type VerificationType = 'initial' | 'subsequent' | 'in_service';

export type ScaleUnit = 'g' | 'kg' | 't' | 'mg';

export type ReportStatus = 'draft' | 'under_evaluation' | 'pending_approval' | 'approved' | 'rejected';

export type UserRole = 'director' | 'senior_metrologist' | 'testing_officer' | 'auditor';

export interface UserProfile {
  id: string;
  name: string;
  role: UserRole;
  designation: string;
  department: string;
  signatureUrl?: string;
}

export interface RangeSpecification {
  rangeIndex: number;
  max: number;
  min: number;
  e: number;
  d: number;
  n: number;
}

export interface InstrumentSpecification {
  id: string;
  reportNumber: string;
  applicationNumber: string;
  manufacturer: string;
  applicant: string;
  model: string;
  serialNumber: string;
  yearOfManufacture: number;
  deviceType: 'Counter Scale' | 'Bench Scale' | 'Platform Scale' | 'Weighbridge' | 'Precision Balance' | 'Crane Scale' | 'Hopper Scale' | 'Axle Weigher';
  accuracyClass: AccuracyClass;
  verificationType: VerificationType;
  unit: ScaleUnit;
  maxCapacity: number;
  minCapacity: number;
  verificationScaleInterval: number; // e
  actualScaleInterval: number; // d
  scaleIntervalCount: number; // n = Max / e
  isMultiInterval: boolean;
  ranges?: RangeSpecification[];
  tareType: 'subtractive' | 'additive' | 'tare_balance' | 'preset_tare' | 'none';
  maxTare: number;
  zeroSettingType: 'semi_automatic' | 'automatic' | 'initial_zero' | 'zero_tracking';
  indicatorModel: string;
  loadCellModel: string;
  loadCellCertificateNo: string;
  loadCellCount: number;
  platformDimensions: string; // e.g. "500 mm x 500 mm" or "18 m x 3 m"
}

export interface EnvironmentalConditions {
  laboratoryName: string;
  laboratoryAddress: string;
  nablAccreditationNo: string;
  oimlIssuingAuthority: string;
  evaluationLocation: string;
  testDate: string;
  evaluationStartTime: string;
  evaluationEndTime: string;
  ambientTempStart: number; // °C
  ambientTempEnd: number; // °C
  relativeHumidity: number; // %
  barometricPressure: number; // hPa
  mainsVoltage: number; // V
  mainsFrequency: number; // Hz
  warmUpTimeMinutes: number;
  standardWeightsClass: 'E1' | 'E2' | 'F1' | 'F2' | 'M1' | 'M2';
  standardWeightsCertNo: string;
  standardWeightsValidity: string;
  standardWeightsUncertainty: string;
}

export interface WeighingTestRow {
  step: number;
  direction: 'increasing' | 'decreasing';
  nominalLoad: number; // L
  indication: number; // I
  deltaL: number; // additional weights placed to find turning point (0.1e weights)
  trueIndication: number; // P = I + 0.5e - deltaL
  error: number; // E = P - L
  correctedError: number; // Ec = E - E0
  mpe: number; // Maximum Permissible Error (±)
  passed: boolean;
  notes?: string;
}

export interface WeighingTestResult {
  zeroErrorStart: number; // E0 start
  zeroErrorEnd: number; // E0 end
  rows: WeighingTestRow[];
  maxCorrectedError: number;
  maxMpeRatio: number; // max(|Ec| / MPE)
  hysteresisMax: number;
  hysteresisPassed: boolean;
  passed: boolean;
}

export interface RepeatabilityRun {
  runIndex: number;
  load: number;
  indication: number;
  deltaL: number;
  trueIndication: number;
  error: number;
}

export interface RepeatabilityTestResult {
  runsHalfMax: RepeatabilityRun[];
  runsMax: RepeatabilityRun[];
  halfMaxLoad: number;
  halfMaxDiff: number; // I_max - I_min
  halfMaxMpe: number;
  halfMaxPassed: boolean;
  maxLoad: number;
  maxDiff: number; // I_max - I_min
  maxMpe: number;
  maxPassed: boolean;
  passed: boolean;
}

export interface EccentricityPoint {
  positionKey: 'center' | 'corner_1' | 'corner_2' | 'corner_3' | 'corner_4' | 'section_1' | 'section_2' | 'section_3';
  positionLabel: string;
  indication: number;
  deltaL: number;
  trueIndication: number;
  error: number;
  correctedError: number;
  mpe: number;
  passed: boolean;
}

export interface EccentricityTestResult {
  testLoad: number; // typically 1/3 Max
  receptorType: 'rectangular_4_corners' | 'round_4_points' | 'weighbridge_sections';
  points: EccentricityPoint[];
  maxSpread: number; // max(Ec) - min(Ec)
  maxMpe: number;
  spreadPassed: boolean;
  passed: boolean;
}

export interface DiscriminationCheck {
  loadLevel: 'Min' | '0.5 Max' | 'Max';
  baseLoad: number;
  baseIndication: number;
  extraLoad: number; // 1.4 * d
  newIndication: number;
  indicationChange: number; // newIndication - baseIndication
  minimumRequiredChange: number; // 1 * d
  passed: boolean;
}

export interface DiscriminationTestResult {
  checks: DiscriminationCheck[];
  passed: boolean;
}

export interface TareTestResult {
  tareApplied: number;
  netTestLoad: number;
  indicatedNet: number;
  deltaL: number;
  trueNet: number;
  netError: number;
  netMpe: number;
  tareBalancingError: number;
  maxPermissibleTareError: number; // 0.25e
  passed: boolean;
}

export interface ZeroTestResult {
  zeroErrorE0: number;
  maxPermissibleE0: number; // 0.25e
  zeroSettingPassed: boolean;
  zeroTrackingRate: number; // d/s
  maxZeroTrackingRate: number; // 0.5 d/s
  zeroTrackingPassed: boolean;
  passed: boolean;
}

export interface TiltingTestResult {
  applicable: boolean;
  tiltRatio: string; // e.g. "50/1000" (approx 2.86°)
  zeroIndicationNoTilt: number;
  zeroIndicationTilted: number;
  zeroShift: number;
  maxPermissibleShift: number; // 1e
  passed: boolean;
}

export interface TemperatureTestPoint {
  tempNominal: number; // °C (e.g. 20, 40, -10, 20)
  actualTemp: number;
  zeroIndication: number;
  zeroShiftPer5C: number;
  maxPermissibleShiftPer5C: number; // 1e per 5°C
  passed: boolean;
}

export interface TemperatureTestResult {
  applicable: boolean;
  points: TemperatureTestPoint[];
  passed: boolean;
}

export interface AuditLogEntry {
  id: string;
  timestamp: string;
  userName: string;
  userRole: UserRole;
  action: 'CREATED' | 'UPDATED' | 'VALIDATED' | 'STATUS_CHANGED' | 'EXPORTED_PDF' | 'EXPORTED_DOCX' | 'APPROVED' | 'REJECTED';
  description: string;
}

export interface OIMLTestReport {
  id: string;
  createdAt: string;
  updatedAt: string;
  status: ReportStatus;
  instrument: InstrumentSpecification;
  environment: EnvironmentalConditions;
  weighingTest: WeighingTestResult;
  repeatabilityTest: RepeatabilityTestResult;
  eccentricityTest: EccentricityTestResult;
  discriminationTest: DiscriminationTestResult;
  tareTest: TareTestResult;
  zeroTest: ZeroTestResult;
  tiltingTest: TiltingTestResult;
  temperatureTest: TemperatureTestResult;
  overallVerdict: 'COMPLIANT' | 'NON_COMPLIANT';
  evaluatorRemarks: string;
  evaluatorSignature?: string;
  approverRemarks?: string;
  approverSignature?: string;
  verificationHash: string;
  auditTrail: AuditLogEntry[];
}

```

---

### File 28: `src/utils/aiService.ts`
*Path: `src/utils/aiService.ts` | Size: 13240 bytes | Gemma 4 & Gemini AI Integration & Dual API Caller*

```typescript
import { GoogleGenAI } from '@google/genai';
import type { OIMLTestReport, WeighingTestRow, EccentricityPoint } from '../types/oiml';

export interface AIModelOption {
  id: string;
  name: string;
  family: 'gemma' | 'gemini';
  description: string;
  recommended?: boolean;
}

export const AVAILABLE_MODELS: AIModelOption[] = [
  {
    id: 'gemma-4-31b-it',
    name: 'Gemma 4 (31B Dense)',
    family: 'gemma',
    description: 'High-precision open model for complex metrological analysis and clause evaluation.',
    recommended: true,
  },
  {
    id: 'gemma-4-26b-a4b-it',
    name: 'Gemma 4 (26B/4B MoE)',
    family: 'gemma',
    description: 'Ultra-fast mixture-of-experts model optimized for instant report reviews and audits.',
  },
  {
    id: 'gemini-3.8-flash',
    name: 'Gemini 3.8 Flash',
    family: 'gemini',
    description: 'Balanced multimodal model for rapid type evaluation workflows and remarks drafting.',
  },
  {
    id: 'gemini-3.5-flash-lite',
    name: 'Gemini 3.5 Flash-Lite',
    family: 'gemini',
    description: 'Lightweight, high-throughput model for instantaneous quick checks.',
  },
];

const STORAGE_KEY_API_KEY = 'oiml_gemma_api_key';
const STORAGE_KEY_MODEL = 'oiml_gemma_selected_model';

/**
 * Retrieve saved API key from localStorage or Vite environment variable
 */
export function getStoredApiKey(): string {
  try {
    const saved = localStorage.getItem(STORAGE_KEY_API_KEY);
    if (saved && saved.trim()) return saved.trim();
  } catch {
    // Ignore localStorage errors
  }
  // Check env variable fallback
  const envKey = (import.meta as any).env?.VITE_GEMMA_API_KEY || (import.meta as any).env?.VITE_GEMINI_API_KEY;
  return envKey ? String(envKey).trim() : '';
}

/**
 * Persist API key to browser localStorage
 */
export function setStoredApiKey(key: string): void {
  try {
    if (key.trim()) {
      localStorage.setItem(STORAGE_KEY_API_KEY, key.trim());
    } else {
      localStorage.removeItem(STORAGE_KEY_API_KEY);
    }
  } catch (err) {
    console.error('Failed to save API key to localStorage', err);
  }
}

/**
 * Retrieve saved model selection or default to Gemma 4
 */
export function getStoredModel(): string {
  try {
    const saved = localStorage.getItem(STORAGE_KEY_MODEL);
    if (saved && AVAILABLE_MODELS.some((m) => m.id === saved)) {
      return saved;
    }
  } catch {
    // fallback
  }
  return 'gemma-4-31b-it';
}

/**
 * Persist chosen model
 */
export function setStoredModel(modelId: string): void {
  try {
    localStorage.setItem(STORAGE_KEY_MODEL, modelId);
  } catch (err) {
    console.error('Failed to save model to localStorage', err);
  }
}

/**
 * Low-level execution helper supporting both @google/genai and direct REST fallback
 */
async function callGemmaApi(prompt: string, apiKey?: string, modelId?: string): Promise<string> {
  const activeKey = apiKey?.trim() || getStoredApiKey();
  const activeModel = modelId || getStoredModel();

  if (!activeKey) {
    throw new Error('Gemma 4 API key is not configured. Please open AI Settings and enter your key.');
  }

  // 1. First attempt: Official @google/genai SDK
  try {
    const client = new GoogleGenAI({ apiKey: activeKey });
    const response = await client.models.generateContent({
      model: activeModel,
      contents: prompt,
    });

    const text = response.text;
    if (text && text.trim()) {
      return text.trim();
    }
  } catch (sdkError: any) {
    console.warn('@google/genai call failed or encountered browser constraint, trying direct REST endpoint...', sdkError);
  }

  // 2. Fallback: Direct Google Generative Language REST API endpoint
  const url = `https://generativelanguage.googleapis.com/v1beta/models/${encodeURIComponent(
    activeModel
  )}:generateContent?key=${encodeURIComponent(activeKey)}`;

  const res = await fetch(url, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
    },
    body: JSON.stringify({
      contents: [
        {
          parts: [{ text: prompt }],
        },
      ],
    }),
  });

  if (!res.ok) {
    const errorData = await res.json().catch(() => ({}));
    const message = errorData?.error?.message || `HTTP ${res.status}: ${res.statusText}`;
    throw new Error(`Gemma API Error (${res.status}): ${message}`);
  }

  const data = await res.json();
  const candidate = data.candidates?.[0];
  const parts = candidate?.content?.parts;
  if (parts && parts.length > 0 && parts[0].text) {
    return parts[0].text.trim();
  }

  throw new Error('Received empty response from Gemma API. Check your model choice or quota.');
}

/**
 * Test the API key with a small ping prompt
 */
export async function testGemmaConnection(apiKey: string, modelId: string): Promise<{ success: boolean; message: string; modelUsed: string }> {
  try {
    const testPrompt = 'Respond with exactly: "Gemma 4 Metrology AI Connected Successfully"';
    const result = await callGemmaApi(testPrompt, apiKey, modelId);
    return {
      success: true,
      message: result,
      modelUsed: modelId,
    };
  } catch (err: any) {
    return {
      success: false,
      message: err.message || 'Connection test failed',
      modelUsed: modelId,
    };
  }
}

/**
 * Construct compact summary text of a test report for prompt context
 */
function buildReportContext(report: OIMLTestReport): string {
  const { instrument, environment, weighingTest, repeatabilityTest, eccentricityTest, discriminationTest, tareTest, zeroTest } = report;

  const weighingPoints = weighingTest.rows.slice(0, 10).map((row: WeighingTestRow) => ({
    load: `${row.nominalLoad} ${instrument.unit}`,
    direction: row.direction,
    indication: row.indication,
    correctedError: row.correctedError,
    mpe: row.mpe,
    passed: row.passed,
  }));

  const cornerPoints = eccentricityTest.points.map((pt: EccentricityPoint) => ({
    position: pt.positionLabel,
    indication: pt.indication,
    correctedError: pt.correctedError,
    mpe: pt.mpe,
    passed: pt.passed,
  }));

  return `
INSTRUMENT DETAILS:
- Model/Designation: ${instrument.model} (${instrument.manufacturer})
- Report Number: ${instrument.reportNumber}
- Accuracy Class: Class ${instrument.accuracyClass}
- Capacity (Max): ${instrument.maxCapacity} ${instrument.unit}
- Min Capacity: ${instrument.minCapacity} ${instrument.unit}
- Verification Interval (e): ${instrument.verificationScaleInterval} ${instrument.unit}
- Scale Interval (d): ${instrument.actualScaleInterval} ${instrument.unit}
- Resolution Ratio n = Max/e: ${instrument.scaleIntervalCount} divisions
- Device Type: ${instrument.deviceType}
- Platform Size: ${instrument.platformDimensions}
- Load Cells: ${instrument.loadCellCount}x ${instrument.loadCellModel} (Cert: ${instrument.loadCellCertificateNo})

ENVIRONMENTAL BASELINE:
- Lab: ${environment.laboratoryName}
- Temperature: ${environment.ambientTempStart}°C to ${environment.ambientTempEnd}°C
- Standard Weights Class: ${environment.standardWeightsClass} (Cert: ${environment.standardWeightsCertNo})

METROLOGICAL COMPLIANCE SUMMARY:
- Overall Verdict: ${report.overallVerdict}
- Weighing Test: ${weighingTest.passed ? 'PASS' : 'FAIL'} (Max Corrected Error: ${weighingTest.maxCorrectedError} ${instrument.unit}, Max MPE Ratio: ${(weighingTest.maxMpeRatio * 100).toFixed(1)}%)
- Repeatability Test: ${repeatabilityTest.passed ? 'PASS' : 'FAIL'} (Half-Max Diff: ${repeatabilityTest.halfMaxDiff} ${instrument.unit}, Max Diff: ${repeatabilityTest.maxDiff} ${instrument.unit})
- Eccentricity Test: ${eccentricityTest.passed ? 'PASS' : 'FAIL'} (Max Corner Spread: ${eccentricityTest.maxSpread} ${instrument.unit}, Load: ${eccentricityTest.testLoad} ${instrument.unit})
- Discrimination Test: ${discriminationTest.passed ? 'PASS' : 'FAIL'}
- Tare Balancing Test: ${tareTest.passed ? 'PASS' : 'FAIL'}
- Zero-Setting & Tracking: ${zeroTest.passed ? 'PASS' : 'FAIL'}

KEY WEIGHING TEST DATA POINTS:
${JSON.stringify(weighingPoints, null, 2)}

CORNER ECCENTRICITY DATA POINTS:
${JSON.stringify(cornerPoints, null, 2)}
`.trim();
}

/**
 * AI Feature 1: Automatically draft official metrology evaluator remarks as per OIML R 76-1
 */
export async function generateEvaluatorRemarksWithGemma(
  report: OIMLTestReport,
  apiKey?: string,
  modelId?: string
): Promise<string> {
  const context = buildReportContext(report);
  const prompt = `
You are a Senior Legal Metrology Officer and Lead Type-Evaluation Metrologist for the Directorate of Legal Metrology, Ministry of Consumer Affairs, India.
Your task is to review the following Non-Automatic Weighing Instrument (NAWI) test observations evaluated strictly against OIML Recommendation R 76-1:2006 and the Legal Metrology (General) Rules, 2011.

${context}

INSTRUCTIONS:
1. Provide a professional, authoritative "Evaluator Technical Findings & Verdict Remarks" section suitable for inclusion in an official OIML R 76-2 Type Approval Test Report.
2. Structure your review into 4 clearly demarcated sections:
   - **Executive Metrological Assessment**: Summary of instrument compliance, verification scale interval (e), and resolution ratio (n).
   - **Error Analysis & Tolerance Performance**: Evaluation of weighing curve against Table 6 Maximum Permissible Errors (MPE) [±0.5e, ±1.0e, ±1.5e], hysteresis, repeatability range (Clause 3.6.1), and eccentricity response (Clause 3.6.2).
   - **Non-Conformities & Anomaly Diagnosis** (if any points failed or were near boundary): State exact clauses violated or mechanical/environmental factors (e.g. corner leveling, draft, load cell hysteresis). If all passed, confirm flawless compliance across full range.
   - **Formal Certification Recommendation**: Explicit recommendation to either Grant Type Approval Certificate, Require Corrective Recalibration, or Reject.
3. Keep the tone rigorous, technical, and objective. Use standard OIML terminology ($P = I + 0.5e - \\Delta L$, $E = P - L$, $E_c = E - E_0$, MPE Table 6, Clause 3.5, Clause 3.6).
4. Do not include extraneous markdown preamble or conversational chatter. Output strictly the formal evaluator remarks.
`.trim();

  return await callGemmaApi(prompt, apiKey, modelId);
}

/**
 * AI Feature 2: Metrological Failure Diagnosis & Mechanical Remediation Advice
 */
export async function diagnoseInstrumentFailureWithGemma(
  report: OIMLTestReport,
  apiKey?: string,
  modelId?: string
): Promise<string> {
  const context = buildReportContext(report);
  const prompt = `
You are an expert weighing system mechanical & instrumentation engineer advising a manufacturer whose Non-Automatic Weighing Instrument (NAWI) underwent type evaluation as per OIML R 76-1.

${context}

TASK:
Analyze the test findings, identify any failures or vulnerabilities (e.g. corner eccentricity imbalance, hysteresis between increasing/decreasing loads, discrimination sluggishness, zero drift), and provide:
1. **Root Cause Analysis**: Mechanical, electrical, strain-gauge, or environmental causes for the observed errors.
2. **Physical Remediation Steps**: Concrete hardware adjustments (e.g., corner trimming resistors, leveling shims, flexure pivot tightening, load cell cable shielding, thermal stabilization).
3. **Re-testing Guidance**: Specific OIML test sequences to repeat after corrective adjustments.

Keep it direct, actionable, and structured with bullet points.
`.trim();

  return await callGemmaApi(prompt, apiKey, modelId);
}

/**
 * AI Feature 3: Interactive Metrology Chat Copilot
 */
export interface ChatMessage {
  role: 'user' | 'assistant';
  content: string;
}

export async function chatWithGemmaMetrology(
  messages: ChatMessage[],
  currentReport?: OIMLTestReport,
  apiKey?: string,
  modelId?: string
): Promise<string> {
  let contextSnippet = '';
  if (currentReport) {
    contextSnippet = `\nCURRENT ACTIVE INSTRUMENT IN WORKBENCH:\n${buildReportContext(currentReport)}\n`;
  }

  const systemPrompt = `
You are the "OIML R 76 Metrology AI Copilot" powered by Gemma 4.
You are embedded inside the NAWI Test Report Generator Application for the Directorate of Legal Metrology, Ministry of Consumer Affairs, Government of India.
You have deep expertise in:
- OIML Recommendation R 76-1:2006 (Metrological and technical requirements — Non-automatic weighing instruments)
- OIML Recommendation R 76-2:2007 (Pattern evaluation report)
- The Legal Metrology Act, 2009 and Legal Metrology (General) Rules, 2011
- Accuracy classes: Class I (Special), Class II (High), Class III (Medium), Class IIII (Ordinary)
- Formulas: $P = I + 0.5e - \\Delta L$, $E = P - L$, $E_c = E - E_0$
- Maximum Permissible Errors (MPE Table 6: initial verification vs in-service)
- Tests: Weighing, Repeatability (Clause 3.6.1), Eccentricity (Clause 3.6.2), Discrimination (Clause 3.8), Zero/Tare (Clause 4.5/4.6).

${contextSnippet}

Answer the user's questions authoritatively, citing relevant OIML clauses and providing step-by-step guidance. Be concise, precise, and practical.
`.trim();

  const conversationHistory = messages
    .map((m) => `${m.role === 'user' ? 'User' : 'Assistant'}: ${m.content}`)
    .join('\n\n');

  const fullPrompt = `${systemPrompt}\n\nCONVERSATION:\n${conversationHistory}\n\nAssistant:`;

  return await callGemmaApi(fullPrompt, apiKey, modelId);
}

```

---

### File 29: `src/utils/docxExport.ts`
*Path: `src/utils/docxExport.ts` | Size: 7007 bytes | Word (.docx) Report Generator with Tables*

```typescript
import {
  Document,
  Packer,
  Paragraph,
  Table,
  TableCell,
  TableRow,
  TextRun,
  WidthType,
  AlignmentType,
  BorderStyle,
  HeadingLevel,
} from 'docx';
import saveAs from 'file-saver';
import type { OIMLTestReport } from '../types/oiml';

export async function exportReportToDocx(report: OIMLTestReport): Promise<void> {
  const { instrument, environment, weighingTest } = report;

  const tableBorder = {
    top: { style: BorderStyle.SINGLE, size: 1, color: 'CCCCCC' },
    bottom: { style: BorderStyle.SINGLE, size: 1, color: 'CCCCCC' },
    left: { style: BorderStyle.SINGLE, size: 1, color: 'CCCCCC' },
    right: { style: BorderStyle.SINGLE, size: 1, color: 'CCCCCC' },
  };

  const headerCell = (text: string, widthPercent: number) =>
    new TableCell({
      width: { size: widthPercent, type: WidthType.PERCENTAGE },
      shading: { fill: '0F2B48' },
      children: [
        new Paragraph({
          children: [new TextRun({ text, bold: true, color: 'FFFFFF', size: 18 })],
          alignment: AlignmentType.CENTER,
        }),
      ],
    });

  const dataCell = (text: string, widthPercent: number, bold: boolean = false, align: (typeof AlignmentType)[keyof typeof AlignmentType] = AlignmentType.LEFT) =>
    new TableCell({
      width: { size: widthPercent, type: WidthType.PERCENTAGE },
      borders: tableBorder,
      children: [
        new Paragraph({
          children: [new TextRun({ text, bold, size: 18, color: '1E293B' })],
          alignment: align,
        }),
      ],
    });

  // Specifications Table
  const specRows = [
    new TableRow({
      children: [
        dataCell('Manufacturer', 25, true),
        dataCell(instrument.manufacturer, 25),
        dataCell('Accuracy Class', 25, true),
        dataCell(`Class ${instrument.accuracyClass}`, 25),
      ],
    }),
    new TableRow({
      children: [
        dataCell('Applicant', 25, true),
        dataCell(instrument.applicant, 25),
        dataCell('Max Capacity (Max)', 25, true),
        dataCell(`${instrument.maxCapacity} ${instrument.unit}`, 25),
      ],
    }),
    new TableRow({
      children: [
        dataCell('Model / Type', 25, true),
        dataCell(instrument.model, 25),
        dataCell('Min Capacity (Min)', 25, true),
        dataCell(`${instrument.minCapacity} ${instrument.unit}`, 25),
      ],
    }),
    new TableRow({
      children: [
        dataCell('Serial Number', 25, true),
        dataCell(instrument.serialNumber, 25),
        dataCell('Verif. Interval (e)', 25, true),
        dataCell(`${instrument.verificationScaleInterval} ${instrument.unit}`, 25),
      ],
    }),
    new TableRow({
      children: [
        dataCell('Device Type', 25, true),
        dataCell(instrument.deviceType, 25),
        dataCell('Scale Intervals (n)', 25, true),
        dataCell(`${instrument.scaleIntervalCount}`, 25),
      ],
    }),
  ];

  // Weighing Test Table
  const weighingTableRows = [
    new TableRow({
      children: [
        headerCell('#', 5),
        headerCell('Dir', 10),
        headerCell(`Load (${instrument.unit})`, 15),
        headerCell(`Indication (${instrument.unit})`, 15),
        headerCell(`True P (${instrument.unit})`, 15),
        headerCell(`Ec (${instrument.unit})`, 15),
        headerCell(`MPE (±)`, 15),
        headerCell('Status', 10),
      ],
    }),
    ...weighingTest.rows.map(
      (r) =>
        new TableRow({
          children: [
            dataCell(r.step.toString(), 5, false, AlignmentType.CENTER),
            dataCell(r.direction === 'increasing' ? 'Inc' : 'Dec', 10, false, AlignmentType.CENTER),
            dataCell(r.nominalLoad.toString(), 15, false, AlignmentType.RIGHT),
            dataCell(r.indication.toString(), 15, false, AlignmentType.RIGHT),
            dataCell(r.trueIndication.toString(), 15, false, AlignmentType.RIGHT),
            dataCell(r.correctedError.toString(), 15, false, AlignmentType.RIGHT),
            dataCell(`±${r.mpe}`, 15, false, AlignmentType.CENTER),
            dataCell(r.passed ? 'PASS' : 'FAIL', 10, true, AlignmentType.CENTER),
          ],
        })
    ),
  ];

  const doc = new Document({
    sections: [
      {
        properties: {},
        children: [
          new Paragraph({
            text: 'GOVERNMENT OF INDIA',
            heading: HeadingLevel.HEADING_1,
            alignment: AlignmentType.CENTER,
          }),
          new Paragraph({
            text: 'MINISTRY OF CONSUMER AFFAIRS, FOOD & PUBLIC DISTRIBUTION',
            alignment: AlignmentType.CENTER,
          }),
          new Paragraph({
            text: 'DIRECTORATE OF LEGAL METROLOGY - OIML R 76-2 TEST REPORT',
            alignment: AlignmentType.CENTER,
          }),
          new Paragraph({ text: '' }),

          new Paragraph({
            children: [
              new TextRun({ text: `Report Number: ${instrument.reportNumber}`, bold: true }),
              new TextRun({ text: `   |   Application Ref: ${instrument.applicationNumber}` }),
              new TextRun({ text: `   |   Date: ${environment.testDate}` }),
            ],
          }),
          new Paragraph({
            children: [
              new TextRun({ text: 'Overall Verdict: ', bold: true }),
              new TextRun({
                text: `${report.overallVerdict} (${report.status.toUpperCase()})`,
                bold: true,
                color: report.overallVerdict === 'COMPLIANT' ? '109543' : 'DC2626',
              }),
            ],
          }),
          new Paragraph({ text: '' }),

          new Paragraph({
            text: '1. Instrument Specifications & Metrological Characteristics',
            heading: HeadingLevel.HEADING_2,
          }),
          new Table({
            rows: specRows,
            width: { size: 100, type: WidthType.PERCENTAGE },
          }),
          new Paragraph({ text: '' }),

          new Paragraph({
            text: '2. Weighing Performance Test Observations (Annex A.4.4)',
            heading: HeadingLevel.HEADING_2,
          }),
          new Table({
            rows: weighingTableRows,
            width: { size: 100, type: WidthType.PERCENTAGE },
          }),
          new Paragraph({ text: '' }),

          new Paragraph({
            text: '3. Evaluator Remarks & Official Certification',
            heading: HeadingLevel.HEADING_2,
          }),
          new Paragraph({
            text: `Evaluator Findings: ${report.evaluatorRemarks}`,
          }),
          new Paragraph({
            text: `Approver Remarks: ${report.approverRemarks || 'N/A'}`,
          }),
          new Paragraph({ text: '' }),
          new Paragraph({
            children: [
              new TextRun({ text: `Digital Verification Token: ${report.verificationHash}`, italics: true, color: '64748B' }),
            ],
          }),
        ],
      },
    ],
  });

  const blob = await Packer.toBlob(doc);
  const filename = `${instrument.reportNumber.replace(/[\/\\:]/g, '_')}_OIML_R76_Report.docx`;
  saveAs(blob, filename);
}

```

---

### File 30: `src/utils/metrologyEngine.ts`
*Path: `src/utils/metrologyEngine.ts` | Size: 15205 bytes | Metrological Calculation Engine (MPE Table 6, True Indication, Ec, n)*

```typescript
import type {
  AccuracyClass,
  VerificationType,
  WeighingTestRow,
  WeighingTestResult,
  RepeatabilityTestResult,
  EccentricityTestResult,
  DiscriminationTestResult,
  ZeroTestResult,
  TareTestResult,
  TiltingTestResult,
  TemperatureTestResult,
  OIMLTestReport,
} from '../types/oiml';

/**
 * Calculates Maximum Permissible Error (MPE) according to OIML R 76-1:2006, Table 6.
 * @param load Nominal load applied
 * @param e Verification scale interval
 * @param accuracyClass Class I, II, III, or IIII
 * @param verificationType 'initial', 'subsequent', or 'in_service'
 * @returns MPE in the same units as e (positive value representing ±MPE)
 */
export function calculateMPE(
  load: number,
  e: number,
  accuracyClass: AccuracyClass,
  verificationType: VerificationType = 'initial'
): number {
  if (e <= 0) return 0;
  const m = Math.abs(load) / e; // load in units of e

  let baseMpeMultiplier: number;

  switch (accuracyClass) {
    case 'I':
      if (m <= 50000) {
        baseMpeMultiplier = 0.5;
      } else if (m <= 200000) {
        baseMpeMultiplier = 1.0;
      } else {
        baseMpeMultiplier = 1.5;
      }
      break;

    case 'II':
      if (m <= 5000) {
        baseMpeMultiplier = 0.5;
      } else if (m <= 20000) {
        baseMpeMultiplier = 1.0;
      } else {
        baseMpeMultiplier = 1.5;
      }
      break;

    case 'III':
      if (m <= 500) {
        baseMpeMultiplier = 0.5;
      } else if (m <= 2000) {
        baseMpeMultiplier = 1.0;
      } else {
        baseMpeMultiplier = 1.5;
      }
      break;

    case 'IIII':
      if (m <= 50) {
        baseMpeMultiplier = 0.5;
      } else if (m <= 200) {
        baseMpeMultiplier = 1.0;
      } else {
        baseMpeMultiplier = 1.5;
      }
      break;

    default:
      baseMpeMultiplier = 1.0;
  }

  // In-service MPE is 2x the initial verification MPE as per Clause 3.5.2
  const factor = verificationType === 'in_service' ? 2 : 1;
  return roundMetrology(baseMpeMultiplier * factor * e, 6);
}

/**
 * Rounds numbers cleanly avoiding IEEE 754 floating point artifacts
 */
export function roundMetrology(val: number, decimals: number = 4): number {
  const multiplier = Math.pow(10, decimals);
  return Math.round((val + Number.EPSILON) * multiplier) / multiplier;
}

/**
 * Calculates turning-point true indication before rounding:
 * P = I + 0.5*e - deltaL  (Annex A.4.4.3)
 */
export function calculateTrueIndication(indication: number, deltaL: number, e: number): number {
  return roundMetrology(indication + 0.5 * e - deltaL, 6);
}

/**
 * Calculates intrinsic error before rounding:
 * E = P - L
 */
export function calculateIntrinsicError(trueIndication: number, nominalLoad: number): number {
  return roundMetrology(trueIndication - nominalLoad, 6);
}

/**
 * Calculates corrected error:
 * Ec = E - E0
 */
export function calculateCorrectedError(intrinsicError: number, zeroErrorE0: number): number {
  return roundMetrology(intrinsicError - zeroErrorE0, 6);
}

/**
 * Validates number of scale intervals (n) against OIML R 76-1 Table 3 limits.
 */
export function validateScaleIntervalCount(
  accuracyClass: AccuracyClass,
  e: number,
  n: number
): { valid: boolean; minN: number; maxN: number; reason?: string } {
  let minN = 100;
  let maxN = 100000;

  switch (accuracyClass) {
    case 'I':
      minN = 50000;
      maxN = 10000000; // practically unlimited
      break;
    case 'II':
      minN = e < 0.1 ? 100 : 5000;
      maxN = 100000;
      break;
    case 'III':
      minN = e < 5 ? 100 : 500;
      maxN = 10000;
      break;
    case 'IIII':
      minN = 100;
      maxN = 1000;
      break;
  }

  if (n < minN) {
    return {
      valid: false,
      minN,
      maxN,
      reason: `Scale interval count n = ${n} is below minimum requirement of ${minN} for Class ${accuracyClass}`,
    };
  }
  if (n > maxN) {
    return {
      valid: false,
      minN,
      maxN,
      reason: `Scale interval count n = ${n} exceeds maximum allowed limit of ${maxN} for Class ${accuracyClass}`,
    };
  }

  return { valid: true, minN, maxN };
}

/**
 * Recalculates and evaluates the entire Weighing Performance Test.
 */
export function evaluateWeighingTest(
  rows: WeighingTestRow[],
  e: number,
  accuracyClass: AccuracyClass,
  verificationType: VerificationType,
  zeroErrorStart: number,
  zeroErrorEnd: number
): WeighingTestResult {
  let maxEc = 0;
  let maxMpeRatio = 0;
  let allRowsPassed = true;

  const evaluatedRows: WeighingTestRow[] = rows.map((row) => {
    const P = calculateTrueIndication(row.indication, row.deltaL, e);
    const E = calculateIntrinsicError(P, row.nominalLoad);
    const Ec = calculateCorrectedError(E, zeroErrorStart);
    const mpe = calculateMPE(row.nominalLoad, e, accuracyClass, verificationType);
    const passed = Math.abs(Ec) <= mpe + 0.000001; // allowance for rounding

    if (!passed) allRowsPassed = false;
    const absEc = Math.abs(Ec);
    if (absEc > maxEc) maxEc = absEc;
    const ratio = mpe > 0 ? absEc / mpe : 0;
    if (ratio > maxMpeRatio) maxMpeRatio = ratio;

    return {
      ...row,
      trueIndication: P,
      error: E,
      correctedError: Ec,
      mpe: mpe,
      passed: passed,
    };
  });

  // Check hysteresis: difference between loading and unloading at same nominal load <= |MPE|
  let hysteresisMax = 0;
  let hysteresisPassed = true;

  const increasingMap = new Map<number, number>();
  evaluatedRows
    .filter((r) => r.direction === 'increasing')
    .forEach((r) => increasingMap.set(r.nominalLoad, r.correctedError));

  evaluatedRows
    .filter((r) => r.direction === 'decreasing')
    .forEach((r) => {
      const incEc = increasingMap.get(r.nominalLoad);
      if (incEc !== undefined) {
        const diff = Math.abs(r.correctedError - incEc);
        if (diff > hysteresisMax) hysteresisMax = diff;
        if (diff > r.mpe + 0.000001) hysteresisPassed = false;
      }
    });

  const passed = allRowsPassed && hysteresisPassed;

  return {
    zeroErrorStart,
    zeroErrorEnd,
    rows: evaluatedRows,
    maxCorrectedError: roundMetrology(maxEc, 6),
    maxMpeRatio: roundMetrology(maxMpeRatio, 3),
    hysteresisMax: roundMetrology(hysteresisMax, 6),
    hysteresisPassed,
    passed,
  };
}

/**
 * Evaluates Repeatability Test runs at 50% Max and 100% Max.
 */
export function evaluateRepeatabilityTest(
  test: RepeatabilityTestResult,
  e: number,
  accuracyClass: AccuracyClass,
  verificationType: VerificationType
): RepeatabilityTestResult {
  const halfMpe = calculateMPE(test.halfMaxLoad, e, accuracyClass, verificationType);
  const maxMpe = calculateMPE(test.maxLoad, e, accuracyClass, verificationType);

  const halfIndications = test.runsHalfMax.map((r) => r.indication);
  const maxIndications = test.runsMax.map((r) => r.indication);

  const halfMaxDiff =
    halfIndications.length > 0
      ? roundMetrology(Math.max(...halfIndications) - Math.min(...halfIndications), 6)
      : 0;
  const maxDiff =
    maxIndications.length > 0
      ? roundMetrology(Math.max(...maxIndications) - Math.min(...maxIndications), 6)
      : 0;

  const halfMaxPassed = halfMaxDiff <= halfMpe + 0.000001;
  const maxPassed = maxDiff <= maxMpe + 0.000001;

  return {
    ...test,
    halfMaxDiff,
    halfMaxMpe: halfMpe,
    halfMaxPassed,
    maxDiff,
    maxMpe,
    maxPassed,
    passed: halfMaxPassed && maxPassed,
  };
}

/**
 * Evaluates Eccentricity / Corner Loading test.
 */
export function evaluateEccentricityTest(
  test: EccentricityTestResult,
  e: number,
  accuracyClass: AccuracyClass,
  verificationType: VerificationType,
  zeroErrorE0: number = 0
): EccentricityTestResult {
  const mpe = calculateMPE(test.testLoad, e, accuracyClass, verificationType);
  let allPointsPassed = true;

  const evaluatedPoints = test.points.map((pt) => {
    const P = calculateTrueIndication(pt.indication, pt.deltaL, e);
    const E = calculateIntrinsicError(P, test.testLoad);
    const Ec = calculateCorrectedError(E, zeroErrorE0);
    const passed = Math.abs(Ec) <= mpe + 0.000001;
    if (!passed) allPointsPassed = false;

    return {
      ...pt,
      trueIndication: P,
      error: E,
      correctedError: Ec,
      mpe,
      passed,
    };
  });

  const ecValues = evaluatedPoints.map((p) => p.correctedError);
  const maxSpread =
    ecValues.length > 0 ? roundMetrology(Math.max(...ecValues) - Math.min(...ecValues), 6) : 0;
  const spreadPassed = maxSpread <= mpe + 0.000001;

  return {
    ...test,
    points: evaluatedPoints,
    maxSpread,
    maxMpe: mpe,
    spreadPassed,
    passed: allPointsPassed && spreadPassed,
  };
}

/**
 * Evaluates Discrimination check (1.4d additional load must cause >= 1d change).
 */
export function evaluateDiscriminationTest(test: DiscriminationTestResult): DiscriminationTestResult {
  let allPassed = true;
  const checks = test.checks.map((chk) => {
    const change = roundMetrology(chk.newIndication - chk.baseIndication, 6);
    const passed = change >= chk.minimumRequiredChange - 0.000001;
    if (!passed) allPassed = false;
    return {
      ...chk,
      indicationChange: change,
      passed,
    };
  });

  return {
    checks,
    passed: allPassed,
  };
}

/**
 * Evaluates Zero-setting and Zero-tracking tests.
 */
export function evaluateZeroTest(test: ZeroTestResult, e: number, d: number): ZeroTestResult {
  const maxPermissibleE0 = roundMetrology(0.25 * e, 6);
  const maxZeroTrackingRate = roundMetrology(0.5 * d, 6);

  const zeroSettingPassed = Math.abs(test.zeroErrorE0) <= maxPermissibleE0 + 0.000001;
  const zeroTrackingPassed = test.zeroTrackingRate <= maxZeroTrackingRate + 0.000001;

  return {
    ...test,
    maxPermissibleE0,
    maxZeroTrackingRate,
    zeroSettingPassed,
    zeroTrackingPassed,
    passed: zeroSettingPassed && zeroTrackingPassed,
  };
}

/**
 * Evaluates Tare test.
 */
export function evaluateTareTest(
  test: TareTestResult,
  e: number,
  accuracyClass: AccuracyClass,
  verificationType: VerificationType
): TareTestResult {
  const P = calculateTrueIndication(test.indicatedNet, test.deltaL, e);
  const netError = calculateIntrinsicError(P, test.netTestLoad);
  const netMpe = calculateMPE(test.netTestLoad, e, accuracyClass, verificationType);
  const maxPermissibleTareError = roundMetrology(0.25 * e, 6);

  const tareBalancingPassed = Math.abs(test.tareBalancingError) <= maxPermissibleTareError + 0.000001;
  const netWeighingPassed = Math.abs(netError) <= netMpe + 0.000001;

  return {
    ...test,
    trueNet: P,
    netError,
    netMpe,
    maxPermissibleTareError,
    passed: tareBalancingPassed && netWeighingPassed,
  };
}

/**
 * Evaluates Tilting test for mobile/portable instruments.
 */
export function evaluateTiltingTest(test: TiltingTestResult, e: number): TiltingTestResult {
  if (!test.applicable) {
    return { ...test, passed: true };
  }
  const zeroShift = roundMetrology(Math.abs(test.zeroIndicationTilted - test.zeroIndicationNoTilt), 6);
  const maxPermissibleShift = roundMetrology(1.0 * e, 6);
  const passed = zeroShift <= maxPermissibleShift + 0.000001;

  return {
    ...test,
    zeroShift,
    maxPermissibleShift,
    passed,
  };
}

/**
 * Evaluates Temperature test points.
 */
export function evaluateTemperatureTest(test: TemperatureTestResult, e: number): TemperatureTestResult {
  if (!test.applicable || test.points.length === 0) {
    return { ...test, passed: true };
  }

  const maxPermissibleShiftPer5C = roundMetrology(1.0 * e, 6);
  let allPassed = true;

  const points = test.points.map((pt) => {
    const passed = pt.zeroShiftPer5C <= maxPermissibleShiftPer5C + 0.000001;
    if (!passed) allPassed = false;
    return {
      ...pt,
      maxPermissibleShiftPer5C,
      passed,
    };
  });

  return {
    ...test,
    points,
    passed: allPassed,
  };
}

/**
 * Computes a tamper-evident digital verification checksum for the report.
 */
export function generateVerificationHash(report: Partial<OIMLTestReport>): string {
  const content = JSON.stringify({
    reportNumber: report.instrument?.reportNumber,
    serialNumber: report.instrument?.serialNumber,
    model: report.instrument?.model,
    class: report.instrument?.accuracyClass,
    max: report.instrument?.maxCapacity,
    e: report.instrument?.verificationScaleInterval,
    weighingPassed: report.weighingTest?.passed,
    maxEc: report.weighingTest?.maxCorrectedError,
    repeatabilityPassed: report.repeatabilityTest?.passed,
    eccentricityPassed: report.eccentricityTest?.passed,
    discriminationPassed: report.discriminationTest?.passed,
    overallVerdict: report.overallVerdict,
    date: report.environment?.testDate,
  });

  let hash = 0;
  for (let i = 0; i < content.length; i++) {
    const char = content.charCodeAt(i);
    hash = (hash << 5) - hash + char;
    hash |= 0;
  }

  const hex = Math.abs(hash).toString(16).padStart(8, '0');
  const timestamp = Date.now().toString(16).slice(-4);
  return `OIML-VERIFY-${hex.toUpperCase()}-${timestamp.toUpperCase()}`;
}

/**
 * Re-evaluates all tests on a report and updates overall verdict.
 */
export function evaluateEntireReport(report: OIMLTestReport): OIMLTestReport {
  const { instrument } = report;
  const e = instrument.verificationScaleInterval;
  const d = instrument.actualScaleInterval;
  const cls = instrument.accuracyClass;
  const verType = instrument.verificationType;

  // 1. Weighing test
  const weighing = evaluateWeighingTest(
    report.weighingTest.rows,
    e,
    cls,
    verType,
    report.weighingTest.zeroErrorStart,
    report.weighingTest.zeroErrorEnd
  );

  // 2. Repeatability
  const repeatability = evaluateRepeatabilityTest(report.repeatabilityTest, e, cls, verType);

  // 3. Eccentricity
  const eccentricity = evaluateEccentricityTest(
    report.eccentricityTest,
    e,
    cls,
    verType,
    report.weighingTest.zeroErrorStart
  );

  // 4. Discrimination
  const discrimination = evaluateDiscriminationTest(report.discriminationTest);

  // 5. Zero
  const zero = evaluateZeroTest(report.zeroTest, e, d);

  // 6. Tare
  const tare = evaluateTareTest(report.tareTest, e, cls, verType);

  // 7. Tilting
  const tilting = evaluateTiltingTest(report.tiltingTest, e);

  // 8. Temperature
  const temperature = evaluateTemperatureTest(report.temperatureTest, e);

  // Interval check
  const intervalCheck = validateScaleIntervalCount(cls, e, instrument.scaleIntervalCount);

  const overallPassed =
    weighing.passed &&
    repeatability.passed &&
    eccentricity.passed &&
    discrimination.passed &&
    zero.passed &&
    tare.passed &&
    tilting.passed &&
    temperature.passed &&
    intervalCheck.valid;

  const overallVerdict: 'COMPLIANT' | 'NON_COMPLIANT' = overallPassed ? 'COMPLIANT' : 'NON_COMPLIANT';

  const updated: OIMLTestReport = {
    ...report,
    updatedAt: new Date().toISOString(),
    weighingTest: weighing,
    repeatabilityTest: repeatability,
    eccentricityTest: eccentricity,
    discriminationTest: discrimination,
    zeroTest: zero,
    tareTest: tare,
    tiltingTest: tilting,
    temperatureTest: temperature,
    overallVerdict,
  };

  updated.verificationHash = generateVerificationHash(updated);

  return updated;
}

```

---

### File 31: `src/utils/pdfExport.ts`
*Path: `src/utils/pdfExport.ts` | Size: 19816 bytes | Multi-page Official OIML R 76-2 PDF Exporter*

```typescript
import jsPDF from 'jspdf';
import autoTable from 'jspdf-autotable';
import type { OIMLTestReport } from '../types/oiml';

export function exportReportToPDF(report: OIMLTestReport): void {
  const doc = new jsPDF({
    orientation: 'portrait',
    unit: 'mm',
    format: 'a4',
  });

  const { instrument, environment, weighingTest, repeatabilityTest, eccentricityTest, discriminationTest, zeroTest, tareTest } = report;

  // Colors
  const primaryNavy: [number, number, number] = [15, 43, 72];
  const slateDark: [number, number, number] = [30, 41, 59];
  const lightBg: [number, number, number] = [248, 250, 252];
  const borderGrey: [number, number, number] = [226, 232, 240];

  // ================= PAGE 1: COVER & SPECIFICATIONS =================
  // Header Banner
  doc.setFillColor(...primaryNavy);
  doc.rect(0, 0, 210, 36, 'F');

  doc.setTextColor(255, 255, 255);
  doc.setFont('helvetica', 'bold');
  doc.setFontSize(14);
  doc.text('GOVERNMENT OF INDIA', 105, 10, { align: 'center' });
  doc.setFontSize(11);
  doc.text('MINISTRY OF CONSUMER AFFAIRS, FOOD & PUBLIC DISTRIBUTION', 105, 16, { align: 'center' });
  doc.setFontSize(9);
  doc.setFont('helvetica', 'normal');
  doc.text('DIRECTORATE OF LEGAL METROLOGY | OIML ISSUING AUTHORITY', 105, 22, { align: 'center' });
  doc.setFontSize(8);
  doc.text('TYPE EVALUATION & PATTERN APPROVAL TEST REPORT (OIML R 76-2:2007)', 105, 28, { align: 'center' });

  // Top info bar
  doc.setFillColor(...lightBg);
  doc.rect(14, 40, 182, 18, 'F');
  doc.setDrawColor(...borderGrey);
  doc.rect(14, 40, 182, 18, 'S');

  doc.setTextColor(...slateDark);
  doc.setFontSize(9);
  doc.setFont('helvetica', 'bold');
  doc.text('Report No:', 18, 47);
  doc.setFont('helvetica', 'normal');
  doc.text(instrument.reportNumber, 38, 47);

  doc.setFont('helvetica', 'bold');
  doc.text('Application Ref:', 18, 54);
  doc.setFont('helvetica', 'normal');
  doc.text(instrument.applicationNumber, 46, 54);

  doc.setFont('helvetica', 'bold');
  doc.text('Date of Test:', 130, 47);
  doc.setFont('helvetica', 'normal');
  doc.text(environment.testDate, 155, 47);

  doc.setFont('helvetica', 'bold');
  doc.text('Status:', 130, 54);
  const isPass = report.overallVerdict === 'COMPLIANT';
  doc.setTextColor(isPass ? 16 : 220, isPass ? 149 : 38, isPass ? 67 : 38);
  doc.setFont('helvetica', 'bold');
  doc.text(`${report.overallVerdict} (${report.status.toUpperCase()})`, 146, 54);

  // Section 1: Instrument Identification
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(11);
  doc.setFont('helvetica', 'bold');
  doc.text('1. Instrument Identification & Technical Characteristics', 14, 66);

  const specData = [
    ['Manufacturer', instrument.manufacturer, 'Accuracy Class', `Class ${instrument.accuracyClass}`],
    ['Applicant', instrument.applicant, 'Max Capacity (Max)', `${instrument.maxCapacity} ${instrument.unit}`],
    ['Model / Type', instrument.model, 'Min Capacity (Min)', `${instrument.minCapacity} ${instrument.unit}`],
    ['Serial Number', instrument.serialNumber, 'Verif. Interval (e)', `${instrument.verificationScaleInterval} ${instrument.unit}`],
    ['Device Type', instrument.deviceType, 'Actual Interval (d)', `${instrument.actualScaleInterval} ${instrument.unit}`],
    ['Year of Make', `${instrument.yearOfManufacture}`, 'Scale Intervals (n)', `${instrument.scaleIntervalCount}`],
    ['Tare Type', `${instrument.tareType} (Max: ${instrument.maxTare} ${instrument.unit})`, 'Zero Setting', `${instrument.zeroSettingType.replace('_', ' ')}`],
    ['Indicator Model', instrument.indicatorModel, 'Load Cell Model', `${instrument.loadCellModel} (${instrument.loadCellCount} unit(s))`],
    ['Platform Size', instrument.platformDimensions, 'Load Cell Cert.', instrument.loadCellCertificateNo],
  ];

  autoTable(doc, {
    startY: 70,
    head: [],
    body: specData,
    theme: 'grid',
    styles: { fontSize: 8, cellPadding: 2, textColor: [30, 41, 59] },
    columnStyles: {
      0: { fontStyle: 'bold', fillColor: [241, 245, 249], cellWidth: 35 },
      1: { cellWidth: 55 },
      2: { fontStyle: 'bold', fillColor: [241, 245, 249], cellWidth: 37 },
      3: { cellWidth: 55 },
    },
    margin: { left: 14, right: 14 },
  });

  // Section 2: Laboratory & Environmental Conditions
  let finalY = (doc as any).lastAutoTable.finalY + 8;
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(11);
  doc.setFont('helvetica', 'bold');
  doc.text('2. Laboratory & Environmental Test Conditions', 14, finalY);

  const envData = [
    ['Testing Laboratory', environment.laboratoryName, 'NABL Accreditation', environment.nablAccreditationNo],
    ['Testing Location', environment.evaluationLocation, 'Issuing Authority', environment.oimlIssuingAuthority],
    ['Ambient Temperature', `${environment.ambientTempStart}°C to ${environment.ambientTempEnd}°C`, 'Relative Humidity', `${environment.relativeHumidity} % RH`],
    ['Barometric Pressure', `${environment.barometricPressure} hPa`, 'Mains Voltage / Freq.', `${environment.mainsVoltage} V AC / ${environment.mainsFrequency} Hz`],
    ['Warm-up Period', `${environment.warmUpTimeMinutes} minutes`, 'Standard Weights', `Class ${environment.standardWeightsClass} (${environment.standardWeightsCertNo})`],
    ['Weights Uncertainty', environment.standardWeightsUncertainty, 'Weights Validity', environment.standardWeightsValidity],
  ];

  autoTable(doc, {
    startY: finalY + 4,
    head: [],
    body: envData,
    theme: 'grid',
    styles: { fontSize: 8, cellPadding: 2, textColor: [30, 41, 59] },
    columnStyles: {
      0: { fontStyle: 'bold', fillColor: [241, 245, 249], cellWidth: 35 },
      1: { cellWidth: 55 },
      2: { fontStyle: 'bold', fillColor: [241, 245, 249], cellWidth: 37 },
      3: { cellWidth: 55 },
    },
    margin: { left: 14, right: 14 },
  });

  // Section 3: Summary of Metrological Conformity
  finalY = (doc as any).lastAutoTable.finalY + 8;
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(11);
  doc.setFont('helvetica', 'bold');
  doc.text('3. Summary of OIML R 76-1 Test Evaluations', 14, finalY);

  const summaryData = [
    ['Weighing Performance Test (Annex A.4.4)', `${weighingTest.rows.length} test points (Inc/Dec)`, `Max |Ec|: ${weighingTest.maxCorrectedError} ${instrument.unit}`, weighingTest.passed ? 'PASSED' : 'FAILED'],
    ['Repeatability Test (Clause 3.6.1)', '3 runs @ 50% Max & 100% Max', `ΔI: ${repeatabilityTest.maxDiff} ${instrument.unit}`, repeatabilityTest.passed ? 'PASSED' : 'FAILED'],
    ['Eccentricity / Corner Loading (Clause 3.6.2)', `${eccentricityTest.points.length} locations @ 1/3 Max`, `Spread: ${eccentricityTest.maxSpread} ${instrument.unit}`, eccentricityTest.passed ? 'PASSED' : 'FAILED'],
    ['Discrimination Test (Clause 3.8)', 'Min, 0.5 Max, Max with 1.4d', 'Visible Change ≥ 1d', discriminationTest.passed ? 'PASSED' : 'FAILED'],
    ['Zero-Setting & Tracking (Clause 4.5)', `E0: ${zeroTest.zeroErrorE0} ${instrument.unit}`, `Limit: ±${zeroTest.maxPermissibleE0} ${instrument.unit}`, zeroTest.passed ? 'PASSED' : 'FAILED'],
    ['Tare Mechanism Test (Clause 4.6)', `Tare: ${tareTest.tareApplied} ${instrument.unit}`, `Net Err: ${tareTest.netError} ${instrument.unit}`, tareTest.passed ? 'PASSED' : 'FAILED'],
  ];

  autoTable(doc, {
    startY: finalY + 4,
    head: [['OIML R 76-1 Test Clause', 'Test Condition / Scope', 'Measured Parameter', 'Compliance Status']],
    body: summaryData,
    theme: 'grid',
    headStyles: { fillColor: primaryNavy, textColor: [255, 255, 255], fontStyle: 'bold', fontSize: 8 },
    styles: { fontSize: 8, cellPadding: 2.2 },
    columnStyles: {
      0: { cellWidth: 65, fontStyle: 'bold' },
      1: { cellWidth: 50 },
      2: { cellWidth: 42 },
      3: { cellWidth: 25, fontStyle: 'bold', halign: 'center' },
    },
    didParseCell: (data) => {
      if (data.section === 'body' && data.column.index === 3) {
        const text = data.cell.text[0];
        if (text === 'PASSED') {
          data.cell.styles.textColor = [16, 149, 67];
        } else {
          data.cell.styles.textColor = [220, 38, 38];
        }
      }
    },
    margin: { left: 14, right: 14 },
  });

  // Footer for Page 1
  doc.setFontSize(7.5);
  doc.setTextColor(100, 116, 139);
  doc.text(`Page 1 of 3 | Verification Hash: ${report.verificationHash}`, 14, 287);
  doc.text('Official Legal Metrology Type Evaluation Record | Confidential', 200, 287, { align: 'right' });

  // ================= PAGE 2: WEIGHING TEST & CORNER LOADING =================
  doc.addPage();

  // Mini Header
  doc.setFillColor(...primaryNavy);
  doc.rect(0, 0, 210, 16, 'F');
  doc.setTextColor(255, 255, 255);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text(`OIML R 76-2 DETAILED OBSERVATION LOG | Report: ${instrument.reportNumber}`, 14, 11);
  doc.setFontSize(8);
  doc.setFont('helvetica', 'normal');
  doc.text(`Instrument: ${instrument.manufacturer} - ${instrument.model}`, 200, 11, { align: 'right' });

  // Weighing Test Table
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text('4. Weighing Performance Test Results (Annex A.4.4 & Table 6)', 14, 24);
  doc.setFontSize(7.5);
  doc.setFont('helvetica', 'normal');
  doc.setTextColor(71, 85, 105);
  doc.text(`Formulas: P = I + 0.5e - ΔL  |  E = P - L  |  Ec = E - E0 (with E0 = ${weighingTest.zeroErrorStart} ${instrument.unit})`, 14, 29);

  const weighingRows = weighingTest.rows.map((r) => [
    r.step.toString(),
    r.direction === 'increasing' ? '▲ Inc' : '▼ Dec',
    `${r.nominalLoad}`,
    `${r.indication}`,
    `${r.deltaL}`,
    `${r.trueIndication}`,
    `${r.error >= 0 ? '+' : ''}${r.error}`,
    `${r.correctedError >= 0 ? '+' : ''}${r.correctedError}`,
    `±${r.mpe}`,
    r.passed ? 'PASS' : 'FAIL',
  ]);

  autoTable(doc, {
    startY: 32,
    head: [['#', 'Dir', `Load (${instrument.unit})`, `Indic. (${instrument.unit})`, `ΔL (${instrument.unit})`, `True P (${instrument.unit})`, `Err E (${instrument.unit})`, `Ec (${instrument.unit})`, `MPE (±)`, 'Result']],
    body: weighingRows,
    theme: 'grid',
    headStyles: { fillColor: primaryNavy, textColor: [255, 255, 255], fontStyle: 'bold', fontSize: 7.5 },
    styles: { fontSize: 7, cellPadding: 1.8, halign: 'center' },
    columnStyles: {
      0: { cellWidth: 8 },
      1: { cellWidth: 14 },
      2: { cellWidth: 22 },
      3: { cellWidth: 22 },
      4: { cellWidth: 20 },
      5: { cellWidth: 22 },
      6: { cellWidth: 20 },
      7: { cellWidth: 20 },
      8: { cellWidth: 18 },
      9: { cellWidth: 16, fontStyle: 'bold' },
    },
    didParseCell: (data) => {
      if (data.section === 'body' && data.column.index === 9) {
        const text = data.cell.text[0];
        data.cell.styles.textColor = text === 'PASS' ? [16, 149, 67] : [220, 38, 38];
      }
    },
    margin: { left: 14, right: 14 },
  });

  // Eccentricity Test Table
  finalY = (doc as any).lastAutoTable.finalY + 8;
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text('5. Eccentricity / Corner Loading Test (Clause 3.6.2 & Annex A.4.7)', 14, finalY);
  doc.setFontSize(7.5);
  doc.setFont('helvetica', 'normal');
  doc.setTextColor(71, 85, 105);
  doc.text(`Test Load: ${eccentricityTest.testLoad} ${instrument.unit} (~ 1/3 Max) | Receptor: ${eccentricityTest.receptorType}`, 14, finalY + 4);

  const eccRows = eccentricityTest.points.map((p) => [
    p.positionLabel,
    `${p.indication}`,
    `${p.deltaL}`,
    `${p.trueIndication}`,
    `${p.error >= 0 ? '+' : ''}${p.error}`,
    `${p.correctedError >= 0 ? '+' : ''}${p.correctedError}`,
    `±${p.mpe}`,
    p.passed ? 'PASS' : 'FAIL',
  ]);

  autoTable(doc, {
    startY: finalY + 7,
    head: [['Position / Location', `Indic. (${instrument.unit})`, `ΔL (${instrument.unit})`, `True P (${instrument.unit})`, `Err E (${instrument.unit})`, `Ec (${instrument.unit})`, `MPE (±)`, 'Result']],
    body: eccRows,
    theme: 'grid',
    headStyles: { fillColor: primaryNavy, textColor: [255, 255, 255], fontStyle: 'bold', fontSize: 7.5 },
    styles: { fontSize: 7.5, cellPadding: 2, halign: 'center' },
    columnStyles: {
      0: { cellWidth: 50, halign: 'left', fontStyle: 'bold' },
      1: { cellWidth: 22 },
      2: { cellWidth: 20 },
      3: { cellWidth: 22 },
      4: { cellWidth: 20 },
      5: { cellWidth: 20 },
      6: { cellWidth: 16 },
      7: { cellWidth: 16, fontStyle: 'bold' },
    },
    didParseCell: (data) => {
      if (data.section === 'body' && data.column.index === 7) {
        const text = data.cell.text[0];
        data.cell.styles.textColor = text === 'PASS' ? [16, 149, 67] : [220, 38, 38];
      }
    },
    margin: { left: 14, right: 14 },
  });

  // Footer for Page 2
  doc.setFontSize(7.5);
  doc.setTextColor(100, 116, 139);
  doc.text(`Page 2 of 3 | Verification Hash: ${report.verificationHash}`, 14, 287);
  doc.text('Official Legal Metrology Type Evaluation Record | Confidential', 200, 287, { align: 'right' });

  // ================= PAGE 3: REPEATABILITY, DISCRIMINATION, SIGN-OFF =================
  doc.addPage();

  // Mini Header
  doc.setFillColor(...primaryNavy);
  doc.rect(0, 0, 210, 16, 'F');
  doc.setTextColor(255, 255, 255);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text(`OIML R 76-2 CONFORMITY CONCLUSION & SIGN-OFF | Report: ${instrument.reportNumber}`, 14, 11);
  doc.setFontSize(8);
  doc.setFont('helvetica', 'normal');
  doc.text(`Instrument: ${instrument.manufacturer} - ${instrument.model}`, 200, 11, { align: 'right' });

  // Repeatability Test Table
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text('6. Repeatability Evaluation (Clause 3.6.1 & Annex A.4.10)', 14, 24);

  const repData = [
    ['Series 1 (~ 50% Max)', `${repeatabilityTest.halfMaxLoad} ${instrument.unit}`, `ΔI = ${repeatabilityTest.halfMaxDiff} ${instrument.unit}`, `|MPE| = ${repeatabilityTest.halfMaxMpe} ${instrument.unit}`, repeatabilityTest.halfMaxPassed ? 'PASSED' : 'FAILED'],
    ['Series 2 (~ 100% Max)', `${repeatabilityTest.maxLoad} ${instrument.unit}`, `ΔI = ${repeatabilityTest.maxDiff} ${instrument.unit}`, `|MPE| = ${repeatabilityTest.maxMpe} ${instrument.unit}`, repeatabilityTest.maxPassed ? 'PASSED' : 'FAILED'],
  ];

  autoTable(doc, {
    startY: 28,
    head: [['Repeatability Load Series', 'Nominal Load', 'Max Difference (Imax - Imin)', 'Permissible Limit (|MPE|)', 'Status']],
    body: repData,
    theme: 'grid',
    headStyles: { fillColor: primaryNavy, textColor: [255, 255, 255], fontStyle: 'bold', fontSize: 7.5 },
    styles: { fontSize: 7.5, cellPadding: 2.2, halign: 'center' },
    columnStyles: {
      0: { cellWidth: 50, halign: 'left', fontStyle: 'bold' },
      1: { cellWidth: 35 },
      2: { cellWidth: 45 },
      3: { cellWidth: 35 },
      4: { cellWidth: 17, fontStyle: 'bold' },
    },
    didParseCell: (data) => {
      if (data.section === 'body' && data.column.index === 4) {
        data.cell.styles.textColor = data.cell.text[0] === 'PASSED' ? [16, 149, 67] : [220, 38, 38];
      }
    },
    margin: { left: 14, right: 14 },
  });

  // Discrimination Test Table
  finalY = (doc as any).lastAutoTable.finalY + 8;
  doc.setTextColor(...primaryNavy);
  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.text('7. Discrimination Evaluation (Clause 3.8 & Annex A.4.8)', 14, finalY);

  const discRows = discriminationTest.checks.map((c) => [
    c.loadLevel,
    `${c.baseLoad} ${instrument.unit}`,
    `${c.extraLoad} ${instrument.unit} (1.4d)`,
    `${c.newIndication} ${instrument.unit}`,
    `${c.indicationChange} ${instrument.unit}`,
    `≥ ${c.minimumRequiredChange} ${instrument.unit} (1d)`,
    c.passed ? 'PASSED' : 'FAILED',
  ]);

  autoTable(doc, {
    startY: finalY + 4,
    head: [['Load Point', 'Base Load', 'Additional Load (1.4d)', 'New Indication', 'Observed Change', 'Required Change', 'Status']],
    body: discRows,
    theme: 'grid',
    headStyles: { fillColor: primaryNavy, textColor: [255, 255, 255], fontStyle: 'bold', fontSize: 7.5 },
    styles: { fontSize: 7.5, cellPadding: 2, halign: 'center' },
    columnStyles: {
      0: { cellWidth: 25, fontStyle: 'bold' },
      1: { cellWidth: 28 },
      2: { cellWidth: 35 },
      3: { cellWidth: 28 },
      4: { cellWidth: 25 },
      5: { cellWidth: 25 },
      6: { cellWidth: 16, fontStyle: 'bold' },
    },
    didParseCell: (data) => {
      if (data.section === 'body' && data.column.index === 6) {
        data.cell.styles.textColor = data.cell.text[0] === 'PASSED' ? [16, 149, 67] : [220, 38, 38];
      }
    },
    margin: { left: 14, right: 14 },
  });

  // Overall Verdict & Official Remarks Box
  finalY = (doc as any).lastAutoTable.finalY + 8;
  doc.setFillColor(...lightBg);
  doc.rect(14, finalY, 182, 38, 'F');
  doc.setDrawColor(...borderGrey);
  doc.rect(14, finalY, 182, 38, 'S');

  doc.setFontSize(10);
  doc.setFont('helvetica', 'bold');
  doc.setTextColor(...primaryNavy);
  doc.text('8. Official Evaluator Findings & Legal Metrology Conformity Decision', 18, finalY + 7);

  doc.setFontSize(8);
  doc.setFont('helvetica', 'normal');
  doc.setTextColor(...slateDark);
  const splitRemarks = doc.splitTextToSize(`Evaluator Remarks: ${report.evaluatorRemarks}`, 174);
  doc.text(splitRemarks, 18, finalY + 14);

  if (report.approverRemarks) {
    const splitApp = doc.splitTextToSize(`Approver Endorsement: ${report.approverRemarks}`, 174);
    doc.text(splitApp, 18, finalY + 26);
  }

  // Stamp / Verdict Badge
  const verdictY = finalY + 44;
  doc.setFillColor(isPass ? 240 : 254, isPass ? 253 : 242, isPass ? 244 : 242);
  doc.rect(14, verdictY, 182, 16, 'F');
  doc.setDrawColor(isPass ? 34 : 239, isPass ? 197 : 68, isPass ? 94 : 68);
  doc.setLineWidth(0.6);
  doc.rect(14, verdictY, 182, 16, 'S');

  doc.setFontSize(11);
  doc.setFont('helvetica', 'bold');
  doc.setTextColor(isPass ? 22 : 185, isPass ? 101 : 28, isPass ? 52 : 28);
  doc.text(
    isPass
      ? '✓ FINAL VERDICT: CONFORMS TO OIML R 76-1:2006 (PATTERN APPROVED)'
      : '✕ FINAL VERDICT: NON-COMPLIANT WITH OIML R 76-1:2006 (REJECTED)',
    105,
    verdictY + 10,
    { align: 'center' }
  );

  // Digital Signatures
  const signY = verdictY + 22;
  // Evaluator
  doc.setDrawColor(203, 213, 225);
  doc.line(18, signY + 20, 85, signY + 20);
  doc.setFontSize(8);
  doc.setFont('helvetica', 'bold');
  doc.setTextColor(...primaryNavy);
  doc.text('TESTING & EVALUATION OFFICER', 18, signY + 24);
  doc.setFont('helvetica', 'normal');
  doc.setTextColor(71, 85, 105);
  doc.text(report.evaluatorSignature || 'Dr. Rajeshwar Sharma', 18, signY + 28);
  doc.text('Senior Metrologist, Legal Metrology Div', 18, signY + 32);

  // Approver
  doc.line(125, signY + 20, 192, signY + 20);
  doc.setFontSize(8);
  doc.setFont('helvetica', 'bold');
  doc.setTextColor(...primaryNavy);
  doc.text('LEGAL METROLOGY APPROVING AUTHORITY', 125, signY + 24);
  doc.setFont('helvetica', 'normal');
  doc.setTextColor(71, 85, 105);
  doc.text(report.approverSignature || 'Director of Legal Metrology', 125, signY + 28);
  doc.text('Ministry of Consumer Affairs, GoI', 125, signY + 32);

  // Verification Hash / QR representation
  doc.setFontSize(7);
  doc.setTextColor(148, 163, 184);
  doc.text(`Digital Verification Hash (SHA256 Token): ${report.verificationHash}`, 105, signY + 38, { align: 'center' });

  // Footer for Page 3
  doc.setFontSize(7.5);
  doc.setTextColor(100, 116, 139);
  doc.text(`Page 3 of 3 | Verification Hash: ${report.verificationHash}`, 14, 287);
  doc.text('Official Legal Metrology Type Evaluation Record | Confidential', 200, 287, { align: 'right' });

  // Save PDF
  const filename = `${instrument.reportNumber.replace(/[\/\\:]/g, '_')}_OIML_R76_Report.pdf`;
  doc.save(filename);
}

```

---

### File 32: `src/utils/sampleData.ts`
*Path: `src/utils/sampleData.ts` | Size: 37367 bytes | 4 Reference NAWI Instruments Benchmark Dataset*

```typescript
import type { OIMLTestReport, UserProfile } from '../types/oiml';
import { evaluateEntireReport } from './metrologyEngine';

export const DEFAULT_USERS: UserProfile[] = [
  {
    id: 'usr-1',
    name: 'Dr. Rajeshwar Sharma',
    role: 'senior_metrologist',
    designation: 'Senior Legal Metrologist & Type Evaluation Officer',
    department: 'Legal Metrology Division, Ministry of Consumer Affairs',
  },
  {
    id: 'usr-2',
    name: 'Priya Sundaram',
    role: 'testing_officer',
    designation: 'Metrological Testing Engineer',
    department: 'National Physical & Metrological Standards Laboratory',
  },
  {
    id: 'usr-3',
    name: 'Sh. Amitabh Mukherjee, IAS',
    role: 'director',
    designation: 'Director of Legal Metrology & Approving Authority',
    department: 'Ministry of Consumer Affairs, Food & Public Distribution',
  },
  {
    id: 'usr-4',
    name: 'Ananya Deshmukh',
    role: 'auditor',
    designation: 'NABL Lead Quality Assessor',
    department: 'National Accreditation Board for Testing Laboratories',
  },
];

// Sample 1: Class III Electronic Retail Counter Scale (30 kg, e = 5 g, d = 5 g, n = 6000) - COMPLIANT
const sample1Raw: OIMLTestReport = {
  id: 'rep-001',
  createdAt: '2026-09-12T10:30:00Z',
  updatedAt: '2026-09-14T14:45:00Z',
  status: 'approved',
  overallVerdict: 'COMPLIANT',
  evaluatorRemarks:
    'Instrument tested strictly in accordance with OIML R 76-1:2006 (clause 3.5, 3.6, 3.8). All intrinsic and corrected errors, repeatability spread, corner loading eccentricity, and discrimination checks conform within the Table 6 Maximum Permissible Errors.',
  evaluatorSignature: 'Dr. Rajeshwar Sharma, M.Tech (Metrology)',
  approverRemarks:
    'Pattern evaluation verified and approved for Model Approval Certificate under Section 22 of the Legal Metrology Act, 2009.',
  approverSignature: 'Sh. Amitabh Mukherjee, IAS, Director (LM)',
  verificationHash: '',
  auditTrail: [
    {
      id: 'aud-101',
      timestamp: '2026-09-12T10:30:00Z',
      userName: 'Dr. Rajeshwar Sharma',
      userRole: 'senior_metrologist',
      action: 'CREATED',
      description: 'Report initialized for Apex Weigh Systems Model APX-30R',
    },
    {
      id: 'aud-102',
      timestamp: '2026-09-13T16:20:00Z',
      userName: 'Dr. Rajeshwar Sharma',
      userRole: 'senior_metrologist',
      action: 'VALIDATED',
      description: 'Automated metrological calculations executed; all test procedures passed.',
    },
    {
      id: 'aud-103',
      timestamp: '2026-09-14T14:45:00Z',
      userName: 'Sh. Amitabh Mukherjee, IAS',
      userRole: 'director',
      action: 'APPROVED',
      description: 'Formally approved and signed digital type evaluation certificate.',
    },
  ],
  instrument: {
    id: 'inst-001',
    reportNumber: 'OIML-R76/MCA/2026/0892',
    applicationNumber: 'IND-LM-MA-2026-44109',
    manufacturer: 'Apex Weigh Systems India Pvt Ltd',
    applicant: 'Apex Weigh Systems India Pvt Ltd, Pune Cluster',
    model: 'APX-30R Pro',
    serialNumber: 'APX-2026-98144',
    yearOfManufacture: 2026,
    deviceType: 'Counter Scale',
    accuracyClass: 'III',
    verificationType: 'initial',
    unit: 'kg',
    maxCapacity: 30,
    minCapacity: 0.1, // 20e = 20 * 0.005 kg = 0.1 kg
    verificationScaleInterval: 0.005, // 5 g = 0.005 kg
    actualScaleInterval: 0.005,
    scaleIntervalCount: 6000, // 30 / 0.005 = 6000
    isMultiInterval: false,
    tareType: 'subtractive',
    maxTare: 15.0,
    zeroSettingType: 'semi_automatic',
    indicatorModel: 'Apex DSP-700 High-Res Microcontroller',
    loadCellModel: 'Zemic L6E3 Single-Point Aluminum',
    loadCellCertificateNo: 'R60/2000-NL1-12.08',
    loadCellCount: 1,
    platformDimensions: '330 mm x 280 mm Stainless Steel Pan',
  },
  environment: {
    laboratoryName: 'Regional Reference Standards Laboratory (RRSL), Western Region',
    laboratoryAddress: 'Sector 18, Industrial Area, Navi Mumbai, Maharashtra 400705',
    nablAccreditationNo: 'NABL-TC-8891-2026',
    oimlIssuingAuthority: 'Legal Metrology Division, Ministry of Consumer Affairs, GoI',
    evaluationLocation: 'Climate Chamber Lab Room 4',
    testDate: '2026-09-12',
    evaluationStartTime: '09:30 AM',
    evaluationEndTime: '04:15 PM',
    ambientTempStart: 21.4,
    ambientTempEnd: 22.1,
    relativeHumidity: 52,
    barometricPressure: 1012,
    mainsVoltage: 230,
    mainsFrequency: 50.1,
    warmUpTimeMinutes: 30,
    standardWeightsClass: 'F1',
    standardWeightsCertNo: 'RRSL-W-2026-0988-F1',
    standardWeightsValidity: '2027-04-30',
    standardWeightsUncertainty: 'U = 0.15 mg to 1.2 mg (k=2)',
  },
  weighingTest: {
    zeroErrorStart: 0.001,
    zeroErrorEnd: 0.001,
    rows: [
      { step: 1, direction: 'increasing', nominalLoad: 0.1, indication: 0.1, deltaL: 0.002, trueIndication: 0.1005, error: 0.0005, correctedError: -0.0005, mpe: 0.0025, passed: true },
      { step: 2, direction: 'increasing', nominalLoad: 1.0, indication: 1.0, deltaL: 0.0022, trueIndication: 1.0003, error: 0.0003, correctedError: -0.0007, mpe: 0.0025, passed: true },
      { step: 3, direction: 'increasing', nominalLoad: 2.5, indication: 2.5, deltaL: 0.0025, trueIndication: 2.5, error: 0, correctedError: -0.001, mpe: 0.0025, passed: true },
      { step: 4, direction: 'increasing', nominalLoad: 5.0, indication: 5.0, deltaL: 0.0023, trueIndication: 5.0002, error: 0.0002, correctedError: -0.0008, mpe: 0.005, passed: true },
      { step: 5, direction: 'increasing', nominalLoad: 10.0, indication: 10.0, deltaL: 0.0024, trueIndication: 10.0001, error: 0.0001, correctedError: -0.0009, mpe: 0.005, passed: true },
      { step: 6, direction: 'increasing', nominalLoad: 15.0, indication: 15.0, deltaL: 0.0022, trueIndication: 15.0003, error: 0.0003, correctedError: -0.0007, mpe: 0.0075, passed: true },
      { step: 7, direction: 'increasing', nominalLoad: 20.0, indication: 20.0, deltaL: 0.002, trueIndication: 20.0005, error: 0.0005, correctedError: -0.0005, mpe: 0.0075, passed: true },
      { step: 8, direction: 'increasing', nominalLoad: 25.0, indication: 25.0, deltaL: 0.0019, trueIndication: 25.0006, error: 0.0006, correctedError: -0.0004, mpe: 0.0075, passed: true },
      { step: 9, direction: 'increasing', nominalLoad: 30.0, indication: 30.0, deltaL: 0.0018, trueIndication: 30.0007, error: 0.0007, correctedError: -0.0003, mpe: 0.0075, passed: true },
      { step: 10, direction: 'decreasing', nominalLoad: 30.0, indication: 30.0, deltaL: 0.0018, trueIndication: 30.0007, error: 0.0007, correctedError: -0.0003, mpe: 0.0075, passed: true },
      { step: 11, direction: 'decreasing', nominalLoad: 20.0, indication: 20.0, deltaL: 0.0021, trueIndication: 20.0004, error: 0.0004, correctedError: -0.0006, mpe: 0.0075, passed: true },
      { step: 12, direction: 'decreasing', nominalLoad: 10.0, indication: 10.0, deltaL: 0.0024, trueIndication: 10.0001, error: 0.0001, correctedError: -0.0009, mpe: 0.005, passed: true },
      { step: 13, direction: 'decreasing', nominalLoad: 2.5, indication: 2.5, deltaL: 0.0026, trueIndication: 2.4999, error: -0.0001, correctedError: -0.0011, mpe: 0.0025, passed: true },
      { step: 14, direction: 'decreasing', nominalLoad: 0.1, indication: 0.1, deltaL: 0.0022, trueIndication: 0.1003, error: 0.0003, correctedError: -0.0007, mpe: 0.0025, passed: true },
    ],
    maxCorrectedError: 0.0011,
    maxMpeRatio: 0.44,
    hysteresisMax: 0.0002,
    hysteresisPassed: true,
    passed: true,
  },
  repeatabilityTest: {
    runsHalfMax: [
      { runIndex: 1, load: 15.0, indication: 15.0, deltaL: 0.0022, trueIndication: 15.0003, error: 0.0003 },
      { runIndex: 2, load: 15.0, indication: 15.0, deltaL: 0.0024, trueIndication: 15.0001, error: 0.0001 },
      { runIndex: 3, load: 15.0, indication: 15.0, deltaL: 0.0021, trueIndication: 15.0004, error: 0.0004 },
    ],
    runsMax: [
      { runIndex: 1, load: 30.0, indication: 30.0, deltaL: 0.0018, trueIndication: 30.0007, error: 0.0007 },
      { runIndex: 2, load: 30.0, indication: 30.0, deltaL: 0.002, trueIndication: 30.0005, error: 0.0005 },
      { runIndex: 3, load: 30.0, indication: 30.0, deltaL: 0.0019, trueIndication: 30.0006, error: 0.0006 },
    ],
    halfMaxLoad: 15.0,
    halfMaxDiff: 0,
    halfMaxMpe: 0.0075,
    halfMaxPassed: true,
    maxLoad: 30.0,
    maxDiff: 0,
    maxMpe: 0.0075,
    maxPassed: true,
    passed: true,
  },
  eccentricityTest: {
    testLoad: 10.0,
    receptorType: 'rectangular_4_corners',
    points: [
      { positionKey: 'center', positionLabel: 'Center (Position 1)', indication: 10.0, deltaL: 0.0024, trueIndication: 10.0001, error: 0.0001, correctedError: -0.0009, mpe: 0.005, passed: true },
      { positionKey: 'corner_1', positionLabel: 'Front-Left (Corner 2)', indication: 10.0, deltaL: 0.0021, trueIndication: 10.0004, error: 0.0004, correctedError: -0.0006, mpe: 0.005, passed: true },
      { positionKey: 'corner_2', positionLabel: 'Back-Left (Corner 3)', indication: 10.0, deltaL: 0.0026, trueIndication: 9.9999, error: -0.0001, correctedError: -0.0011, mpe: 0.005, passed: true },
      { positionKey: 'corner_3', positionLabel: 'Back-Right (Corner 4)', indication: 10.0, deltaL: 0.0023, trueIndication: 10.0002, error: 0.0002, correctedError: -0.0008, mpe: 0.005, passed: true },
      { positionKey: 'corner_4', positionLabel: 'Front-Right (Corner 5)', indication: 10.0, deltaL: 0.0025, trueIndication: 10.0, error: 0, correctedError: -0.01, mpe: 0.005, passed: true },
    ],
    maxSpread: 0.0005,
    maxMpe: 0.005,
    spreadPassed: true,
    passed: true,
  },
  discriminationTest: {
    checks: [
      { loadLevel: 'Min', baseLoad: 0.1, baseIndication: 0.1, extraLoad: 0.007, newIndication: 0.105, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
      { loadLevel: '0.5 Max', baseLoad: 15.0, baseIndication: 15.0, extraLoad: 0.007, newIndication: 15.005, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
      { loadLevel: 'Max', baseLoad: 30.0, baseIndication: 30.0, extraLoad: 0.007, newIndication: 30.005, indicationChange: 0.005, minimumRequiredChange: 0.005, passed: true },
    ],
    passed: true,
  },
  tareTest: {
    tareApplied: 10.0,
    netTestLoad: 15.0,
    indicatedNet: 15.0,
    deltaL: 0.0023,
    trueNet: 15.0002,
    netError: 0.0002,
    netMpe: 0.0075,
    tareBalancingError: 0.0005,
    maxPermissibleTareError: 0.00125,
    passed: true,
  },
  zeroTest: {
    zeroErrorE0: 0.001,
    maxPermissibleE0: 0.00125,
    zeroSettingPassed: true,
    zeroTrackingRate: 0.0015,
    maxZeroTrackingRate: 0.0025,
    zeroTrackingPassed: true,
    passed: true,
  },
  tiltingTest: {
    applicable: false,
    tiltRatio: 'Not applicable (fixed bench installation)',
    zeroIndicationNoTilt: 0,
    zeroIndicationTilted: 0,
    zeroShift: 0,
    maxPermissibleShift: 0.005,
    passed: true,
  },
  temperatureTest: {
    applicable: true,
    points: [
      { tempNominal: 20, actualTemp: 20.2, zeroIndication: 0, zeroShiftPer5C: 0.0008, maxPermissibleShiftPer5C: 0.005, passed: true },
      { tempNominal: 40, actualTemp: 39.8, zeroIndication: 0.002, zeroShiftPer5C: 0.0012, maxPermissibleShiftPer5C: 0.005, passed: true },
      { tempNominal: -10, actualTemp: -9.9, zeroIndication: -0.002, zeroShiftPer5C: 0.0014, maxPermissibleShiftPer5C: 0.005, passed: true },
      { tempNominal: 20, actualTemp: 20.1, zeroIndication: 0.001, zeroShiftPer5C: 0.0007, maxPermissibleShiftPer5C: 0.005, passed: true },
    ],
    passed: true,
  },
};

// Sample 2: Class II High Precision Laboratory Balance (1200 g, e = 0.01 g, d = 0.001 g) - COMPLIANT
const sample2Raw: OIMLTestReport = {
  id: 'rep-002',
  createdAt: '2026-08-20T11:00:00Z',
  updatedAt: '2026-08-22T15:30:00Z',
  status: 'approved',
  overallVerdict: 'COMPLIANT',
  evaluatorRemarks:
    'Electromagnetic force compensation precision balance evaluated in class II metrology chamber. Auxiliary scale interval d=0.001g verified with bracketed differentiator. MPE compliant across all 5,000e to 120,000e load ranges.',
  evaluatorSignature: 'Dr. Rajeshwar Sharma, M.Tech (Metrology)',
  approverRemarks: 'Approved for pharmaceutical and precious metal commercial transactions.',
  approverSignature: 'Sh. Amitabh Mukherjee, IAS, Director (LM)',
  verificationHash: '',
  auditTrail: [
    {
      id: 'aud-201',
      timestamp: '2026-08-20T11:00:00Z',
      userName: 'Priya Sundaram',
      userRole: 'testing_officer',
      action: 'CREATED',
      description: 'Report initialized for Sartorius-Optima Model EMB-1200',
    },
    {
      id: 'aud-202',
      timestamp: '2026-08-22T15:30:00Z',
      userName: 'Sh. Amitabh Mukherjee, IAS',
      userRole: 'director',
      action: 'APPROVED',
      description: 'Approved and issued verification certificate.',
    },
  ],
  instrument: {
    id: 'inst-002',
    reportNumber: 'OIML-R76/MCA/2026/0744',
    applicationNumber: 'IND-LM-MA-2026-38291',
    manufacturer: 'Optima Precision Balances Ltd',
    applicant: 'Optima Scientific Metrology India, Bengaluru',
    model: 'EMB-1200 Precision',
    serialNumber: 'OPT-2026-LAB-0442',
    yearOfManufacture: 2026,
    deviceType: 'Precision Balance',
    accuracyClass: 'II',
    verificationType: 'initial',
    unit: 'g',
    maxCapacity: 1200,
    minCapacity: 0.5,
    verificationScaleInterval: 0.01,
    actualScaleInterval: 0.001,
    scaleIntervalCount: 120000,
    isMultiInterval: false,
    tareType: 'subtractive',
    maxTare: 1200,
    zeroSettingType: 'semi_automatic',
    indicatorModel: 'EMB Touch Interface V3',
    loadCellModel: 'Monolithic EMFC Sensor Cell',
    loadCellCertificateNo: 'R60/2000-DE1-09.11',
    loadCellCount: 1,
    platformDimensions: 'Dia 130 mm Circular Pan with Glass Draft Shield',
  },
  environment: {
    laboratoryName: 'National Physical Laboratory (NPL) Metrology Cell',
    laboratoryAddress: 'Dr. K.S. Krishnan Marg, New Delhi 110012',
    nablAccreditationNo: 'NABL-TC-0001-2026',
    oimlIssuingAuthority: 'Director of Legal Metrology, GoI',
    evaluationLocation: 'Acoustic & Vibration Isolated Clean Room C-2',
    testDate: '2026-08-20',
    evaluationStartTime: '10:00 AM',
    evaluationEndTime: '03:00 PM',
    ambientTempStart: 20.0,
    ambientTempEnd: 20.2,
    relativeHumidity: 48,
    barometricPressure: 1014,
    mainsVoltage: 230,
    mainsFrequency: 50.0,
    warmUpTimeMinutes: 60,
    standardWeightsClass: 'E2',
    standardWeightsCertNo: 'NPL-E2-CAL-2026-118',
    standardWeightsValidity: '2027-08-15',
    standardWeightsUncertainty: 'U = 0.006 mg to 0.03 mg (k=2)',
  },
  weighingTest: {
    zeroErrorStart: 0.002,
    zeroErrorEnd: 0.002,
    rows: [
      { step: 1, direction: 'increasing', nominalLoad: 0.5, indication: 0.5, deltaL: 0.003, trueIndication: 0.502, error: 0.002, correctedError: 0, mpe: 0.005, passed: true },
      { step: 2, direction: 'increasing', nominalLoad: 50, indication: 50, deltaL: 0.003, trueIndication: 50.002, error: 0.002, correctedError: 0, mpe: 0.005, passed: true },
      { step: 3, direction: 'increasing', nominalLoad: 200, indication: 200, deltaL: 0.0025, trueIndication: 200.0025, error: 0.0025, correctedError: 0.0005, mpe: 0.01, passed: true },
      { step: 4, direction: 'increasing', nominalLoad: 600, indication: 600, deltaL: 0.002, trueIndication: 600.003, error: 0.003, correctedError: 0.001, mpe: 0.015, passed: true },
      { step: 5, direction: 'increasing', nominalLoad: 1000, indication: 1000, deltaL: 0.0018, trueIndication: 1000.0032, error: 0.0032, correctedError: 0.0012, mpe: 0.015, passed: true },
      { step: 6, direction: 'increasing', nominalLoad: 1200, indication: 1200, deltaL: 0.0015, trueIndication: 1200.0035, error: 0.0035, correctedError: 0.0015, mpe: 0.015, passed: true },
      { step: 7, direction: 'decreasing', nominalLoad: 1200, indication: 1200, deltaL: 0.0015, trueIndication: 1200.0035, error: 0.0035, correctedError: 0.0015, mpe: 0.015, passed: true },
      { step: 8, direction: 'decreasing', nominalLoad: 600, indication: 600, deltaL: 0.0022, trueIndication: 600.0028, error: 0.0028, correctedError: 0.0008, mpe: 0.015, passed: true },
      { step: 9, direction: 'decreasing', nominalLoad: 200, indication: 200, deltaL: 0.0027, trueIndication: 200.0023, error: 0.0023, correctedError: 0.0003, mpe: 0.01, passed: true },
      { step: 10, direction: 'decreasing', nominalLoad: 0.5, indication: 0.5, deltaL: 0.003, trueIndication: 0.502, error: 0.002, correctedError: 0, mpe: 0.005, passed: true },
    ],
    maxCorrectedError: 0.0015,
    maxMpeRatio: 0.1,
    hysteresisMax: 0.0002,
    hysteresisPassed: true,
    passed: true,
  },
  repeatabilityTest: {
    runsHalfMax: [
      { runIndex: 1, load: 600, indication: 600, deltaL: 0.002, trueIndication: 600.003, error: 0.003 },
      { runIndex: 2, load: 600, indication: 600, deltaL: 0.0022, trueIndication: 600.0028, error: 0.0028 },
      { runIndex: 3, load: 600, indication: 600, deltaL: 0.0019, trueIndication: 600.0031, error: 0.0031 },
    ],
    runsMax: [
      { runIndex: 1, load: 1200, indication: 1200, deltaL: 0.0015, trueIndication: 1200.0035, error: 0.0035 },
      { runIndex: 2, load: 1200, indication: 1200, deltaL: 0.0017, trueIndication: 1200.0033, error: 0.0033 },
      { runIndex: 3, load: 1200, indication: 1200, deltaL: 0.0016, trueIndication: 1200.0034, error: 0.0034 },
    ],
    halfMaxLoad: 600,
    halfMaxDiff: 0,
    halfMaxMpe: 0.015,
    halfMaxPassed: true,
    maxLoad: 1200,
    maxDiff: 0,
    maxMpe: 0.015,
    maxPassed: true,
    passed: true,
  },
  eccentricityTest: {
    testLoad: 400,
    receptorType: 'round_4_points',
    points: [
      { positionKey: 'center', positionLabel: 'Center of Pan', indication: 400, deltaL: 0.002, trueIndication: 400.003, error: 0.003, correctedError: 0.001, mpe: 0.015, passed: true },
      { positionKey: 'corner_1', positionLabel: 'Front Quadrant', indication: 400, deltaL: 0.0018, trueIndication: 400.0032, error: 0.0032, correctedError: 0.0012, mpe: 0.015, passed: true },
      { positionKey: 'corner_2', positionLabel: 'Left Quadrant', indication: 400, deltaL: 0.0022, trueIndication: 400.0028, error: 0.0028, correctedError: 0.0008, mpe: 0.015, passed: true },
      { positionKey: 'corner_3', positionLabel: 'Rear Quadrant', indication: 400, deltaL: 0.0019, trueIndication: 400.0031, error: 0.0031, correctedError: 0.0011, mpe: 0.015, passed: true },
      { positionKey: 'corner_4', positionLabel: 'Right Quadrant', indication: 400, deltaL: 0.0021, trueIndication: 400.0029, error: 0.0029, correctedError: 0.0009, mpe: 0.015, passed: true },
    ],
    maxSpread: 0.0004,
    maxMpe: 0.015,
    spreadPassed: true,
    passed: true,
  },
  discriminationTest: {
    checks: [
      { loadLevel: 'Min', baseLoad: 0.5, baseIndication: 0.5, extraLoad: 0.0014, newIndication: 0.501, indicationChange: 0.001, minimumRequiredChange: 0.001, passed: true },
      { loadLevel: '0.5 Max', baseLoad: 600, baseIndication: 600, extraLoad: 0.0014, newIndication: 600.001, indicationChange: 0.001, minimumRequiredChange: 0.001, passed: true },
      { loadLevel: 'Max', baseLoad: 1200, baseIndication: 1200, extraLoad: 0.0014, newIndication: 1200.001, indicationChange: 0.001, minimumRequiredChange: 0.001, passed: true },
    ],
    passed: true,
  },
  tareTest: {
    tareApplied: 500,
    netTestLoad: 600,
    indicatedNet: 600,
    deltaL: 0.002,
    trueNet: 600.003,
    netError: 0.003,
    netMpe: 0.015,
    tareBalancingError: 0.001,
    maxPermissibleTareError: 0.0025,
    passed: true,
  },
  zeroTest: {
    zeroErrorE0: 0.002,
    maxPermissibleE0: 0.0025,
    zeroSettingPassed: true,
    zeroTrackingRate: 0.0003,
    maxZeroTrackingRate: 0.0005,
    zeroTrackingPassed: true,
    passed: true,
  },
  tiltingTest: {
    applicable: false,
    tiltRatio: 'Self-leveling optical indicator installed',
    zeroIndicationNoTilt: 0,
    zeroIndicationTilted: 0,
    zeroShift: 0,
    maxPermissibleShift: 0.01,
    passed: true,
  },
  temperatureTest: {
    applicable: true,
    points: [
      { tempNominal: 20, actualTemp: 20.0, zeroIndication: 0, zeroShiftPer5C: 0.002, maxPermissibleShiftPer5C: 0.01, passed: true },
      { tempNominal: 30, actualTemp: 30.1, zeroIndication: 0.003, zeroShiftPer5C: 0.0015, maxPermissibleShiftPer5C: 0.01, passed: true },
      { tempNominal: 10, actualTemp: 10.1, zeroIndication: -0.002, zeroShiftPer5C: 0.0025, maxPermissibleShiftPer5C: 0.01, passed: true },
    ],
    passed: true,
  },
};

// Sample 3: Class III Pitless Heavy-Duty Weighbridge (60,000 kg, e = 20 kg) - COMPLIANT
const sample3Raw: OIMLTestReport = {
  id: 'rep-003',
  createdAt: '2026-09-01T08:00:00Z',
  updatedAt: '2026-09-03T18:00:00Z',
  status: 'approved',
  overallVerdict: 'COMPLIANT',
  evaluatorRemarks:
    'Full site verification of 18m x 3m weighbridge with mobile test truck and 20t calibrated weights. Axle load sections and end-to-end eccentricity conform to Clause 3.6.2.2 requirements.',
  evaluatorSignature: 'Dr. Rajeshwar Sharma, M.Tech (Metrology)',
  approverRemarks: 'Certified for commercial highway tolling and industrial weighment.',
  approverSignature: 'Sh. Amitabh Mukherjee, IAS, Director (LM)',
  verificationHash: '',
  auditTrail: [
    {
      id: 'aud-301',
      timestamp: '2026-09-01T08:00:00Z',
      userName: 'Dr. Rajeshwar Sharma',
      userRole: 'senior_metrologist',
      action: 'CREATED',
      description: 'Report initialized for Bharat Heavy Weigh Model BHW-60T',
    },
    {
      id: 'aud-302',
      timestamp: '2026-09-03T18:00:00Z',
      userName: 'Sh. Amitabh Mukherjee, IAS',
      userRole: 'director',
      action: 'APPROVED',
      description: 'Approved and issued official weighbridge verification certificate.',
    },
  ],
  instrument: {
    id: 'inst-003',
    reportNumber: 'OIML-R76/MCA/2026/0915',
    applicationNumber: 'IND-LM-MA-2026-49021',
    manufacturer: 'Bharat Heavy Weighbridges Ltd',
    applicant: 'National Highway Authority Freight Terminal, Panipat',
    model: 'BHW-60T Pitless Titan',
    serialNumber: 'BHW-2026-WB-883',
    yearOfManufacture: 2026,
    deviceType: 'Weighbridge',
    accuracyClass: 'III',
    verificationType: 'initial',
    unit: 'kg',
    maxCapacity: 60000,
    minCapacity: 400,
    verificationScaleInterval: 20,
    actualScaleInterval: 20,
    scaleIntervalCount: 3000,
    isMultiInterval: false,
    tareType: 'subtractive',
    maxTare: 30000,
    zeroSettingType: 'semi_automatic',
    indicatorModel: 'BHW Digital Terminal 9000 with Dual Display',
    loadCellModel: 'Double Ended Shear Beam Cell 30t',
    loadCellCertificateNo: 'R60/2000-GB1-08.02',
    loadCellCount: 8,
    platformDimensions: '18 m x 3 m Steel Deck Structure',
  },
  environment: {
    laboratoryName: 'Field Inspection Unit, Haryana State Legal Metrology Wing',
    laboratoryAddress: 'Sector 25, Transport Nagar, Panipat, Haryana 132103',
    nablAccreditationNo: 'NABL-TC-4412-2026',
    oimlIssuingAuthority: 'Controller of Legal Metrology, Haryana & Ministry of Consumer Affairs',
    evaluationLocation: 'NH-44 Freight Weighing Station Platform 1',
    testDate: '2026-09-01',
    evaluationStartTime: '08:30 AM',
    evaluationEndTime: '05:30 PM',
    ambientTempStart: 28.5,
    ambientTempEnd: 33.2,
    relativeHumidity: 65,
    barometricPressure: 1008,
    mainsVoltage: 230,
    mainsFrequency: 49.9,
    warmUpTimeMinutes: 45,
    standardWeightsClass: 'M1',
    standardWeightsCertNo: 'GOI-RRSL-M1-2026-5591',
    standardWeightsValidity: '2027-02-28',
    standardWeightsUncertainty: 'U = 100 g for 1000 kg block (k=2)',
  },
  weighingTest: {
    zeroErrorStart: 4,
    zeroErrorEnd: 4,
    rows: [
      { step: 1, direction: 'increasing', nominalLoad: 400, indication: 400, deltaL: 8, trueIndication: 402, error: 2, correctedError: -2, mpe: 10, passed: true },
      { step: 2, direction: 'increasing', nominalLoad: 5000, indication: 5000, deltaL: 9, trueIndication: 5001, error: 1, correctedError: -3, mpe: 10, passed: true },
      { step: 3, direction: 'increasing', nominalLoad: 10000, indication: 10000, deltaL: 8, trueIndication: 10002, error: 2, correctedError: -2, mpe: 10, passed: true },
      { step: 4, direction: 'increasing', nominalLoad: 20000, indication: 20000, deltaL: 7, trueIndication: 20003, error: 3, correctedError: -1, mpe: 20, passed: true },
      { step: 5, direction: 'increasing', nominalLoad: 30000, indication: 30000, deltaL: 6, trueIndication: 30004, error: 4, correctedError: 0, mpe: 20, passed: true },
      { step: 6, direction: 'increasing', nominalLoad: 40000, indication: 40000, deltaL: 7, trueIndication: 40003, error: 3, correctedError: -1, mpe: 20, passed: true },
      { step: 7, direction: 'increasing', nominalLoad: 50000, indication: 50000, deltaL: 8, trueIndication: 50002, error: 2, correctedError: -2, mpe: 30, passed: true },
      { step: 8, direction: 'increasing', nominalLoad: 60000, indication: 60000, deltaL: 9, trueIndication: 60001, error: 1, correctedError: -3, mpe: 30, passed: true },
      { step: 9, direction: 'decreasing', nominalLoad: 60000, indication: 60000, deltaL: 9, trueIndication: 60001, error: 1, correctedError: -3, mpe: 30, passed: true },
      { step: 10, direction: 'decreasing', nominalLoad: 40000, indication: 40000, deltaL: 7, trueIndication: 40003, error: 3, correctedError: -1, mpe: 20, passed: true },
      { step: 11, direction: 'decreasing', nominalLoad: 20000, indication: 20000, deltaL: 7, trueIndication: 20003, error: 3, correctedError: -1, mpe: 20, passed: true },
      { step: 12, direction: 'decreasing', nominalLoad: 400, indication: 400, deltaL: 8, trueIndication: 402, error: 2, correctedError: -2, mpe: 10, passed: true },
    ],
    maxCorrectedError: 3,
    maxMpeRatio: 0.3,
    hysteresisMax: 1,
    hysteresisPassed: true,
    passed: true,
  },
  repeatabilityTest: {
    runsHalfMax: [
      { runIndex: 1, load: 30000, indication: 30000, deltaL: 6, trueIndication: 30004, error: 4 },
      { runIndex: 2, load: 30000, indication: 30000, deltaL: 7, trueIndication: 30003, error: 3 },
      { runIndex: 3, load: 30000, indication: 30000, deltaL: 6, trueIndication: 30004, error: 4 },
    ],
    runsMax: [
      { runIndex: 1, load: 60000, indication: 60000, deltaL: 9, trueIndication: 60001, error: 1 },
      { runIndex: 2, load: 60000, indication: 60000, deltaL: 8, trueIndication: 60002, error: 2 },
      { runIndex: 3, load: 60000, indication: 60000, deltaL: 9, trueIndication: 60001, error: 1 },
    ],
    halfMaxLoad: 30000,
    halfMaxDiff: 0,
    halfMaxMpe: 20,
    halfMaxPassed: true,
    maxLoad: 60000,
    maxDiff: 0,
    maxMpe: 30,
    maxPassed: true,
    passed: true,
  },
  eccentricityTest: {
    testLoad: 20000,
    receptorType: 'weighbridge_sections',
    points: [
      { positionKey: 'section_1', positionLabel: 'Section 1 (Entry Axle pair)', indication: 20000, deltaL: 6, trueIndication: 20004, error: 4, correctedError: 0, mpe: 20, passed: true },
      { positionKey: 'section_2', positionLabel: 'Section 2 (Mid-Span)', indication: 20000, deltaL: 7, trueIndication: 20003, error: 3, correctedError: -1, mpe: 20, passed: true },
      { positionKey: 'section_3', positionLabel: 'Section 3 (Exit Axle pair)', indication: 20000, deltaL: 8, trueIndication: 20002, error: 2, correctedError: -2, mpe: 20, passed: true },
    ],
    maxSpread: 2,
    maxMpe: 20,
    spreadPassed: true,
    passed: true,
  },
  discriminationTest: {
    checks: [
      { loadLevel: 'Min', baseLoad: 400, baseIndication: 400, extraLoad: 28, newIndication: 420, indicationChange: 20, minimumRequiredChange: 20, passed: true },
      { loadLevel: '0.5 Max', baseLoad: 30000, baseIndication: 30000, extraLoad: 28, newIndication: 30020, indicationChange: 20, minimumRequiredChange: 20, passed: true },
      { loadLevel: 'Max', baseLoad: 60000, baseIndication: 60000, extraLoad: 28, newIndication: 60020, indicationChange: 20, minimumRequiredChange: 20, passed: true },
    ],
    passed: true,
  },
  tareTest: {
    tareApplied: 15000,
    netTestLoad: 30000,
    indicatedNet: 30000,
    deltaL: 6,
    trueNet: 30004,
    netError: 4,
    netMpe: 20,
    tareBalancingError: 2,
    maxPermissibleTareError: 5,
    passed: true,
  },
  zeroTest: {
    zeroErrorE0: 4,
    maxPermissibleE0: 5,
    zeroSettingPassed: true,
    zeroTrackingRate: 4,
    maxZeroTrackingRate: 10,
    zeroTrackingPassed: true,
    passed: true,
  },
  tiltingTest: {
    applicable: false,
    tiltRatio: 'Rigid Civil Foundation (Pitless)',
    zeroIndicationNoTilt: 0,
    zeroIndicationTilted: 0,
    zeroShift: 0,
    maxPermissibleShift: 20,
    passed: true,
  },
  temperatureTest: {
    applicable: false,
    points: [],
    passed: true,
  },
};

// Sample 4: Class III Industrial Platform Scale (150 kg, e = 50 g) - FAILED (Corner Eccentricity Error)
const sample4Raw: OIMLTestReport = {
  id: 'rep-004',
  createdAt: '2026-09-18T14:15:00Z',
  updatedAt: '2026-09-19T09:40:00Z',
  status: 'rejected',
  overallVerdict: 'NON_COMPLIANT',
  evaluatorRemarks:
    'NON-COMPLIANCE DETECTED: Platform Corner 3 (Back-Left) exhibited excessive mechanical deflection and mounting bolt play, resulting in corrected error of -60 g which exceeds the Maximum Permissible Error (MPE = ±25 g). Instrument returned for realignment and re-evaluation.',
  evaluatorSignature: 'Dr. Rajeshwar Sharma, M.Tech (Metrology)',
  approverRemarks: 'Rejected. Model approval rejected pending technical rectifications.',
  approverSignature: 'Sh. Amitabh Mukherjee, IAS, Director (LM)',
  verificationHash: '',
  auditTrail: [
    {
      id: 'aud-401',
      timestamp: '2026-09-18T14:15:00Z',
      userName: 'Dr. Rajeshwar Sharma',
      userRole: 'senior_metrologist',
      action: 'CREATED',
      description: 'Report initialized for Delta Industrial Scale Model DS-150P',
    },
    {
      id: 'aud-402',
      timestamp: '2026-09-18T17:00:00Z',
      userName: 'Dr. Rajeshwar Sharma',
      userRole: 'senior_metrologist',
      action: 'VALIDATED',
      description: 'Automated verification flagged Corner 3 Eccentricity failure.',
    },
    {
      id: 'aud-403',
      timestamp: '2026-09-19T09:40:00Z',
      userName: 'Sh. Amitabh Mukherjee, IAS',
      userRole: 'director',
      action: 'REJECTED',
      description: 'Rejected certificate issuance due to non-conformance.',
    },
  ],
  instrument: {
    id: 'inst-004',
    reportNumber: 'OIML-R76/MCA/2026/0998',
    applicationNumber: 'IND-LM-MA-2026-51200',
    manufacturer: 'Delta Weigh Systems Corp',
    applicant: 'Delta Metrology Equipments Pvt Ltd, Chennai',
    model: 'DS-150P Heavy Platform',
    serialNumber: 'DLT-2026-PL-912',
    yearOfManufacture: 2026,
    deviceType: 'Platform Scale',
    accuracyClass: 'III',
    verificationType: 'initial',
    unit: 'kg',
    maxCapacity: 150,
    minCapacity: 1.0,
    verificationScaleInterval: 0.05,
    actualScaleInterval: 0.05,
    scaleIntervalCount: 3000,
    isMultiInterval: false,
    tareType: 'subtractive',
    maxTare: 75,
    zeroSettingType: 'semi_automatic',
    indicatorModel: 'Delta IND-500 LCD',
    loadCellModel: 'Single Point Load Cell 200kg',
    loadCellCertificateNo: 'R60/2000-NL1-15.01',
    loadCellCount: 1,
    platformDimensions: '600 mm x 600 mm Mild Steel Chequered Plate',
  },
  environment: {
    laboratoryName: 'Southern Regional Standards Laboratory, Chennai',
    laboratoryAddress: 'GST Road, Guindy Industrial Estate, Chennai 600032',
    nablAccreditationNo: 'NABL-TC-1922-2026',
    oimlIssuingAuthority: 'Ministry of Consumer Affairs, GoI',
    evaluationLocation: 'Testing Bay 2',
    testDate: '2026-09-18',
    evaluationStartTime: '02:00 PM',
    evaluationEndTime: '05:30 PM',
    ambientTempStart: 25.1,
    ambientTempEnd: 25.8,
    relativeHumidity: 68,
    barometricPressure: 1010,
    mainsVoltage: 228,
    mainsFrequency: 50.0,
    warmUpTimeMinutes: 30,
    standardWeightsClass: 'M1',
    standardWeightsCertNo: 'RRSL-M1-2026-8911',
    standardWeightsValidity: '2027-06-30',
    standardWeightsUncertainty: 'U = 250 mg for 10 kg standard (k=2)',
  },
  weighingTest: {
    zeroErrorStart: 0.01,
    zeroErrorEnd: 0.01,
    rows: [
      { step: 1, direction: 'increasing', nominalLoad: 1.0, indication: 1.0, deltaL: 0.02, trueIndication: 1.005, error: 0.005, correctedError: -0.005, mpe: 0.025, passed: true },
      { step: 2, direction: 'increasing', nominalLoad: 25.0, indication: 25.0, deltaL: 0.022, trueIndication: 25.003, error: 0.003, correctedError: -0.007, mpe: 0.025, passed: true },
      { step: 3, direction: 'increasing', nominalLoad: 75.0, indication: 75.0, deltaL: 0.02, trueIndication: 75.005, error: 0.005, correctedError: -0.005, mpe: 0.05, passed: true },
      { step: 4, direction: 'increasing', nominalLoad: 100.0, indication: 100.0, deltaL: 0.018, trueIndication: 100.007, error: 0.007, correctedError: -0.003, mpe: 0.05, passed: true },
      { step: 5, direction: 'increasing', nominalLoad: 150.0, indication: 150.0, deltaL: 0.015, trueIndication: 150.01, error: 0.01, correctedError: 0, mpe: 0.075, passed: true },
      { step: 6, direction: 'decreasing', nominalLoad: 150.0, indication: 150.0, deltaL: 0.015, trueIndication: 150.01, error: 0.01, correctedError: 0, mpe: 0.075, passed: true },
      { step: 7, direction: 'decreasing', nominalLoad: 75.0, indication: 75.0, deltaL: 0.021, trueIndication: 75.004, error: 0.004, correctedError: -0.006, mpe: 0.05, passed: true },
      { step: 8, direction: 'decreasing', nominalLoad: 1.0, indication: 1.0, deltaL: 0.022, trueIndication: 1.003, error: 0.003, correctedError: -0.007, mpe: 0.025, passed: true },
    ],
    maxCorrectedError: 0.007,
    maxMpeRatio: 0.28,
    hysteresisMax: 0.001,
    hysteresisPassed: true,
    passed: true,
  },
  repeatabilityTest: {
    runsHalfMax: [
      { runIndex: 1, load: 75.0, indication: 75.0, deltaL: 0.02, trueIndication: 75.005, error: 0.005 },
      { runIndex: 2, load: 75.0, indication: 75.0, deltaL: 0.022, trueIndication: 75.003, error: 0.003 },
      { runIndex: 3, load: 75.0, indication: 75.0, deltaL: 0.02, trueIndication: 75.005, error: 0.005 },
    ],
    runsMax: [
      { runIndex: 1, load: 150.0, indication: 150.0, deltaL: 0.015, trueIndication: 150.01, error: 0.01 },
      { runIndex: 2, load: 150.0, indication: 150.0, deltaL: 0.018, trueIndication: 150.007, error: 0.007 },
      { runIndex: 3, load: 150.0, indication: 150.0, deltaL: 0.016, trueIndication: 150.009, error: 0.009 },
    ],
    halfMaxLoad: 75.0,
    halfMaxDiff: 0,
    halfMaxMpe: 0.05,
    halfMaxPassed: true,
    maxLoad: 150.0,
    maxDiff: 0,
    maxMpe: 0.075,
    maxPassed: true,
    passed: true,
  },
  eccentricityTest: {
    testLoad: 50.0,
    receptorType: 'rectangular_4_corners',
    points: [
      { positionKey: 'center', positionLabel: 'Center', indication: 50.0, deltaL: 0.022, trueIndication: 50.003, error: 0.003, correctedError: -0.007, mpe: 0.025, passed: true },
      { positionKey: 'corner_1', positionLabel: 'Front-Left (Corner 1)', indication: 50.0, deltaL: 0.02, trueIndication: 50.005, error: 0.005, correctedError: -0.005, mpe: 0.025, passed: true },
      { positionKey: 'corner_2', positionLabel: 'Back-Left (Corner 2)', indication: 49.95, deltaL: 0.045, trueIndication: 49.93, error: -0.07, correctedError: -0.08, mpe: 0.025, passed: false },
      { positionKey: 'corner_3', positionLabel: 'Back-Right (Corner 3)', indication: 50.0, deltaL: 0.025, trueIndication: 50.0, error: 0, correctedError: -0.01, mpe: 0.025, passed: true },
      { positionKey: 'corner_4', positionLabel: 'Front-Right (Corner 4)', indication: 50.0, deltaL: 0.023, trueIndication: 50.002, error: 0.002, correctedError: -0.008, mpe: 0.025, passed: true },
    ],
    maxSpread: 0.075,
    maxMpe: 0.025,
    spreadPassed: false,
    passed: false,
  },
  discriminationTest: {
    checks: [
      { loadLevel: 'Min', baseLoad: 1.0, baseIndication: 1.0, extraLoad: 0.07, newIndication: 1.05, indicationChange: 0.05, minimumRequiredChange: 0.05, passed: true },
      { loadLevel: '0.5 Max', baseLoad: 75.0, baseIndication: 75.0, extraLoad: 0.07, newIndication: 75.05, indicationChange: 0.05, minimumRequiredChange: 0.05, passed: true },
      { loadLevel: 'Max', baseLoad: 150.0, baseIndication: 150.0, extraLoad: 0.07, newIndication: 150.05, indicationChange: 0.05, minimumRequiredChange: 0.05, passed: true },
    ],
    passed: true,
  },
  tareTest: {
    tareApplied: 50.0,
    netTestLoad: 75.0,
    indicatedNet: 75.0,
    deltaL: 0.02,
    trueNet: 75.005,
    netError: 0.005,
    netMpe: 0.05,
    tareBalancingError: 0.005,
    maxPermissibleTareError: 0.0125,
    passed: true,
  },
  zeroTest: {
    zeroErrorE0: 0.01,
    maxPermissibleE0: 0.0125,
    zeroSettingPassed: true,
    zeroTrackingRate: 0.012,
    maxZeroTrackingRate: 0.025,
    zeroTrackingPassed: true,
    passed: true,
  },
  tiltingTest: {
    applicable: false,
    tiltRatio: 'Fixed bench mounted',
    zeroIndicationNoTilt: 0,
    zeroIndicationTilted: 0,
    zeroShift: 0,
    maxPermissibleShift: 0.05,
    passed: true,
  },
  temperatureTest: {
    applicable: false,
    points: [],
    passed: true,
  },
};

export const INITIAL_REPORTS: OIMLTestReport[] = [
  evaluateEntireReport(sample1Raw),
  evaluateEntireReport(sample2Raw),
  evaluateEntireReport(sample3Raw),
  evaluateEntireReport(sample4Raw),
];

```

---

### File 33: `start.bat`
*Path: `start.bat` | Size: 240 bytes | Source File*

```batch
@echo off
echo ===================================================
echo Starting NAWI Test Report Generator & Repository
echo ===================================================
echo.
echo Launching Vite Dev Server...
npm.cmd run dev
pause

```

---

### File 34: `tsconfig.app.json`
*Path: `tsconfig.app.json` | Size: 655 bytes | Source File*

```json
{
  "compilerOptions": {
    "tsBuildInfoFile": "./node_modules/.tmp/tsconfig.app.tsbuildinfo",
    "target": "es2023",
    "lib": ["ES2023", "DOM"],
    "module": "esnext",
    "types": ["vite/client"],
    "allowArbitraryExtensions": true,
    "skipLibCheck": true,

    /* Bundler mode */
    "moduleResolution": "bundler",
    "allowImportingTsExtensions": true,
    "verbatimModuleSyntax": true,
    "moduleDetection": "force",
    "noEmit": true,
    "jsx": "react-jsx",

    /* Linting */
    "noUnusedLocals": true,
    "noUnusedParameters": true,
    "erasableSyntaxOnly": true,
    "noFallthroughCasesInSwitch": true
  },
  "include": ["src"]
}

```

---

### File 35: `tsconfig.json`
*Path: `tsconfig.json` | Size: 119 bytes | Source File*

```json
{
  "files": [],
  "references": [
    { "path": "./tsconfig.app.json" },
    { "path": "./tsconfig.node.json" }
  ]
}

```

---

### File 36: `tsconfig.node.json`
*Path: `tsconfig.node.json` | Size: 558 bytes | Source File*

```json
{
  "compilerOptions": {
    "tsBuildInfoFile": "./node_modules/.tmp/tsconfig.node.tsbuildinfo",
    "target": "es2023",
    "lib": ["ES2023"],
    "types": ["node"],
    "skipLibCheck": true,

    /* Bundler mode */
    "module": "nodenext",
    "allowImportingTsExtensions": true,
    "verbatimModuleSyntax": true,
    "moduleDetection": "force",
    "noEmit": true,

    /* Linting */
    "noUnusedLocals": true,
    "noUnusedParameters": true,
    "erasableSyntaxOnly": true,
    "noFallthroughCasesInSwitch": true
  },
  "include": ["vite.config.ts"]
}

```

---

### File 37: `vercel.json`
*Path: `vercel.json` | Size: 183 bytes | Source File*

```json
{
  "buildCommand": "npm run build",
  "outputDirectory": "dist",
  "framework": "vite",
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/index.html"
    }
  ]
}

```

---

### File 38: `vite.config.ts`
*Path: `vite.config.ts` | Size: 161 bytes | Vite Build & Bundler Config*

```typescript
import react from '@vitejs/plugin-react'
import { defineConfig } from 'vite'

// https://vite.dev/config/
export default defineConfig({
  plugins: [react()],
})

```

---

