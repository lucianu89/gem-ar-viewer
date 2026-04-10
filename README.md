# GEM Sampling Design – AR Viewer

View the 50×50 m GEM savanna plot in augmented reality on any phone, no app required.

## Files
- `index.html` — the AR viewer page
- `Claude_GEM.glb` — the 3D model

## How to deploy (5 minutes)

### 1. Create a GitHub repository
1. Go to https://github.com and sign in (or create a free account)
2. Click the **+** icon → **New repository**
3. Name it something like `gem-ar-viewer`
4. Set it to **Public**
5. Click **Create repository**

### 2. Upload the files
1. On your new repo page click **Add file → Upload files**
2. Upload **both** `index.html` and `Claude_GEM.glb`
3. Click **Commit changes**

### 3. Enable GitHub Pages
1. Go to **Settings** (top menu of your repo)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source** select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**
6. Wait ~60 seconds then refresh — you'll see your live URL:
   `https://YOUR-USERNAME.github.io/gem-ar-viewer/`

### 4. Generate a QR code
1. Copy your GitHub Pages URL
2. Go to https://qr-code-generator.com
3. Paste the URL and download the QR code image

### 5. Scan and view in AR
- **Android** (Chrome): tap "View in AR" → point at floor/table → tap to place
- **iPhone/iPad** (Safari): tap "View in AR" → Quick Look launches automatically

## Tips
- The model is ~4 MB so it loads in a few seconds on 4G/WiFi
- For best AR experience, scan a well-lit flat surface (table, floor)
- Pinch to scale the model once placed in AR
