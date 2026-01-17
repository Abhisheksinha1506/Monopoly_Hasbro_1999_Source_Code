# Monopoly (Hasbro 1999) - PC Source Code

## Overview
This repository contains the complete source code for the **1999 PC version of Monopoly** published by **Hasbro Interactive**. This was one of the most successful digital adaptations of the classic board game, featuring 3D graphics, animated tokens, and multiplayer support. The codebase represents a significant commercial game development effort from the late 1990s.

## Project Details
- **Developer**: Westwood Studios / Hasbro Interactive
- **Release Year**: 1999
- **Platform**: Windows 95/98/ME
- **Engine**: Custom 3D engine with middleware integration

## Technology Stack
- **Graphics**: Custom PC3D engine for 3D board rendering
- **Video**: Bink Video codec for cutscenes and animations
- **Compression**: ZLib for asset compression
- **Image Format**: JPEG library for texture management
- **Core Library**: Custom artlib for game logic and rendering

## Repository Structure

### Core Game Engine
- **monopoly/**: (1,251 files) Main game logic, AI, and board mechanics
- **artlib/**: (79 files) Core rendering and asset management library
- **PC3D/**: (107 files) 3D graphics engine for board visualization

### Middleware & Libraries
- **Bink/**: (6 files) RAD Game Tools' Bink Video codec integration
- **JPEG/**: (61 files) JPEG image decoding library
- **ZLib/**: (24 files) Data compression library

## Key Technical Features
- **3D Board Rendering**: Fully 3D Monopoly board with camera controls
- **Animated Tokens**: 3D character models with personality animations
- **AI Players**: Sophisticated computer opponents with different strategies
- **Multiplayer**: Network and hot-seat multiplayer support
- **Video Integration**: Bink video for Mr. Monopoly animations and cutscenes

## Historical Significance
This 1999 Monopoly adaptation was groundbreaking for bringing a traditional board game to PC with full 3D graphics and production values. It demonstrated how classic games could be successfully modernized for the digital era while maintaining their core gameplay. The source code reveals professional game development practices from Westwood Studios, the legendary creators of Command & Conquer.

## How to Explore
1. **monopoly/**: Examine the core game logic and AI implementation
2. **PC3D/**: Study the 3D rendering engine
3. **artlib/**: Review the asset management and rendering library
4. **Bink/**: Understand video codec integration
