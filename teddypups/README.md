# 🧸 TeddyPups U.A.E. — Website Clone

A playful, hand-drawn style website for a Dubai-based miniature puppy brand. The site is built with three plain files (`index.html`, `style.css`, `script.js`) and has six pages, a page-transition animation, working filters and a contact form that opens WhatsApp.

> **Note:** This is a front-end design clone built for learning and demo purposes. All puppy photos are replaced with emoji and colour tiles, and the phone number and email are placeholders.

---

## ✨ Features

- **6 pages** in one file: Home, Puppies, Happy families, How it works, FAQ, Visit & contact
- **Page-load animation:** a poodle runs across a lattice-pattern screen (about 2 seconds) every time you change page
- **Puppy filters:** filter by where (everywhere / imported / Korean teacup), breed and boy or girl
- **FAQ board:** pinned-note style questions with live search
- **How it works toggle:** switch between "In Dubai" and "Imported" journeys
- **Contact letter form:** "Dear TeddyPups…" form that opens WhatsApp with a pre-filled message
- **Responsive:** works on phones, tablets and desktops, with a mobile menu
- **Dark mode:** follows the device's light or dark setting
- **Accessible basics:** keyboard focus outlines and reduced-motion support

---

## 📄 Pages

| Page | Link | What's inside |
|---|---|---|
| Home | `#home` | Hero with arch windows, "Meet the pups" doors, two ways to meet, puppy journey, trust badges, "Already gone home" |
| Puppies | `#puppies` | Filter board and puppy bubbles with "Available" tags |
| Happy families | `#happy-families` | Polaroid wall and testimonial note |
| How it works | `#how-it-works` | In Dubai / Imported toggle, step cards, premium promise, delivery, why choose us |
| FAQ | `#faq` | Searchable corkboard of questions |
| Visit & contact | `#contact` | Contact details, showroom card, letter form |

Pages switch using the URL hash (for example `yoursite.vercel.app/#puppies`), so no server configuration is needed.

---

## 🧰 Tech stack

- HTML, CSS and vanilla JavaScript (no framework, no build step)
- Google Fonts: **Fraunces**, **Caveat**, **Outfit**
- No backend, no database, no dependencies

---

## 📁 Project structure

```
teddypups/
├── index.html   # structure and content of all 6 pages (HTML)
├── style.css    # all styling (CSS)
├── script.js    # filters, FAQ search, form, page animation (JavaScript)
└── README.md
```

---

## 🚀 Run locally

1. Unzip the folder.
2. Double-click `index.html` to open in your browser.

That's it. An internet connection is only needed for the Google Fonts.

---

## 🌍 Deploy

### 1. Upload to GitHub
1. Create a new repository on [github.com](https://github.com) (for example `teddypups`).
2. Click **uploading an existing file** and upload all the files (or push the folder from VS Code).
3. Click **Commit changes**.

### 2. Deploy on Vercel
1. Log in to [vercel.com](https://vercel.com) with GitHub.
2. Click **Add New → Project** and **Import** your repository.
3. Keep the default settings (Framework: *Other*, no build command) and click **Deploy**.
4. Your site goes live at `your-project.vercel.app`.

Every time you edit `index.html` on GitHub, Vercel redeploys automatically.

---

## 🛠️ Customise

Open the folder in VS Code and search for these:

| What to change | Where to look |
|---|---|
| WhatsApp number | Search all files (Ctrl+Shift+H) for `971500000000` and replace with your number (country code, no `+`) |
| Phone and email | Search `+971 50 000 0000` and `info@instabizweb.com` |
| Puppy list | The `P` array in `script.js`: `[name, breed, boy/girl, age, emoji, imported(1) or local(0)]` |
| FAQ questions | The `Q` array in `script.js` |
| Happy-family captions | The `caps` array in `script.js` |
| Colours | CSS variables at the top of `style.css` (`--bg`, `--cara`, `--org`, `--grn`, `--sand`) |
| Real photos | Add image files to the repository and replace the emoji tiles with `<img>` tags |

---

## ⚠️ Limitations

- **No backend.** The contact form does not save or email data; it opens WhatsApp with a ready message. Real form storage needs a service such as Formspree or a Vercel serverless function.
- **Puppy data is hard-coded.** To add, remove or edit puppies you edit the code. An admin panel would need a database (for example Supabase).
- **No individual puppy pages.** Puppy cards link to WhatsApp.
- **Placeholder visuals.** Emoji and colour tiles stand in for photos and the cartoon mascot.

---

## 🔮 Ideas for next steps

- Add real puppy photos and videos
- Separate profile page for each puppy
- Contact form that sends email
- Admin panel to manage puppies
- Multi-language support (English / Arabic)

---

## 📜 Credits

Layout and content are inspired by the TeddyPups U.A.E. demo website (`puppy.instabizweb.com`). All trademarks, brand names and original content belong to their respective owners. This project is a design exercise and is not affiliated with the original brand.
