# Noucake Demo Data

Demo data for Noucake WordPress theme

## Structure
- `demo1/` - Demo 1 data
  - `content.xml` - WordPress content export file
  - `widgets.wie` - Widget settings
  - `theme-options.txt` - Theme options
  - `screenshot.png` - Demo preview image
  - `uploads/` - Media files
  - `images/` - Theme images

## Usage

The demo data is served via GitHub raw content:

```
https://raw.githubusercontent.com/nouthemes/demo-noucake/main/demo1/
```

## Upload Instructions

1. Initialize git in this directory: `git init`
2. Add all files: `git add .`
3. Commit: `git commit -m "Add demo data"`
4. Add remote: `git remote add origin https://github.com/nouthemes/demo-noucake.git`
5. Push to main: `git branch -M main && git push -u origin main`
