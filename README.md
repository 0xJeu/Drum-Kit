# Drum-Kit

<img width="1440" alt="Screenshot 2023-06-19 at 2 04 24 PM" src="https://github.com/0xJeu/Drum-Kit/assets/129988927/62b88e2c-ee6e-4710-ab02-9bfb3199faca">

This JavaScript code creates a simple drum kit application that responds to user clicks on drum elements or keypress events. Each drum element produces a unique sound, and the corresponding key on the keyboard triggers the same sound.

## How It Works

- The code uses a loop to iterate through all the elements with the class "drum" and adds a click event listener to each element. When a drum element is clicked, the `makeSound()` and `buttonAnimate()` functions are called.

- The code also adds a keypress event listener to the whole document. When a key is pressed, the `makeSound()` and `buttonAnimate()` functions are called.

- The `makeSound()` function takes the clicked drum element or key as an argument and plays the corresponding sound based on the key value. It uses a `switch` statement to determine which sound to play based on the key value.

- The `buttonAnimate()` function takes the current key or drum element as an argument. It adds a CSS class called "pressed" to the corresponding drum element or key element. This class adds a visual effect to indicate that the drum or key has been pressed. After a brief delay of 100 milliseconds, the function removes the "pressed" class.

## Example Output

Example output when the "w" key or the corresponding drum element is clicked:

- The "w" key is pressed or the drum element with the letter "w" is clicked.
- The sound file "sounds/tom-1.mp3" is played.
- The corresponding drum element or key element receives the "pressed" class, creating a visual effect.

## Acknowledgments

This code is a simple implementation of a drum kit using JavaScript. Feel free to modify and expand it according to your preferences and requirements.
