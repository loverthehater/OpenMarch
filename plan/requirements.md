# Requirements
## Main

- Be able to create and preview a full marching show within a single program/environment.

# Features
## Core

- Language: C++
    - Most optimizable and easiest to do cross-platform development
        - (see: Goals->Compatibility->Cross-platform)
- Have a rendering environment wrapped in a GUI (i.e. MuseScore)
    - Redering environment
        - Library: [SDL](http://wiki.libsdl.org/Introduction)?
            - TODO: Figure out which rendering API to use. SDL sounds promising but more research needs to be done.
    - Program GUI
        - Library: [Qt](https://www.qt.io/download-qt-installer)


## Ideas

# Goals
## Compatibility

- File formats
    - Use file formats that are compatible with major existing software (i.e. Musescore for music scores, whatever pyware is with pyware, etc.)
    - If that isn't feasible, have file converters
- Cross-platform
    - Open-source C++, releases to Windows, Mac OSX, Linux
    - Should work well on devices such as tablets as well as desktop/laptop computers.

## Extensibility

- M O D U L A R I T Y - Use architecture styles and models so that anything can easily be swapped out or taken away without everything falling apart.

## Development
### Documentation

- Keep naming verbose so anybody could guess what something is by looking at its name, but also provide verbose documentation on important class/method definitions/declarations.
- For the sake of clarity, update UML diagrams to reflect both the implemented and planned code-base.
    - TODO: See if there's a way to convert C++ projects into UML diagrams to ease this process.

### Paradigms

- For the time being, domain-driven development seems like the best option with appropriate usage of patterns to reflect things.
- [Multi-tier development](https://en.wikipedia.org/wiki/Multitier_architecture)?
    - TODO: define tiers and what goes in each?
- [Entity-component-system](https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system)
- File organization
    - TODO: figure out how to organize the files in a way that is easy to change if necessary.

### Testing

- TODO: figure out how tests will work, but they are *necessary*.