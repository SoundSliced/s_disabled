## [3.0.0]
- `s_packages` dependency upgraded to ^3.0.0

 
## 2.1.0
- `s_packages` dependency upgraded to ^1.3.0
- Added `applyGrayscale` flag to apply a grayscale filter when disabled
- Added `disabledSemanticLabel` for custom accessibility label when disabled
- Added `disabledChild` to show an alternative widget when disabled

## 2.0.0
- package no longer holds the source code for it, but exports/exposes the `s_packages` package instead, which will hold this package's latest source code.
- The only future changes to this package will be made via `s_packages` package dependency upgrades, in order to bring the new fixes or changes to this package
- dependent on `s_packages`: ^1.1.2


## 1.0.0

* **Initial Release**: Stable release of s_disabled package
* **SDisabled Widget**: A customizable Flutter widget for disabling child widgets with smooth animations
* **Features**:
  - Animated opacity changes when disabled (customizable, can be disabled)
  - Configurable opacity level when disabled (default 0.3)
  - Tap detection on disabled widgets with optional callback
  - Smooth transitions using AnimatedOpacity (300ms duration)
  - AbsorbPointer to prevent interaction with disabled children
  - Full state management support
* **Parameters**:
  - `child`: The widget to be disabled/enabled
  - `isDisabled`: Boolean flag to control disabled state
  - `disableOpacityChange`: Prevent visual opacity indication when disabled
  - `opacityWhenDisabled`: Custom opacity value for disabled state
  - `onTappedWhenDisabled`: Callback function for tap events on disabled widget
* **Documentation**: Complete README with basic and advanced examples
* **Testing**: Comprehensive widget tests covering all functionality
* **Example App**: Full Flutter example demonstrating usage patterns
