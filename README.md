# boyhouten

Simple React image icon components.

## Installation

```bash
npm i boyhouten
```

## Usage (Vite / React)

`src/App.tsx`

```tsx
import { Boy1, Boy2, Boy3 } from "boyhouten";

export default function App() {
  return (
    <div style={{ padding: 24 }}>
      <Boy1 w={100} h={100} />
      <Boy2 w={100} h={100} />
      <Boy3 w={100} h={100} />
    </div>
  );
}
```

Run:

```bash
npm run dev
```

## Props

All icons render an `<img />` and accept normal `<img>` props plus:

- `w?: number` — width (default: 24)
- `h?: number` — height (default: 24)
- `alt?: string` — alt text

Example:

```tsx
<Boy1 w={64} h={64} alt="Boy1" />
```

## Exports

```ts
import { Boy1, Boy2, Boy3 } from "boyhouten";
```

## License

ISC
