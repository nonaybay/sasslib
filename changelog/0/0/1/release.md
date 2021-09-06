# Release v0.0.1

* Function to get the linear version of an color. `linear-srgb($color)`
* Function to get the luminance of an color. `get-luminance($color)`
* Function to calculate the contrast-ratio between two colors. `contrast-ratio($color-a, $color-b)`
* Function to determine if the color is considered "light" or "dark". `get-tone($color)`
* Function to determine the best "ratio" based on level ("A", "AA", "AAA"), font size and weight ("bold: true or false"). `get-ratio($level, $size, $bold, $forced)`
* Function that returns the most accessible color according to your foreground, background, level, font size and weight. `a11y-color($foreground, $background, $level, $size, $bold, $forced)`
* Function to convert a color into its web-safe version. `websafe-color($color)`