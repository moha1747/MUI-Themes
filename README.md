# Theme Utility Files

## Overview

This repository includes utility files for implementing dynamic theme toggling (light and dark modes) in a React application using Material-UI.

## Files

- **theme.js**: Defines the theme settings for light and dark modes.
- **ThemeProviderWrapper.js**: Provides a theme context and toggle functionality throughout the application.

## Usage

### Theme Configuration (`theme.js`)

This file exports a `getTheme` function that generates a theme object based on the specified mode (`light` or `dark`).

```javascript
import { getTheme } from './theme';
const theme = getTheme('light');  // Use 'dark' to get the dark theme
