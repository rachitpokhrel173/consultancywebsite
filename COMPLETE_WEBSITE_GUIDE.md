6# BMC Educational Consultancy - Complete Website Package

## 📁 Website Structure

```
bmc-website/
├── index.html (UPDATE REQUIRED - see instructions below)
├── services/
│   ├── essay-writing.html ✅
│   ├── ielts-coaching.html ✅
│   ├── visa-support.html ✅
│   └── career-planning.html ✅
├── resources/
│   ├── free-guide.html ✅
│   ├── student-blog.html ✅
│   ├── scholarship-db.html ✅
│   ├── faq.html ✅
│   └── privacy-policy.html ✅
├── README.md
├── FOOTER_UPDATE_INSTRUCTIONS.txt
└── COMPLETE_WEBSITE_GUIDE.md (this file)
```

## ✨ What's Included

### Service Pages (4 pages)
Each service page includes:
- Comprehensive service description
- Process breakdown
- Feature highlights with icons
- Call-to-action sections
- Consistent BMC branding

1. **Essay Writing** - Personal statements, supplemental essays, scholarship applications
2. **IELTS Coaching** - All four modules, mock tests, certified instructors
3. **Visa Support** - Document preparation, interview prep, multiple countries
4. **Career Planning** - Psychometric testing, industry research, 5-year roadmaps

### Resource Pages (5 pages)
Each resource page provides value to visitors:

1. **Free Guide Download** - 6 downloadable PDF guides with real download counts
2. **Student Blog** - 6 featured blog articles with engaging topics
3. **Scholarship Database** - Searchable database of major scholarships
4. **FAQ** - 8 common questions with expandable answers (interactive)
5. **Privacy Policy** - Comprehensive, legally-sound privacy documentation

## 🎨 Design Theme

All pages share a consistent, premium design:
- **Colors**: Ink black (#0b0e14), Luxe gold (#d4a94c), Warm cream (#f6f3ed)
- **Typography**: Cormorant Garamond (elegant serif), Outfit (modern sans-serif)
- **Effects**: Subtle grain overlay, smooth animations, hover effects
- **Mobile**: Fully responsive design for all devices

## 📝 Required Updates to index.html

You need to make TWO updates to your main index.html:

### 1. Add Developer Credit to Footer

Find this section near the end of index.html:
```html
<div class="footer-bottom">
  <span>© 2026 BMC Educational Consultancy. All rights reserved.</span>
  <span>Designed with passion for your future.</span>
</div>
```

Replace with:
```html
<div class="footer-bottom">
  <span>© 2026 BMC Educational Consultancy. All rights reserved.</span>
  <span>Designed with passion for your future.</span>
  <span>Developed by <a href="https://rachitpokhrel.com.np" target="_blank">Rachit Pokhrel</a></span>
</div>
```

### 2. Update Footer Links

Find the Services and Resources sections in the footer and update the links:

**Services Section:**
```html
<div class="f-col"><h5>Services</h5><ul>
  <li><a href="services/essay-writing.html">Essay Writing</a></li>
  <li><a href="services/ielts-coaching.html">IELTS Coaching</a></li>
  <li><a href="services/visa-support.html">Visa Support</a></li>
  <li><a href="services/career-planning.html">Career Planning</a></li>
</ul></div>
```

**Resources Section:**
```html
<div class="f-col"><h5>Resources</h5><ul>
  <li><a href="resources/free-guide.html">Free Guide Download</a></li>
  <li><a href="resources/student-blog.html">Student Blog</a></li>
  <li><a href="resources/scholarship-db.html">Scholarship DB</a></li>
  <li><a href="resources/faq.html">FAQ</a></li>
  <li><a href="resources/privacy-policy.html">Privacy Policy</a></li>
</ul></div>
```

## 🚀 Deployment Instructions

1. **Update your index.html** with the footer changes above
2. **Upload all files** to your web server maintaining the folder structure
3. **Test all links** to ensure navigation works correctly
4. **Verify mobile responsiveness** on different devices

## 💡 Key Features

✅ Consistent branding across all 10 pages
✅ SEO-friendly structure with proper headings
✅ Fast-loading, optimized CSS
✅ Accessible design with proper alt texts and labels
✅ Professional, conversion-focused copy
✅ Interactive elements (FAQ accordion, hover effects)
✅ Clear calls-to-action throughout

## 📧 Contact Information in All Pages

All pages include BMC's contact details:
- Address: New Baneshwor 10, Subarna Margh, 44600
- Phone: +977 976-7657313
- Email: bmceducationconsultancy@gmail.com
- Hours: Sun – Fri: 9:00 AM – 6:00 PM

## 🎯 Developer Credit

**Developer**: Rachit Pokhrel  
**Website**: https://rachitpokhrel.com.np

This credit appears in the footer of every page (index.html requires manual update).

## 📱 Browser Compatibility

Tested and optimized for:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive breakpoints: 1024px, 768px, 640px, 380px

## 🎨 Customization Notes

If you need to modify colors or fonts:
- CSS variables are defined in `:root` at the top of each page's `<style>` section
- Easy to find and update: `--ink`, `--gold`, `--cream`, etc.
- Font families specified in the `<link>` tags (Google Fonts)

---

**Need help?** Contact the developer at https://rachitpokhrel.com.np

*Last Updated: February 3, 2026*
