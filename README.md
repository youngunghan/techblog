# WENIVLOG

## Project Introduction

A service that allows you to easily create a blog using GitHub Pages. You can create your own blog by forking the repository to your own account.

## Development Information

- Developer: WENIV Corporation
- Version: v1.0.0

## Service URLs

- Manual Page: https://blog.weniv.co.kr/
- Blog Page (Example): https://weniv.github.io/weniv_blog/

## Sponsors

Support WENIV's activities and become a contributor with the price of a cup of coffee!

## Usage Guide

### Blog Setup

1. Fork this repository
2. Go to your repository and activate GitHub Pages in settings
3. Clone your repository to manage your blog

### Blog Management

1. Modify the config.js file in your cloned project folder
2. Enter GitHub information in siteConfig
3. Enter your information in users. Multiple users can manage the blog together by adding user information

### Writing Blog Posts

Blog posts should be written in the blog folder using the following format:
```markdown
[date]_[title]_[category]_[thumbnail]_[description].md
```

If not using a thumbnail:
```markdown
[date]_[title]_[category]_[].md
```

- Thumbnail paths can be managed in the img folder or using published image links
- Manage displayed posts by modifying `data/localBlogList.json`

### Menu Management

To manage the menu in the upper right:
- Create files in the menu folder as `desired_menu_name.md`
- Manage displayed menus by editing `data/local_blogMenu.json`

### Design Customization

- Modify `style/globalStyle.js` to customize overall styles
- Apply your own styles easily using Tailwind CSS
- WENIV Friends images and thumbnail illustrations are provided for profile use

## Folder Structure

| Folder | File | Function | Variable | Note |
|--------|------|----------|-----------|------|
| style | globalStyle.js | Global style settings | | |
| style | blogContentsStyle.js | Blog content style settings | | |
| JS | config.js | siteConfig | Site configuration | |
| JS | URLparsing.js | extractFromUrl() | url, pathParts, isLocal | URL parsing, schema verification |
| JS | render.js | renderBlogPosts(), renderMenu() | | Renders data to DOM |
| JS | initData.js | initDataBlogList(), initDataBlogMenu() | blogList, blogMenu | Initial data loading, schema verification |
