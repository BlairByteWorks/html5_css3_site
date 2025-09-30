HTML5 + CSS3 + Docker Practical - Blair's Jersey Store

This site demonstrates HTML5 features, CSS3 styling, media elements and Docker containerization.

Pages

1.	index.html — Semantic structure, skip link, headings, quotes, time, abbr, code/kbd/samp
2.	about.html — Sections, lists, definition lists, internal links
3.	media.html — `<picture>` responsive image, audio, and video
4.	extras.html — Tables (caption/thead/tbody/tfoot), <details>, <dialog>, <progress>, <meter>

Live site: https://blairbyteworks.github.io/html5_css3_site/

Features

⦁	Semantic HTML5 structure with proper headings
⦁	Skip link present and functional
⦁	Responsive navigation with Flexbox
⦁	CSS Grid layout for main content
⦁	CSS custom properties (variables) for theming
⦁	Responsive images via `<picture>` element
⦁	Audio and video
⦁	Accessible tables with proper semantics
⦁	Docker containerization with nginx
⦁	W3C HTML & CSS validation passing

Design Tokens

The site uses CSS custom properties for consistent theming:
⦁	Colors: --bg, --fg, --muted, --brand, --brand-contrast
⦁	Typography: --font-sans, --font-mono, --h1, --h2, --body
⦁	Spacing: --space-1 through --space-5

Responsive Breakpoints

⦁	Mobile: < 480px (single column, stacked navigation)
⦁	Tablet: 480px - 1024px (adjusted spacing)
⦁	Desktop: > 1024px (grid layout with sidebar)

Accessibility Features

⦁	Skip to main content link
⦁	Proper heading hierarchy (H1-H6)
⦁	Reduced motion preferences respected
⦁	Semantic HTML throughout


Docker Commands

1.	Build the image:

docker build -t blairbytesworks/html5_css3_site .

2.	Run the container:
docker run --rm -p 8080:80 blairbytesworks/html5_css3_site

3.	Push to docker:
docker push blairbytesworks/html5_css3_site

docker tag blairbytesworks/html5_css3_site blairbytesworks/html5_css3_site:latest

   docker push blairbytesworks/html5_css3_site:latest


Deliverables

Live GitHub Pages URL: https://blairbyteworks.github.io/html5_css3_site/

GitHub Repository Link:

Published Docker Image: https://hub.docker.com/repository/docker/blairbytesworks/html5_css3_site/tags
