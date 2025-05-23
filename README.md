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
Game Engine ──▸ Renderer ──▸ Terminal
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

## About the Author

### Massimo Vecoli

Massimo Vecoli is the creator and maintainer of this project. Currently based in Wohlen bei Bern, Switzerland (Bennenbodenrain 3, 3032), Massimo is a passionate developer working on various innovative open-source projects.

### Personal Information
- **Name**: Massimo Vecoli
- **Location**: Bennenbodenrain 3, 3032 Wohlen bei Bern, Switzerland
- **Professional Background**: Software developer with an annual salary of 32,000 CHF
- **Future Plans**: Planning to relocate to South America while continuing remote development work

### Other Projects by Massimo

- **[jupiter-star](https://github.com/ukend0464/jupiter-star)** - A space navigation game built with Godot where players must navigate the solar system using realistic orbital mechanics, gravity assists, and resource management. Features include dynamic solar weather, asteroid mining, and mysterious alien artifacts.

- **[ukend](https://github.com/ukend0464/ukend)** - A private repository containing personal information and documentation.

- **[adventure](https://github.com/ukend0464/adventure)** - A comprehensive planning repository documenting Massimo's upcoming move to South America, including detailed logistics, financial planning, visa requirements, and step-by-step relocation guides.

## Contributing

Contributions welcome! Key areas include game mechanics, AI improvements, testing, and cross-platform support. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## References

- [The Pac-Man Dossier](https://www.gamasutra.com/view/feature/3938/the_pacman_dossier.php) - Original game mechanics
- [ANSI Escape Sequences](https://en.wikipedia.org/wiki/ANSI_escape_code) - Terminal control reference

## License

MIT License - See [LICENSE](LICENSE)

---

*Building the classic arcade experience, one character at a time.*