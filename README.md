# Djasa2288 GitHub Pages Site

This is a personal website powered by [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.  
The site is managed easily via the `jekyll-admin` interface and enhanced with several plugins for SEO, sitemap, feeds, pagination, asset management, and archives.

## Features

- **[jekyll-admin](https://github.com/jekyll/jekyll-admin)**  
  Manage your site content and configuration via a friendly web-based admin dashboard (`/admin`).

- **[jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)**  
  Automatically adds SEO tags to your pages for better search engine visibility.

- **[jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)**  
  Generates a sitemap.xml for search engines.

- **[jekyll-feed](https://github.com/jekyll/jekyll-feed)**  
  Provides an Atom (RSS) feed for your posts.

- **[jekyll-paginate](https://github.com/jekyll/jekyll-paginate)**  
  Adds support for paginating your blog posts.

- **[jekyll-assets](https://github.com/jekyll/jekyll-assets)**  
  Asset pipeline for image, CSS, and JavaScript optimization.

- **[jekyll-archives](https://github.com/jekyll/jekyll-archives)**  
  Generates archive pages for categories, tags, and years.

## Getting Started

1. **Clone this repository**
   ```sh
   git clone https://github.com/Djasa2288/Djasa2288.github.io.git
   cd Djasa2288.github.io
   ```

2. **Install dependencies**
   ```sh
   bundle install
   ```

3. **Run Jekyll locally with admin interface**
   ```sh
   bundle exec jekyll serve --livereload
   ```
   Then open [http://localhost:4000/admin](http://localhost:4000/admin) to access the admin dashboard.

## Configuration

All plugin settings are managed in `_config.yml`.  
Key configurations:

- **SEO**: Customize site title, description, social links, and more for better SEO.
- **Pagination**: Set `paginate` and `paginate_path` in `_config.yml`.
- **RSS Feed**: Automatically available at `/feed.xml`.
- **Sitemap**: Accessible at `/sitemap.xml`.
- **Archives**: Configure archive types in `_config.yml`.

## Example `_config.yml` Plugins Section

```yaml
plugins:
  - jekyll-admin
  - jekyll-seo-tag
  - jekyll-sitemap
  - jekyll-feed
  - jekyll-paginate
  - jekyll-assets
  - jekyll-archives

paginate: 5
paginate_path: "/page:num/"
```

## Deployment

This site is deployed automatically via GitHub Pages.  
Push changes to the `main` branch and your site will update at:  
`https://Djasa2288.github.io`

---

**Happy Ending!**
```
