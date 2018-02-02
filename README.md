# Custom Reveal.js Template

Cloned from reveal.js @3.6.0

Changed:
   - Added modified chalkboard plugin and audio plugin (for playing back chalkboard.
      - Added size config to chalkboard.
      - Removed chalkboard texture.
      - Changed hotkeys around.
      - Audio plugin only configured for chalkboard playback.
         - Long duration, no auto switching to next fragment/slide.
         - Audio controls are completely hidden.
   - Customized markdown to ignore frontmatter (for use with VS Code Markdown Preview Enhanced)
   - Added custom css for flexboxes to allow aligned right/left images.