# Terminal Pacman 🟡

A terminal-based implementation of the classic Pacman arcade game using ASCII graphics and ANSI escape sequences.

## Overview

This project recreates the Pacman experience in the terminal, featuring authentic ghost AI behaviors, smooth rendering, and all the classic game mechanics. Built with Python, it demonstrates advanced terminal manipulation techniques and clean game architecture.

## Technical Scope

- **Rendering Engine**: Custom ANSI-based renderer with double-buffering
- **Game Logic**: Complete Pacman rules, scoring, and level progression  
- **Ghost AI**: Faithful recreation of Blinky, Pinky, Inky, and Clyde behaviors
- **Input System**: Non-blocking keyboard controls
- **Performance**: Optimized for smooth terminal gameplay

## Architecture

```
Game Engine ──► Renderer ──► Terminal
     │
State Manager
     │
Game Objects / AI System / Input Handler
```

The modular design separates game logic from rendering and I/O, making the codebase easy to understand and extend.

## Requirements

- Python 3.7+
- Terminal with ANSI escape sequence support
- 80x24 character window minimum

## Development Status

🚧 **Under Active Development**

- [x] Core rendering engine
- [x] Maze system
- [ ] Player controls and collision
- [ ] Ghost AI implementation
- [ ] Scoring and power-ups
- [ ] Sound effects and polish

## Contributing

Contributions welcome! Key areas include game mechanics, AI improvements, testing, and cross-platform support. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## References

- [The Pac-Man Dossier](https://www.gamasutra.com/view/feature/3938/the_pacman_dossier.php) - Original game mechanics
- [ANSI Escape Sequences](https://en.wikipedia.org/wiki/ANSI_escape_code) - Terminal control reference

## License

MIT License - See [LICENSE](LICENSE)

---

*Building the classic arcade experience, one character at a time.*
