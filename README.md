# Mouse and Keyboard Listener 

This script demonstrates the use of the `pynput` library to create mouse and keyboard event listeners in Python. It captures various mouse and keyboard events and provides a way to respond to them.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Functionality](#functionality)
    - [Mouse Events](#mouse-events)
    - [Keyboard Events](#keyboard-events)

## Prerequisites

- Python 3.7+
- Required Python packages: `pynput`

## Usage

1. Install the required package using `pip install pynput`.
2. Copy the provided code into your Python script or file.
3. Customize the event handler functions as needed for your use case.
4. Run the script using `python your_script_name.py`.

## Functionality

### Mouse Events

The script captures the following mouse events:
- **Mouse Move**: The `on_move` function is called when the mouse is moved. This function can be customized to respond to mouse movement.

- **Mouse Click**: The `on_click` function is called when a mouse button is clicked. The `button` parameter indicates which button was clicked, and the `pressed` parameter indicates if the button was pressed or released. This function can be customized to respond to mouse clicks.

- **Mouse Scroll**: The `on_scroll` function is called when the mouse wheel is scrolled. The `dx` and `dy` parameters indicate the scroll direction. This function can be customized to respond to mouse scroll events.

### Keyboard Events

The script captures the following keyboard events:
- **Key Press**: The `on_press` function is called when a key is pressed. This function can be customized to respond to key presses.

- **Key Release**: The `on_release` function is called when a key is released. This function can be customized to respond to key releases.

### Purpose and Advantages

The script provides a way to create event listeners for both mouse and keyboard events. This can be used for various purposes such as creating automation scripts, monitoring user activity, and more. The script's modular structure allows you to easily customize event handlers to suit your specific requirements.

**Advantages:**
- Offers cross-platform support for capturing mouse and keyboard events.
- Easy-to-use and well-documented `pynput` library simplifies event handling.
- Can be integrated into various applications to add user interaction features.

---

Feel free to explore and modify the code to suit your needs. It's a useful tool for capturing and responding to mouse and keyboard events in your Python programs.
![Running GIF](  https://raw.githubusercontent.com/trinib/trinib/82213791fa9ff58d3ca768ddd6de2489ec23ffca/images/footer.svg)
