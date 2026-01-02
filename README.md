# Glue Factory Radio - Splash Page

Simple splash page for `gluefactoryradio.com`

## Quick Deploy to Vercel

### Option 1: Deploy from GitHub
1. Create a new GitHub repository
2. Push this code to the repository
3. In Vercel dashboard, click "Add New Project"
4. Import the GitHub repository
5. Vercel will auto-detect the settings
6. Add domain `gluefactoryradio.com` in project settings → Domains
7. Deploy!

### Option 2: Deploy from CLI
```bash
npm i -g vercel
cd glue-factory-radio-splash
vercel
# Follow the prompts
# Add domain: vercel domains add gluefactoryradio.com
```

## Files

- `index.html` - The splash page with MailChimp email signup
- `logo.png` - Glue Factory Radio logo
- `vercel.json` - Vercel configuration for static hosting

## Features

- Red background (#ff0000)
- Glue Factory Radio logo
- Email signup form (MailChimp integration)
- Arrow submit button
- Fully responsive

## When Ready to Launch

When you're ready to launch the full radio app:
1. In Vercel, go to your main radio app project
2. Add domain `gluefactoryradio.com` to that project
3. Remove `gluefactoryradio.com` from this splash page project
4. This splash page project can be archived or deleted

