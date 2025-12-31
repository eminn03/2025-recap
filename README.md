# 2025 Recap - Interactive Year in Review

An immersive, web-based storytelling experience to showcase your yearly memories, statistics, and highlights. Designed with an interface similar to Instagram/Snapchat stories, featuring smooth CSS animations, progress bars, and background audio.

## About The Project

This project serves as a personal portfolio piece or a creative way to share your year's summary. It is built with:
- **HTML5** for structure.
- **CSS3** for animations, responsive design, and particles.
- **Vanilla JavaScript** for story navigation and logic.

## A Unique Digital Gift Idea

**Looking for a meaningful, non-material New Year's gift?** This project is the perfect template to create a sentimental **digital time capsule** for your loved ones (partner, best friend, or family).

* **Make it Personal:** Replace the text with inside jokes, shared memories, and milestones you reached together.
* **Visual Memories:** Add photos from your trips or special moments in the photo grid section.
* **The Soundtrack of Your Year:** Use songs that have a special meaning for both of you in the `music/` folder.
* **The Reveal:** Deploy the site and send them the link exactly at midnight on New Year's Eve! 🕛

## Use as a Template

You are welcome to use this repository as a template for your own "Year in Review"

### How to Setup

1.  **Clone or Download** this repository.
2.  **Edit `index.html`**:
    - Update the text content (H1, p tags) with your own memories.
    - Change the colors in the inline `style="background: ..."` attributes to match your mood.
3.  **Add Your Photos**:
    - Replace the background images or the photo grid images with your own.

### Important: Music & Image Setup

To keep the repository lightweight, example music and image files are **not included**. You must add your own audio files for the experience to work correctly.

1.  Copy your musics into folder named `music` and images (must be .jpg , otherwise you must edit the code) to folder named `images` in the root directory.
2.  **Naming Convention**: The code expects specific filenames corresponding to each story slide index (starting from 0).
    - `story1.mp3` (for the first slide)
    - `story2.mp3` (for the second slide)
    - ...and so on.
    
**Directory Structure:**
```text
2025-recap/
├── index.html
├── README.md
├── images/
    ├──story1.jpg
    ├──story2.jpg
    ├──story3.jpg
    └── ...
└── music/           
    ├── story1.mp3
    ├── story2.mp3
    ├── story3.mp3
    └── ...
```

## Features

- **Responsive Design**: Works seamlessly on desktop and mobile.
- **Touch & Keyboard Support**: Touch/Swipe on mobile or use Arrow keys on desktop to navigate.
- **Progress Bars**: Auto-filling indicator for each story segment.
- **Audio Integration**: Individual background tracks for specific stories.
- **Particle Effects**: CSS-based animated backgrounds.
