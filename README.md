# Zenhanced

A sleek, minimalist Firefox CSS customization that enhances the Zen Browser interface with clean aesthetics and smooth transitions.

## Features

### UI Enhancements

#### Hidden Elements
- Removed unnecessary buttons and UI elements for a cleaner interface
- Hidden tab icon overlays for a more consistent look

#### URL Bar Styling
- Centered URL bar with 40vw width
- Centered text input for better aesthetics
- Subtle opacity change on hover (0.85 to 1)
- Transparent background when not focused
- Sleek border-radius of 3px
- Smooth focus transitions with box-shadow effect

#### Tab Styling
- Clean, transparent backgrounds for tabs
- Border highlighting for selected tabs
- Tab close buttons appear only on hover
- Smooth background color transitions on hover
- Fade animations for tab elements

#### Navigation and Control Elements
- Streamlined navigation buttons
- Scale animations on hover for interactive elements
- Smooth opacity transitions for all control elements

#### Sidebar Elements
- Dynamic sidebar splitter that expands on hover
- Organized sidebar buttons with proper ordering
- Transition effects for all sidebar elements
- Hidden workspace indicators with preserved spacing for cleaner layout

#### Panel and Status Elements
- Enhanced status panel with rounded corners
- Transition effects for panel elements

#### Background and Window Styling
- Semi-transparent main window for a modern look
- Transparent navigator toolbox
- Smooth background transitions

#### CtrlTab Panel
- Completely redesigned Ctrl+Tab panel
- Thumbnails scale on hover for better feedback
- Removed favicon containers for cleaner appearance
- Smooth transitions between tabs

### Start Page Customizations

#### Custom Start Page Background
- Zen logo watermark with 15% opacity
- Background animates subtly on hover
- Different styling for regular and private browsing modes

#### Search Area Enhancements
- Centered search bar with glass-like effect
- Backdrop filter blur effects
- Search bar scales slightly on hover
- Box-shadow effects on hover for visual feedback
- Rounded corners (3px border-radius)

#### Logo and Wordmark
- Subtle animations for logo elements
- Scale and opacity changes on hover

### Animation System

- Comprehensive transition system for all UI elements
- Consistent animation timing (0.2s-0.4s durations)
- Easing functions for natural movement
- Scale, opacity, and color transitions
- Hover effects throughout the interface

## Installation

1. Navigate to `about:config` in Firefox
2. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
3. Find your Firefox profile folder:
   - Go to `about:support`
   - Click "Open Directory" next to "Profile Directory"
4. Create a `chrome` folder in your profile directory if it doesn't exist
5. Copy `userChrome.css` and `userContent.css` into the `chrome` folder
6. Restart Firefox

## Config Optimization

These styles are intended to work with some specific configurations in Zen Browser:

- `toolkit.legacyUserProfileCustomizations.stylesheets` set to `true`
- `zen.view.compact` set to `true` (for compact mode)
- `zen.view.compact.hide-tabbar` set to `true` (for compact mode)
- Enable "Ctrl+Tab cycles through tabs in recently used order"
- Home Page > Firefox default
- Keybindings navigation-based (you should customize them)
- Not using workspaces (yes, I know, but I don't need them)
- Not using light theme (yes, I know, but I don't need it)

## Acknowledgments

This project is derived from [Zenplified](https://github.com/sejjy/zenplified) by sejjy. 
All credit for the original concept and foundation goes to them.