# Hirst-Painting

A Python program that creates dot paintings inspired by Damien Hirst's spot paintings using the Turtle graphics library. The program extracts colors from an image and uses them to create a grid of colored dots.

## Features

- Extracts colors from an image using `colorgram` library
- Creates a 10x10 grid of dots
- Each dot has a diameter of 20 pixels
- Uses random colors from the extracted palette
- Turtle graphics for visual output

## Components

- [`main.py`](main.py): Creates the dot painting using Turtle graphics
- [`extract_colors.py`](extract_colors.py): Extracts RGB colors from an input image

## Python Concepts Implemented

- **Turtle Graphics**: Using the turtle library for drawing
- **Color Handling**: RGB color management and colormode
- **Random Selection**: Choosing random colors from a palette
- **List Operations**: Storing and managing color data
- **Functions**: Modular code organization
- **Loops**: Creating grid patterns

## How It Works

1. Color Extraction:
   - Uses `colorgram` to extract 30 colors from source image
   - Converts colors to RGB tuples
   - Stores colors in a list

2. Painting Creation:
   - Sets up Turtle graphics window
   - Creates 10x10 grid of dots
   - Each dot is randomly colored from extracted palette
   - 50 pixel spacing between dots

## Usage

1. First extract colors from your image:
```python
python extract_colors.py
```

2. Then create the painting:
```python
python main.py
```

## Dependencies

- Python 3.x
- turtle (built-in)
- colorgram.py (`pip install colorgram.py`)
