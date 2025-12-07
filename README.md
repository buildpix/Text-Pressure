# Text Pressure

A React component that distorts text based on mouse distance, creating a "pressure" effect on font weight and width.

## Installs

No external dependencies.

## Usage

```jsx
import TextPressure from './TextPressure';

const Example = () => {
  return (
    <div style={{ position: 'relative', height: '300px' }}>
      <TextPressure
        text="Compressa"
        flex={true}
        alpha={false}
        stroke={false}
        width={true}
        weight={true}
        italic={true}
        textColor="#ffffff"
        minFontSize={36}
      />
    </div>
  );
};

export default Example;
```

## Props

| Prop | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `text` | `string` | `'Compressa'` | The text to display. |
| `fontFamily` | `string` | `'Compressa VF'` | Font family name. |
| `fontUrl` | `string` | `...` | URL to the variable font file (WOFF2). |
| `width` | `boolean` | `true` | Enable width variation. |
| `weight` | `boolean` | `true` | Enable weight variation. |
| `italic` | `boolean` | `true` | Enable italic variation. |
| `alpha` | `boolean` | `false` | Enable opacity variation. |
| `flex` | `boolean` | `true` | Use flexbox for spacing. |
| `stroke` | `boolean` | `false` | Enable text stroke (outline). |
| `scale` | `boolean` | `false` | Enable vertical scaling. |
| `textColor` | `string` | `'#FFFFFF'` | Color of the text. |
| `strokeColor` | `string` | `'#FF0000'` | Color of the stroke if enabled. |
| `strokeWidth` | `number` | `2` | Width of the stroke. |
| `minFontSize` | `number` | `24` | Minimum font size. |
