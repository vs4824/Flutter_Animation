# Flutter Animation

## High quality pre-built Animations for Flutter

This package contains pre-canned animations for commonly-desired effects. The animations can be customized with your content and dropped into your application to delight your users.

To see examples of the following animations on a device or simulator:

   ```
   cd example/
flutter run --release
```

## Material motion for Flutter

Material motion is a set of transition patterns that help users understand and navigate an app. For more information on the patterns and how to choose between them, check out the Material motion system spec.

A codelab, Building Beautiful Transitions with Material Motion for Flutter, is also available.

Material motion defines the following transition patterns:

1. Container transform

2. Shared axis

3. Fade through

4. Fade

### Container transform

The container transform pattern is designed for transitions between UI elements that include a container. This pattern creates a visible connection between two UI elements.

Examples of the container transform:

1. A card into a details page

2. A list item into a details page

3. A FAB into a details page

4. A search bar into expanded search

### Shared axis

The shared axis pattern is used for transitions between UI elements that have a spatial or navigational relationship. This pattern uses a shared transformation on the x, y, or z axis to reinforce the relationship between elements.

Examples of the shared axis pattern:

1. An onboarding flow transitions along the x-axis

2. A stepper transitions along the y-axis

3. A parent-child navigation transitions along the z-axis

### Fade through

The fade through pattern is used for transitions between UI elements that do not have a strong relationship to each other.

Examples of the fade through pattern:

1. Tapping destinations in a bottom navigation bar

2. Tapping a refresh icon

3. Tapping an account switcher

### Fade

The fade pattern is used for UI elements that enter or exit within the bounds of the screen, such as a dialog that fades in the center of the screen.

Examples of the fade pattern:

1. A dialog

2. A menu

3. A snackbar

4. A FAB
