# Cellularium

A physics-based cellular automaton (falling sand game) built with JavaScript and Canvas.

![Cellularium](https://img.shields.io/badge/elements-13-blue)

## Elements

| Element | Description |
|---------|-------------|
| **Sand** | Falls and piles up |
| **Water** | Flows and evaporates at high temps |
| **Fire** | Rises, burns fuel, and spreads heat |
| **Lava** | Extremely hot, turns water to stone |
| **Smoke** | Rises when hot, falls when cold, turns to dirt |
| **Steam** | Rises through air and water |
| **Ice** | Melts at high temperatures |
| **Snow** | Falls and melts near heat |
| **Dirt** | Static, piles up |
| **Stone** | Static, created when lava meets water |
| **Plant** | Grows when near water, burns |
| **Seed** | Falls and grows into plants near water |

## Temperature System

- All elements have a temperature that propagates to neighbors
- Fire and lava transfer heat to nearby cells
- Ice absorbs heat (reverse lava behavior)
- Cold smoke falls and turns to dirt
- Water evaporates at high temperatures

## Development

To run locally:

```bash
# Open index.html in a browser
# Or serve it:
npx serve .
```

## License

MIT
