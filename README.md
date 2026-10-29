
# Colorado Climbing Fastest Known Times

**Website:** https://climbingfkt.com

An independent archive documenting verified fastest known times (FKTs) on technical rock climbing routes in Colorado.

## Purpose

Preserve the history of Colorado speed climbing by providing a centralized, searchable, and transparent record of climbing FKTs.

## Coverage

- Eldorado Canyon
- Flatirons
- Rocky Mountain National Park
- Other Colorado climbing areas

## Repository Structure

```text
/
├── _includes/                  # Reusable Jekyll components
│
├── _layouts/
│   ├── default.html            # Shared website layout
│   └── route.html              # Individual route layout
│
├── _routes/                    # Individual climbing route records
│
├── assets/
│   ├── css/
│   │   └── style.css           # Global dark theme
│   │
│   ├── images/
│   │   ├── eldo/
│   │   ├── rmnp/
│   │   ├── flatirons/
│   │   └── other-colorado/
│   │
│   └── gps/
│       ├── eldo/
│       ├── rmnp/
│       ├── flatirons/
│       └── other-colorado/
│
├── CNAME                       # Custom domain
├── README.md                   # Project documentation
├── _config.yml                 # Jekyll configuration
│
├── index.html                  # Homepage
├── eldo.html                   # Eldorado Canyon FKTs
├── flatirons.html              # Flatirons FKTs
├── rmnp.html                   # RMNP FKTs
├── other-colorado.html         # Other Colorado FKTs
├── about.html                  # About the project
├── submit.html                 # Submission instructions
│
├── robots.txt                  # Search engine crawling
└── sitemap.xml                 # Search engine indexing
```

## Record Organization

### Regional Pages

Display current FKTs for each climbing route, linking to individual route pages for additional details.

### Individual Route Pages

Document current and historical FKTs, including:

- Route name, location, and climbing grade
- Athlete names and record dates
- Elapsed times and climbing styles
- Defined start and finish points
- Historical record progression
- Verification evidence and original sources

## Verification Standards

FKT submissions should include verifiable primary-source evidence whenever available:

- Original GPS activity (GPX/FIT or Strava)
- Athlete-submitted trip report
- Route, date, elapsed time, and climbing style
- Clearly defined start and finish points
- Split times when available

Historical records without GPS evidence are evaluated individually using available primary sources.

## Project Principles

- Accuracy and transparency
- Consistent route and timing definitions
- Attribution to original sources
- Athlete permission for reproduced content
- Preservation of historical climbing achievements

## Technology

- GitHub Pages — Website hosting
- Jekyll — Static site generator
- Markdown, HTML, and CSS — Website content and styling
- Cloudflare — Custom domain and DNS management

## Contact

[contact@climbingfkt.com](mailto:contact@climbingfkt.com)

## Copyright

© 2026 Climbing FKT. All rights reserved.

Website content and photographs may not be reproduced without permission from their respective copyright holders.
