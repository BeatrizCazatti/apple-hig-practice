# Liquid Glass

- Creates the feeling of a single, continuous surface.
- Its effects provide flexibility, fluidity, responsiveness, and dynamic movement.
- Interactions react naturally to touch and motion, making the interface feel alive and connected to the physical world.
- When a user taps a button, elements like modals can emerge from that button, reinforcing the perception that the interface is physically connected.
- Translucency allows users to perceive content, depth, volume, and controls behind the material while maintaining context and hierarchy.
- Floating sidebars, toolbars, navigation bars, and layered surfaces create a sense of spatial depth and overlapping views.
- Multiple layers adapt together automatically to preserve clarity, focus, and hierarchy within the UI.
- Scroll Edge Effects dynamically adjust background appearance and contrast to maintain legibility across lighter and darker content.

## Material Composition 
Liquid Glass continuously communicates depth and legibility through multiple visual layers:

1. Highlight layer
    - Produces reflections and shine across the material.
    - Highlights react to geometry, lighting, and sometimes device movement.
    - This creates the sensation that the material exists in physical space and responds to the user’s position.
2. Shadows
    - Shadows adapt according to the content behind the material.
    - For example, opacity may increase when positioned over text to preserve readability.

## Attention
- Avoid applying Liquid Glass material to every layer simultaneously.
- Instead, combine fills, transparency, and vibrancy effects so foreground elements feel integrated with the material rather than disconnected from it.

## Liquid Glass Variants
- **Regular:** Works well in most interfaces and contexts.
- **Clear:** Uses less adaptive behavior and more transparency. Allows underlying content to remain more visible and vibrant. Works especially well for:
    - media-rich interfaces
    - dimmed overlays
    - bold and colorful backgrounds

## Legibility and Adaptation
- Content dynamically adapts contrast between light and dark environments.
- Smooth transitions reinforce the feeling of fluid and adaptive surfaces.
- The material continuously maintains readability while preserving visual continuity.

## Tinting
- Use tinting to emphasize primary actions, important interactions, or meaningful states.
- If every element is tinted, nothing stands out.
- To introduce stronger color identity into your app, prefer applying color within the content layer rather than throughout the entire material system.

## Touch Interaction
- Buttons are designed with touch proportions in mind, reinforcing the feeling that elements are physically interactive and comfortable to tap.

## Accessibility
Liquid Glass includes accessibility adaptations that improve clarity and comfort:
- Reduce Transparency: makes materials more opaque to improve visibility and contrast.
- Increased Contrast: enhances borders and separation between elements.
- Reduce Motion: reduces animation intensity and disables some elastic material behaviors.