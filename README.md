# My portfolio Website

![GitHub repo size](https://img.shields.io/github/repo-size/tersoo-atsen/my-portfolio)

A modern portfolio web site built with **Next.js** and **Strapi CMS**, **Tailwind CSS**, and automated SEO metadata. It effectively showcases skills, projects, and achievements through a performant, SEO-optimized platform.

The website features statically generated pages for projects, blog posts, and a secure contact form with both client-side and server-side validation. Content is seamlessly managed in Strapi CMS, including SEO configurations (titles, meta descriptions), while JSON-LD schemas (BlogPosting, Organization, etc.) enhance search engine visibility. Optimizations include a dynamic XML sitemap, OpenGraph metadata, image optimizations, semantic HTML and many more.

Security measures like honeypot spam protection, API rate limiting, and email obfuscation safeguard sensitive data. Built with Tailwind CSS for rapid styling, this starter template balances flexibility with maintainability—ideal for portfolios, agencies, or developers prioritizing performance, accessibility, and modern best practices.

**[See the site](https://demo.url)**

## Features

### Core functionality

✅ Dynamic content management:

- All content is managed via Strapi CMS, allowing easy updates without code changes.

✅ Home page:

- Features a hero, about, skills, experience or services, featured projects, testimonials, latest posts, FAQ, and a prominent call-to-action.
- A dynamic zone allows users to tailor the homepage based on their needs:
  - Experience section: For developers showcasing their career journey.
  - Services section: For freelance developers or agencies highlighting their offerings.

✅ Projects:

- A dynamically updated projects page that lists all published projects and supports dynamic sorting. Each project has a dedicated page with detailed information, rich metadata for SEO, and syntax highlighting for code snippets.

✅ Contact page:

- Features a secure contact form with both client-side and server-side validation powered by Zod, along with spam protection implemented through a honeypot.

✅ Privacy policy page:

- A dedicated page for privacy-related information.

### Performance & optimization

✅ Static site generation (SSG):

- Delivers optimal performance and improves SEO by pre-rendering pages at build time.

✅ Optimized images:

- Explicitly defined dimensions prevent layout shifts, improving visual stability and user experience.
- Priority loading for critical above-the-fold images and lazy loading for non-essential images reduce initial page load time and improve user experience.
- The `sizes` property is used to deliver appropriately sized images based on screen widths and device pixel ratios, minimizing bandwidth usage and enhancing page performance.

✅ Inline CSS:

- Reduces additional network requests by inlining critical CSS, improving key performance metrics like First Contentful Paint (FCP) and Largest Contentful Paint (LCP).

### SEO & accessibility

✅ Semantic HTML:

- Ensures accessibility and screen reader compatibility.
- Enhances SEO by providing clear structure and context to web content, making it easier for search engines to crawl, index, and understand the content. This can improve visibility and relevance in search results.

✅ SEO enhancements:

- Automated XML sitemap generation.
- Canonical tags for all pages.
- Supports various JSON-LD schemas (e.g., Organization, Person, BlogPosting, ItemPage, ContactPage, CollectionPage, WebPage) to enhance SEO and provide rich search engine results.
- OpenGraph metadata for social sharing across platforms.

### Security & spam protection

✅ Spam protection:

- Honeypot implementation to block bot submissions in the contact form.

✅ Email & phone number obfuscation:

- Protects sensitive contact information using Base64 encoding and client-side rendering.

✅ Rate limiting Strapi middleware:

- Protects APIs from abuse using a fixed window rate limiter.

✅ API validation with Zod:

- Ensures type safety and robust error handling across all API interactions.

## Roadmap

- [ ] Add CAPTCHA solution for contact form
- [ ] Add pagination to Blog and Projects pages
- [ ] Create breadcrumb component with SEO schema integration
- [ ] Restrict media uploads by file type and size

## Acknowledgements

Special thanks to the amazing contributors and open-source communities behind the tools that made this project possible:

- The [Strapi](https://strapi.io/) team for their incredible headless CMS, which powers the backend of this application.
- The [Next.js](https://nextjs.org/) team for providing a robust framework that simplifies building modern web applications.
- The [Tailwind CSS](https://tailwindcss.com/) community for their elegant and efficient utility-first CSS framework.
- The [React](https://react.dev/) ecosystem and its contributors for enabling seamless UI development.

Your dedication to open-source innovation inspires developers worldwide. Thank you!

## License

&copy; 2025 [Tersoo Atsen](https://www.msof.me/). Code released under the [MIT](LICENSE) license.
