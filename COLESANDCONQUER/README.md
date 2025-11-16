# Coles and Conquer

This is a custom game based on Command & Conquer: Tiberian Dawn. It was created as a copy of the TiberianDawn game logic DLL for gradual modification into a custom game experience.

## Project Structure

This project is a complete copy of the Tiberian Dawn source code, configured to build as a separate game DLL called `ColesAndConquer.dll`.

## Build Instructions

### Requirements
- Visual Studio 2017 (v141 toolset)
- Windows 8.1 SDK
- Win32 platform target

### Building
1. Open `CnCRemastered.sln` in Visual Studio
2. Select the `ColesAndConquer` project
3. Build for Release|Win32 configuration
4. The output DLL will be in `../bin/Win32/ColesAndConquer.dll`

## Current Status

This is currently an exact copy of Tiberian Dawn. Future modifications will gradually transform it into a unique game.

## Key Configuration Details

- **Project GUID**: `{095CAEAE-99E3-49D2-AE0B-CB2DD4095564}`
- **Output DLL**: `ColesAndConquer.dll` (Release), `ColesAndConquerI.dll` (Debug)
- **Preprocessor Define**: `COLESANDCONQUER_EXPORTS`

## Next Steps

1. Test build the project to ensure it compiles successfully
2. Begin making custom modifications to differentiate from Tiberian Dawn
3. Update game data, units, buildings, etc.
4. Modify graphics, sounds, and other assets
5. Implement new gameplay features

## License

This code is licensed under GPL v3 with additional restrictions, inherited from the original C&C Remastered Collection source code.
