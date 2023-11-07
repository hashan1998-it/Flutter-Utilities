# Responsive Design Utility in Flutter

This code provides methods for achieving responsive design in Flutter applications. It is based on Figma design dimensions and allows you to adapt padding, margin, font sizes, and image sizes to different screen sizes.

## Constants
```dart
FIGMA_DESIGN_WIDTH: //Width of the design template in Figma (default: 414).
FIGMA_DESIGN_HEIGHT: //Height of the design template in Figma (default: 896).
FIGMA_DESIGN_STATUS_BAR: //Height of the status bar in the design template (default: 0).
```

## Functions
```dart
getHorizontalSize(double px): // Sets horizontal padding, margin, or width based on viewport width.
getVerticalSize(double px): // Sets vertical padding, margin, or height based on viewport height, accounting for status and bottom bars.
getFontSize(double px): ///Sets text font size based on viewport, considering both vertical and horizontal scaling.
getSize(double px): // Determines the smallest size for image height and width, considering both vertical and horizontal scaling.
```

## Usage
Use these functions to ensure your Flutter app's layout and elements adapt to various screen sizes, making your app responsive to different devices. Simply input pixel values, and the functions will calculate the appropriate sizes based on Figma design dimensions and screen properties.
