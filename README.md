# transformFunctions

## (Ryan Welzel 7/17/2025)

Implements a curve-based interpolation system for color and UI using SDL.

---

Features:
- Unified interpolation function for int, float, Uint8, and SDL_Color
- Modular easing curves: sigmoid, sine, easeIn/OutQuad, easeIn/OutCubic, and linear
- Customizable curveFunction interface to plug in new transition / type behaviors


Requirements:
- SDL2 development libraries
- C++17 or later for template and lambda support
