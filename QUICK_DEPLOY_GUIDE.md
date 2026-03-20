# Quick Heroku Deployment Guide

## Checklist
- [ ] Ensure your app is tested thoroughly.
- [ ] Create a Heroku account if you don't have one.
- [ ] Install the Heroku CLI.
- [ ] Log in to your Heroku account via CLI.
- [ ] Ensure your project has a `Procfile` to specify how to run the app.

## Commands
1. **Log in to Heroku:**  
   ```bash
   heroku login
   ```
2. **Create a new Heroku app:**  
   ```bash
   heroku create <app-name>
   ```
3. **Deploy to Heroku:**  
   ```bash
   git push heroku main
   ```
4. **Open the app in the browser:**  
   ```bash
   heroku open
   ```
5. **View logs for debugging:**  
   ```bash
   heroku logs --tail
   ```