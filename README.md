# Pixel Light Effects

A lightweight JavaScript library for creating pixelated light ray effects for games, websites and applications.

## Features

- Customizable light rays with control over shape, angle and color
- Pixelated rendering for retro and artistic style
- Light points to create complex atmospheres
- Simple and easy to use API

## Usage

```html
<div id="light-container" style="width: 500px; height: 300px; position: relative;"></div>

<script src="LightRay.js"></script>
<script>
  // Create a canvas inside the container
  const lightEffect = new PixelLight.LightRay('light-container', {
    pixelSize: 6,
    angle: 45,
    direction: 270,
    centerColor: '#ffffff',
    midColor: '#f5d76e',
    edgeColor: '#996633',
    noise: 0.2
  });
  
  // Add light points if desired
  lightEffect.addLightPoint(0.3, 0.4, 10, 0.8);
</script>
