# mol-fe-react

React utility belt.

  - Collection of React goodies
  - Isomorphic - all components work in browser and Node
  - [See demos and docs](https://mailonline.github.io/mol-fe-react/)

## Installation

```shell
npm install mol-fe-react --save
```

## Usage

Import each utility individually to decrease your bundle size

```js
import {mock} from 'mol-fe-react/lib/mock';

const MyComponent = mock();
```

## Reference

  - Dummies
     - [`mock()`](./docs/mock.md)
     - [`loadable()`](./docs/loadable.md)
     - [`lazy()`](./docs/lazy.md)
     - [`delayed()`](./docs/delayed.md)
     - [`invert()`](./docs/invert.md)
  - Sensors
     - [`<SizeSensor>`](./docs/SizeSensor.md)
     - [`<WidthSensor>`](./docs/WidthSensor.md)
     - [`<ScrollSensor>`](./docs/ScrollSensor.md)
     - [`<MediaSensor>`](./docs/MediaSensor.md)
     - [`<WindowSizeSensor>`](./docs/WindowSizeSensor.md)
     - [`<WindowScrollSensor>`](./docs/WindowScrollSensor.md)
     - [`<NetworkSensor>`](./docs/NetworkSensor.md) and [`withNetwork()`](./docs/NetworkSensor.md#withnetwork)
     - [`<BatterySensor>`](./docs/BatterySensor.md)
     - [`<LightSensor>`](./docs/LightSensor.md)
     - [`<MediaDeviceSensor>`](./docs/MediaDeviceSensor.md)
  - Generators
     - [`<Speak>`](./docs/Speak.md)
     - [`<Vibrate>`](./docs/Vibrate.md)
     - [`<LocalStorage>`](./docs/LocalStorage.md)
     - [`<Audio>`](./docs/Audio.md)
  - Context
     - [`<Provider>`](./docs/context.md#provider), [`<Consumer>`](./docs/context.md#consumer), and [`withContext()`](./docs/context.md#withcontext)
     - [`<Theme>`](./docs/theme.md#theme), [`<Themed>`](./docs/theme.md#themed), and [`withTheme()`](./docs/theme.md#withtheme)
     - `<CssVars>`
  - CSS resets
     - [`<CssResetEricMeyer>`](./docs/reset/CssResetEricMeyer.md)
     - [`<CssResetEricMeyerCondensed>`](./docs/reset/CssResetEricMeyerCondensed.md)
     - [`<CssResetMinimalistic>`](./docs/reset/CssResetMinimalistic.md)
     - [`<CssResetMinimalistic2>`](./docs/reset/CssResetMinimalistic2.md)
     - [`<CssResetMinimalistic3>`](./docs/reset/CssResetMinimalistic3.md)
     - [`<CssResetPoorMan>`](./docs/reset/CssResetPoorMan.md)
     - [`<CssResetShaunInman>`](./docs/reset/CssResetShaunInman.md)
     - [`<CssResetSiolon>`](./docs/reset/CssResetSiolon.md)
     - [`<CssResetTantek>`](./docs/reset/CssResetTantek.md)
     - [`<CssResetUniversal>`](./docs/reset/CssResetUniversal.md)
     - [`<CssResetYahoo>`](./docs/reset/CssResetYahoo.md)
  - Other
     - [`<Resolve>`](./docs/Resolve.md)