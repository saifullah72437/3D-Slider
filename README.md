# 3D-Slider
It is a 3D slider using HTML CSS and 3D geometry 💚

![image](https://github.com/user-attachments/assets/b9a6fe5f-a428-4350-aafb-8c49726de66f)
![image](https://github.com/user-attachments/assets/047b8691-daaf-436e-b1ae-7bf172c09244)
![WhatsApp Image 2024-07-14 at 1 58 01 AM](https://github.com/user-attachments/assets/23beb4af-0bd1-4ff9-87e9-3be028c76bc6)


# 🎨 CSS Only Rotating Image Slider

Welcome to the **CSS Only Rotating Image Slider** project! This project showcases a rotating image slider using only CSS, with a focus on animations and styling. Below you'll find detailed explanations of the code and the features implemented.

## 📂 Project Structure

The project consists of the following files:

- `index.html`: The main HTML file containing the structure of the webpage.
- `style.css`: The CSS file for styling and animations.

## 📄 index.html

### HTML Structure

The HTML file consists of the following sections:

1. **Head Section**:
    - Meta tags for character set and viewport settings.
    - Title of the webpage.
    - Inline CSS for background styling.
    - Link to the external CSS file (`style.css`).

2. **Body Section**:
    - A `div` with the class `banner` containing:
        - A `div` with the class `slider` which includes multiple `div` elements with the class `item`, each containing an image.
        - A `div` with the class `content` which includes:
            - An `h1` tag for the title "CSS ONLY".
            - A nested `div` with the class `author` which contains:
                - An `h2` tag for the author name "SAIF".
                - Paragraphs for additional information.

### CSS Styling

The CSS file is imported using `@import` rules for fonts from external sources.

#### General Styling

- `*`: Sets margin, padding, and box-sizing for all elements.
- `body`: Sets the background color and applies a repeating linear gradient for the background pattern.
- `body::before`: Adds a background image overlay for decorative purposes.

#### Banner Section

- `.banner`: Sets the dimensions, text alignment, overflow, and position.
- `a`: Sets the cursor to pointer for all anchor tags.

#### Slider Animation

- `.banner .slider`: Defines the size, position, and 3D transformation of the slider. An animation (`autoRun`) is applied for continuous rotation.
- `@keyframes autoRun`: Specifies the rotation animation from 0 to 360 degrees.

#### Item Styling

- `.banner .slider .item`: Positions each item within the slider and applies a 3D transformation.
- `.banner .slider .item img`: Sets the dimensions and object-fit property for images.

#### Content Styling

- `.banner .content`: Positions and styles the content section, including the title and author information.
- `.banner .content h1`: Sets the font, size, line-height, and color for the title. An `::after` pseudo-element is used to create an outline effect.
- `.banner .content .author`: Styles the author information with specific fonts and alignment.

#### Responsive Design

- Media queries are used to adjust the layout and styling for different screen sizes (`max-width: 1023px` and `max-width: 767px`).

### Responsive Adjustments

- For screens with a maximum width of 1023px, the slider and content are resized, and text alignment and shadow effects are adjusted.
- For screens with a maximum width of 767px, further adjustments are made to the slider and content sizes.

## 🚀 Getting Started

To view the rotating image slider, simply open the `index.html` file in your web browser. Ensure that you have the images available in the specified path (`images/`).



## 📝 Author

- **Saifullah Khan**
- Follow me on [LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/saifullah-khan-4aa554231/))


---

Feel free to explore and modify the code to suit your needs. Happy coding! 🎉
