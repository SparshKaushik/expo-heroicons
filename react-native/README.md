# heroicons-native

This package provides the Heroicons set adapted for React Native and Expo.

Install

```bash
npm install heroicons-native
# install the peer dependency
npm install react-native-svg
```

Quick usage

```jsx
import React from 'react'
import { View, Text } from 'react-native'
import { BeakerIcon } from 'heroicons-native/24/solid'

export default function Example() {
  return (
    <View>
      <BeakerIcon width={24} height={24} color="blue" />
      <Text>Example</Text>
    </View>
  )
}
```

Import paths

- `heroicons-native/24/outline`
- `heroicons-native/24/solid`
- `heroicons-native/20/solid`
- `heroicons-native/16/solid`

API notes

- Components are React forwardRef components and accept props from `react-native-svg` (e.g. `width`, `height`, `color`, etc.).
- TypeScript declaration files are included for proper typings.
- Title support has been removed; components do not accept `title` or `titleId` props.

Credits and links

This package is a React Native port of the official Heroicons set. For web-focused React and Vue packages, see the upstream repository:

- https://github.com/tailwindlabs/heroicons

License

MIT
