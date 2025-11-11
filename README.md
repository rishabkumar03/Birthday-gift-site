# Birthday Gift Site  

A fun and creative web page designed as a **personalized birthday gift**. Built using pure HTML and CSS, this interactive site presents a heartfelt birthday greeting with surprise images revealed on hover.  

## Features  

- **Interactive Gift Boxes**: Each gift reveals a funny or expressive image when hovered  
- **Personalized Layout**: Includes birthday message, photo, and details of the birthday person  
- **Animated Background**: Gradient color scheme for a lively, celebratory feel  
- **Custom Fonts**: Uses Google Fonts for a playful and unique style  
- **Responsive Centered Design**: Layout aligned neatly using flexbox  

## Technologies Used  

- **Frontend**: HTML5, CSS3  
- **Fonts**: Google Fonts (Happy Monkey, Mukta, Snowburst One, Lato)  
- **Media**: Local images and GIFs for hover animations  

## Prerequisites  

No installation required — works on any modern web browser.  

## Installation  

1. Clone or download the project files:  
  ```bash
  git clone https://github.com/rishabkumar03/Birthday-gift-site
  cd birthday-gift-site
  ```
2. Place all image and GIF files (`bunnu.jpg`, `gift-cover.jpg`, etc.) in the same folder as the HTML file.
3. Open the project in your browser:
  ```diff
  index.html
  ```

## Usage

1. Open `index.html` in any browser.
2. Hover over each gift box to reveal the surprise image.
3. Scroll through each section to see different reactions and moments.
4. Enjoy the birthday wishes and humor built into the design!

## File Structure

  ```bash
  birthday-gift-site/
  ├── .gitattributes
  ├── bewakoof.gif
  ├── bunnu.jpg         # Birthday person's image
  ├── dog-food.gif
  ├── dog.gif
  ├── gift-cover.jpg    # Default gift box cover
  ├── headache-stupid-people.gif
  ├── index.html        # Main web page
  ├── spit-it-out-spit.gif
  └── styles.css        # Styling and hover animations
  ```

## How It Works

1. **Header Section:** Displays the title, image, and birthday details.
2. **Gift Sections:** Each section contains a hoverable div that reveals a unique image or GIF when hovered.
3. **Hover Effects:** CSS `:hover` changes the `background-image` dynamically to show hidden content.
4. **Footer:** Includes a contact link for others to request their own custom birthday gift site.

## Configuration

- To personalize the site:
  - Replace `bunnu.jpg` with your own image.
  - Edit text inside `<h1>`, `<h2>`, and `<h4>` in `index.html`.
  - Update GIFs or background colors in `styles.css`.

## Known Issues

1. **Fixed Width Layout:** May not scale perfectly on smaller mobile screens.
2. **GIF Loading Delay:** Depending on file size, hover GIFs may take a moment to appear.
3. **No Sound Effects:** Currently visual-only; sound or music could be added manually.

## Troubleshooting

### Images Not Showing

- Verify the image and GIF filenames match exactly with those referenced in `styles.css`.
- Keep all media files in the same directory as `index.html`.

### Layout Looks Off

- Clear browser cache or refresh after editing CSS.
- Use latest Chrome, Firefox, or Edge browser for best experience.

## Security Considerations

- Fully client-side — no personal data collected or stored.
- Safe to host or share publicly.

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Add your creative ideas or design improvements.
4. Test visually.
5. Submit a pull request.
