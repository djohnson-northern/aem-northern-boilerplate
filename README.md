# Your Project's Title...
For projects that want a few more batteries. Built by the team who brought you da.live and adobe.com.

## Environments
- Preview: https://main--aem-northern-boilerplate--djohnson-northern.aem.page/
- Live: https://main--aem-northern-boilerplate--djohnson-northern.aem.live/

## Documentation

Before using the aem-boilerplate, we recommand you to go through the documentation on https://www.aem.live/docs/ and more specifically:
1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `aem-northern-boilerplate` directory in your favorite IDE and start coding :)

## Getting started

### 1. Github
1. Use this template to make a new repo.
1. Install [AEM Code Sync](https://da.live/bot).

### 2. DA content
1. Browse to https://da.live/start.
2. Follow the steps.

### 3. Local development
1. Clone your new repo to your computer.
1. Install the AEM CLI using your terminal: `sudo npm install -g @adobe/aem-cli`
1. Start the AEM CLI: `aem up`.
1. Open the `aem-northern-boilerplate` folder in your favorite code editor and buil something.
1. **Recommended:** Install common npm packages like linting and testing: `npm i`.

## Features

### Localization & globalization
* Language only support - Ex: en, de, hi, ja
* Region only support - Ex: en-us, en-ca, de-de, de-ch
* Hybrid support - Ex: en, en-us, de, de-ch, de-at
* Fragment-based localized 404s
* Localized Header & Footer
* Do not translate support (#_dnt)

### Flexible section authoring
* Optional containers to constrain content
* Grids: 1-6
* Columns: 1-12
* Color scheme: light, dark
* Gap: xs, s, m, l, xl, xxl
* Spacing: xs, s, m, l, xl, xxl
* Background: token / image / color / gradient

### Base content
* Universal buttons w/ extensive styles
* Images w/ retina breakpoint
* Color scheme support: light, dark
* Modern favicon support
* New window support
* Deep link support
* Modal support

### Header and footer content
* Brand - First link in header
* Main Menu - First list in header
* Actions - Last section of header
* Menu & mega menu support
* Disable header/footer via meta props

### Scheduled content
* Schedule content using spreadsheets

### Sidekick & pre-production
* Quick Edit
* Extensible plumbing for plugins
* Schedule simulator
* Convert production links to relative

### Performance
* Extensible LCP detection

### Developer tools
* Environment detection
* Extensible logging (console, coralogix, splunk, etc.)
* Buildless reactive framework support (Lit)
* Hash utils patterns (#_blank, #_dnt, etc)
* Modern CSS scoping & nesting
* AEM Operational Telemetry

### Operations
* Cloudflare Worker reference implementation

## Patterns
### Page
A page is what holds your content. It can be styled using a metadata property called `template` which will load styles that apply to the entire page.

### Section
A section is a sub-section of your page. It can be styled using a `section-metadata` block. A section will control the layout of blocks.

### Block
Blocks are children of sections. A block adds visual context to parts of a page.

### Auto Block
An auto block is a block generated from a pre-defined piece of content. Often times from a link that matches a particular pattern. Link-based auto blocks can be helpful when additional nesting of content is required.

### Default content
Default content is content that lives outside a block.

## Design System

### Spacing & Gap
XS, S, M, L, XL, XXL

### Emphasis
quiet, default, strong, negative

### Buttons
accent, primary, secondary, negative
(w/ outline variations)

### Columns
1 - 12

### Grid
1 - 6

### Color tokens
blue, gray, green, magenta, organge, red, purple, yellow
(w/ 100-900 variations)

### Color schemes
light, dark
