# Portfolio Website - Harsh Patel

A modern, interactive portfolio website showcasing backend engineering experience, projects, and skills.

## Features

✨ **Interactive Design**
- Smooth scrolling navigation
- Responsive layout
- Modern dark theme matching GitHub's aesthetic

💼 **LinkedIn-Style Work Experience**
- Timeline view with visual connection
- Detailed role descriptions with bullet points
- Technology tags for each position
- Hover effects for better interactivity

📂 **Project Showcase**
- Expandable project descriptions
- Clean card-based layout
- "See more/less" functionality

📧 **Contact Form**
- Integrated email submission
- Form validation
- Success/error feedback
- Uses Web3Forms (free service)

## Setup Instructions

### 1. Contact Form Configuration

The website uses **Web3Forms** - a free email forwarding service.

**Steps:**
1. Visit [https://web3forms.com/](https://web3forms.com/)
2. Enter your email address (where you want to receive messages)
3. Click "Get Access Key"
4. Copy the access key you receive
5. Open `index.html`
6. Find this line (around line 398):
   ```javascript
   formData.append('access_key', 'YOUR_WEB3FORMS_ACCESS_KEY');
   ```
7. Replace `YOUR_WEB3FORMS_ACCESS_KEY` with your actual key

**Example:**
```javascript
formData.append('access_key', 'a1b2c3d4-e5f6-7890-abcd-ef1234567890');
```

### 2. Running the Website

Simply open `index.html` in any modern web browser:
- Chrome
- Firefox
- Safari
- Edge

No server or build process required!

### 3. Deploying

You can deploy this website to:
- **GitHub Pages** (free)
- **Netlify** (free)
- **Vercel** (free)
- Any static hosting service

## Technologies Used

- HTML5
- CSS3 (Custom styling)
- Vanilla JavaScript
- Web3Forms API

## Customization

### Update Your Information

1. **Personal Details**: Edit the `<header>` and `.about` sections
2. **Work Experience**: Modify the `.timeline-item` sections
3. **Projects**: Update the project cards in `#projects` section
4. **Skills**: Add/remove skills in the `#skills` section
5. **LinkedIn Link**: Update the LinkedIn URL in the navigation

### Color Scheme

The website uses a GitHub-inspired dark theme. To customize colors:
- Primary: `#58a6ff` (blue)
- Success: `#238636` (green)
- Background: `#0d1117` (dark)
- Card Background: `#161b22`

## Contact

For any questions or feedback, reach out via the contact form on the website!

---

Built with ❤️ by Harsh Patel
