# Attention Span
Welcome to the **Attention Span** repository! This project is a simple web-based animation designed to help users practice mindfulness and focus by guiding them through a breathing exercise and attention span boosting exercises.

## TODO
1. Filtered calming sine wave
2. Mini-games (space hold timing rhythm game etc.)
3. Migrate to other stack

## How It Works

The project is built using HTML, CSS, and JavaScript:

- **HTML**: The structure includes a `div` for the animated circle and a container for the text prompts.
- **CSS**: Keyframe animations are used to create the breathing effect and text fade-in/fade-out transitions. The circle's color and size are dynamically adjusted using CSS variables.
- **JavaScript**: A simple script updates the circle's color and gradually increases the duration of the breathing animation over time.

## Usage

To use this project, simply open the `index.html` file in your web browser. The animation will start automatically, and you can follow the text prompts to practice mindful breathing.

### Customization

You can customize the animation by modifying the CSS variables in the `:root` selector:

- `--animation-duration`: Controls the speed of the breathing animation.
- `--hue`: Adjusts the base color of the circle.

For example, to make the animation slower, you can increase the `--animation-duration` value:

```css
:root {
    --animation-duration: 10s;
}
```

## Contributing

Contributions are welcome! If you have any ideas for improving the animation, adding new features, or enhancing the user experience, feel free to open an issue or submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as you see fit.

---

Enjoy the **Attention Span** experience, and take a moment to breathe and focus! 🌬️
