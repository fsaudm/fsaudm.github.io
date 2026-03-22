# fsaudm.github.io

Personal portfolio site for Farid Saud - Data Scientist | ML Engineer | AI Engineer.

## Structure

- `/` - Landing page with two routes
- `/hand/` - **Gesture Mode** - hand-gesture interactive resume powered by MediaPipe (vanilla JS, Canvas)
- `/resume/` - **Traditional** - classic resume format

## Stack

- **Landing page**: Standalone HTML/CSS (dark theme, corner-mark design)
- **Gesture Mode**: [HandCV](https://github.com/fsaudm/HandCV) - MediaPipe hand tracking, HTML5 Canvas, no build step
- **Traditional Resume**: [Jekyll](https://jekyllrb.com/) + [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)

## Local Development

```bash
# requires Ruby (Homebrew: brew install ruby)
bundle install
bundle exec jekyll serve --port 4000
```

## Inspiration

- [the.poet.engineer](https://www.instagram.com/the.poet.engineer/) - creative coding and interaction design
