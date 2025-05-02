# Xtream Player Deployment

## Quick Start

1. **Enter your credentials** in the configuration form
2. **Click "Save Configuration"**
3. **Browse channels** and click to play

## Deployment Options

### Option 1: Deploy to Vercel (Recommended)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag and drop this entire folder
3. Click "Deploy"

### Option 2: Deploy to Firebase
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting` (choose current directory)
4. Deploy: `firebase deploy`

## Troubleshooting

If you get CORS errors:
1. Try different server URL formats:
   - `http://starshare.st:80`
   - `http://starshare.st`
   - `https://starshare.st`

If streams don't play:
1. Check your credentials
2. Try a different browser
3. Ensure your server is online
