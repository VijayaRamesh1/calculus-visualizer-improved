# Calculus Visualizer - Enhanced Accessibility Version

This repository contains an enhanced version of the Calculus Visualizer tool, focusing on improved accessibility, usability, and inclusive design principles. The goal is to make interactive calculus learning more accessible to all users, regardless of their abilities or disabilities.

## Key Accessibility Improvements

The enhanced version includes the following accessibility features based on WCAG 2.1 guidelines:

### Perceptibility Enhancements
- **Improved Color Contrast**: All text elements meet WCAG 2.1 AA contrast requirements (4.5:1 for normal text).
- **Dark Mode**: Added a high-contrast dark theme option for users with visual sensitivity.
- **Alt Text**: Descriptive alternative text for all non-decorative images.
- **Semantic Structure**: Proper HTML5 semantic elements and ARIA landmarks.
- **Text Alternatives**: Mathematical formulas include descriptive text alternatives.
- **Screen Reader Support**: ARIA attributes and roles for improved screen reader navigation.

### Operability Enhancements
- **Keyboard Navigation**: Full keyboard accessibility for all interactive elements.
- **Skip Links**: Added skip navigation links for keyboard users.
- **Focus Indicators**: Enhanced visual focus states for keyboard navigation.
- **Reduced Motion**: Respects user preferences for reduced motion.
- **Keyboard Shortcuts**: Added keyboard shortcuts for common actions with a visible help modal.
- **Responsive Design**: Improved layout for different devices and screen sizes.

### Simplicity Improvements
- **Clear Instructions**: Explicit instructions for interactive elements.
- **Consistent Layout**: Standardized navigation patterns throughout the application.
- **Progressive Disclosure**: Complex interactions are broken down into manageable steps.
- **Simplified UI**: Reduced visual clutter and improved information hierarchy.

### Forgiveness Features
- **Error Prevention**: Confirmation dialogs for significant actions.
- **Clear Feedback**: Visual and auditory feedback for user actions.
- **Undo Options**: Added ability to reset parameters and visualizations.
- **Helpful Error Messages**: Clear error messages with recovery suggestions.

## UX Design Principles Implemented

The redesign follows key UX principles:

- **Aesthetic-Usability Effect**: Improved visual design for a more appealing interface.
- **Affordance**: Clear visual cues for interactive elements.
- **Consistency**: Maintained consistent patterns throughout the interface.
- **Constraints**: Limited options in complex interactions to prevent errors.
- **Control**: Provided users with control over the visualization environment.
- **Cost-Benefit**: Optimized interactions for maximum benefit with minimal effort.
- **Entry Point**: Simplified initial experience with clear points of entry.
- **Feedback Loop**: Immediate and clear feedback for all user actions.
- **Flexibility-Usability Tradeoff**: Balanced flexibility with usability for different user needs.
- **Legibility**: Improved typography and text layout for better readability.
- **Mapping**: Created intuitive relationships between controls and their effects.
- **Mental Model**: Aligned interface with users' existing understanding of calculus concepts.
- **Ockham's Razor**: Simplified design elements where possible.
- **Performance Load**: Reduced cognitive effort through clear organization.
- **Proximity**: Grouped related elements for better understanding.
- **Recognition Over Recall**: Used familiar patterns and clear labels.
- **Signal-to-Noise Ratio**: Minimized distractions and highlighted important information.
- **Visibility**: Made system status and available actions clearly visible.

## Structure

The repository is organized as follows:

- `index.html`: Main entry point with accessible cards for each calculus module
- `assets/`: Contains CSS, images, and other static assets
- `core/`: Core JavaScript functionality including the enhanced UI core
- `modules/`: Individual calculus visualization modules
  - `projectile-motion/`: Enhanced projectile motion visualization
  - (Other modules to be adapted)
- `accessibility.html`: Accessibility statement and guide

## Getting Started

1. Clone the repository
2. Open `index.html` in your web browser
3. Explore the different calculus modules

## Accessibility Statement

This project is committed to WCAG 2.1 AA compliance. See our [Accessibility Statement](accessibility.html) for details on our approach to accessibility and known limitations.

## License

MIT

## Credits

Based on the original Calculus Visualizer by VijayaRamesh1, with accessibility enhancements.
