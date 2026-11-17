# Arthur Mello — Music Portfolio

A responsive four-page static portfolio built with HTML, CSS and JavaScript. Ready for GitHub Pages.

## Pages
- `index.html` — landing page, image gallery, featured work and social links
- `about.html` — artist biography
- `works.html` — songs, credits, audio previews and streaming links
- `contact.html` — interactive contact form and social links

## Personalize before publishing

### 1. Set your email address
Open `contact.html` and replace both occurrences of `YOUR_EMAIL_ADDRESS` with the email address where you want to receive submissions.

The form uses FormSubmit (`formsubmit.co`) to deliver submissions to your inbox. On the first submission, FormSubmit will send a confirmation email to that address; confirm it to activate delivery. This is a third-party service, not a custom backend. Review its privacy terms before using it.

### 2. Add your photos
You said you'll provide photographs later, so the current image URLs are temporary examples. When you're ready:
1. Create `assets/images/`.
2. Add your own photographs there.
3. Replace the relevant image URLs in the HTML with paths such as `assets/images/live-show.jpg`.

### 3. Add your songs
Create `assets/audio/` and add:
- `track-one.mp3`
- `track-two.mp3`
- `track-three.mp3`

Replace the sample song titles, descriptions, credits and streaming URLs in `works.html`. Only upload audio you own or have permission to share.

### 4. Publish on GitHub Pages
1. Upload the contents of this folder to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your main branch and `/ (root)`, then save.

### 5. Connect your domain
Under **Settings → Pages → Custom domain**, enter your domain. Configure the DNS records at your domain registrar exactly as GitHub Pages instructs. Enable HTTPS when it becomes available.

## Notes
- No framework, build step, server or database is needed.
- The contact form relies on FormSubmit, a third-party service.
- Google Fonts and temporary remote image URLs need an internet connection.
