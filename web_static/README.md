# Project Overview

This project creates an HTML page featuring a header, footer, a filter box with dropdown lists, and a section to display search results. The design focuses on user-friendliness and adheres to specified layout and style requirements. Multiple CSS files are used to maintain a modular structure and facilitate easy styling adjustments.

## Features

- **Header**: Includes a logo and navigation links.
- **Footer**: Positioned at the bottom of the page with contact information.
- **Filters Box**: Dropdown lists for locations and amenities, with a search button.
- **Search Results**: Displays detailed information about places matching the filters.

## Requirements

- Use specific HTML tags: `header`, `footer`, `section`, `article`, `button`, `h1`, `h2`, `h3`, `h4`, `ul`, `li`.
- No inline styles or `<style>` tags in the `<head>`.
- No `<img>` tags.
- Images must be stored in the `images` folder.
- Styles must be divided into:
  - `styles/4-common.css`: Global styles.
  - `styles/3-header.css`: Header styles.
  - `styles/3-footer.css`: Footer styles.
  - `styles/6-filters.css`: Filter styles.
  - `styles/8-places.css`: Place styles.

## Directory Structure

project-root/
├── images/
│ └── logo.png
├── styles/
│ ├── 4-common.css
│ ├── 3-header.css
│ ├── 3-footer.css
│ ├── 6-filters.css
│ └── 8-places.css
└── index.html


## Usage

1. **Setup**: Ensure all CSS files are correctly linked in the `index.html` file.
2. **Images**: Place the logo image (`logo.png`) in the `images` folder.
3. **Customization**: Modify the CSS files (`styles/*.css`) to customize the styles as needed.
4. **Deployment**: Host the entire project folder on a web server or open `index.html` in a web browser to view the page.

## License

This project is licensed under the [MIT License](LICENSE).

