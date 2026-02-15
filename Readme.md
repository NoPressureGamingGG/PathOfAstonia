# Path of Astonia

This is a monorepo combining the Path of Astonia client and server codebases from the Astonia Community.

## Repository Structure

This repository is organized into two main directories:

### PathServer/
Contains the complete game server code for Astonia 3.5 Server, Community Edition. This is the server-side component that handles game logic, player management, database interactions, and world simulation.

**Source:** [AstoniaCommunity/astonia_community_server35](https://github.com/AstoniaCommunity/astonia_community_server35)

Key features:
- Server-side game logic and world management
- MySQL/MariaDB database integration
- Player account and character management
- Built for Linux (tested on Ubuntu)

See [PathServer/readme.md](PathServer/readme.md) for detailed server setup and building instructions.

### PathClient/
Contains the complete game client code for Astonia Community Client. This is the client-side application that players use to connect to the server and play the game.

**Source:** [AstoniaCommunity/astonia_community_client](https://github.com/AstoniaCommunity/astonia_community_client)

Key features:
- Cross-platform client (Windows, Linux, macOS)
- Modern rendering with SDL3
- Compatible with the original game server
- Community-driven development

See [PathClient/readme.md](PathClient/readme.md) for detailed client setup and building instructions.

## About the Project

Path of Astonia is based on the Astonia 3 MMORPG, a classic isometric online role-playing game. This monorepo structure allows developers to work on both the client and server code in a single unified repository while maintaining the complete, original structure of both projects.

## Getting Started

1. **For Server Development:** Navigate to `PathServer/` and follow the instructions in the README to set up and build the server
2. **For Client Development:** Navigate to `PathClient/` and follow the instructions in the README to set up and build the client
3. **For Full Stack Development:** You can work on both components simultaneously using this monorepo structure

## Original Repositories

This monorepo contains the complete code from the following AstoniaCommunity repositories:
- Server: https://github.com/AstoniaCommunity/astonia_community_server35
- Client: https://github.com/AstoniaCommunity/astonia_community_client

## License

Both components maintain their original licenses. Please refer to the license files in each respective directory for more information.
