# Color

## Best Practices
- Each color communicates its own meaning, such as status or interactivity, so avoid using the same color for different purposes.
- Consider providing system color variables for different appearance and contrast contexts, such as Light Mode, Dark Mode, and high contrast settings.
- Test your app on a sunny day (when colors can look darker and muted) and in dim lighting (when colors can appear lighter and more saturated) to provide an optimal viewing experience across different lighting conditions.
- Be aware of display technologies on different devices, such as True Tone displays and various TV standards like HD and 4K. For developer guidance, see(UIWhitePointAdaptivityStyle)[!https://developer.apple.com/documentation/BundleResources/Information-Property-List/UIWhitePointAdaptivityStyle]
- You can also test your app’s appearance using different color profiles on a Mac — such as P3 and Standard RGB (sRGB) — by choosing a profile in System Settings > Displays. For more information, see Color Managment.
- **Color management** keeping colors consistent across different screens can display different amounts of color:
    - sRGB - show fewer colors
    - P3 - show more vibrant/richer colors
- Consider how translucency effects and artwork affect your app’s identity to maintain visual continuity.
- Use (Color Picker)[!https://developer.apple.com/documentation/SwiftUI/ColorPicker] to let users choose colors while maintaining a consistent user experience.

## Attention
- Be sure to provide the same information in alternative ways so people with color blindness, or other visual disabilitieas or neither in other countries and cultures can understand it. Using Inclusive Colors and sufficient contrasts 

## System colors
- Avoid hardcoding system color values. But use semantic color design: “what is this element’s role?” instead of "what exact color should this be?", when the system decides:
    - proper contrast
    - proper appearance
    - adaptation for accessibility
- System colors are semantic-based (purpose), not appearance-based.
- Example:
    - background colors → hierarchy/depth
    - label colors → foreground content
    - separator colors → dividers
- Don’t redefine the purpose of semantic system colors.
- Avoid using:
    - separator color as text color
    - secondary label color as background color

## Liquid Glass Color
- You can apply color to some Liquid Glass elements, for drawing emphasis to a specific control, like a primary call to action, and is the approach the system uses for prominent button styling.
- If you apply color, reserve it for elements that truly benefit from emphasis, such as status indicators or primary actions.
-  If your app features colorful backgrounds or visually rich content, prefer a monochromatic appearance for toolbars and tab bars, or choose an accent color with sufficient visual differentiation.

