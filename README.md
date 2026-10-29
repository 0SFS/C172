# Cessna 172

The Cessna 172 Skyhawk: its flight model, visual model, and the files the simulator serves for that aircraft. It uses the IO-320 engine package.

The fly app depends on this package and runs its tests. From the `fly` directory, `npm test` includes them.

## Community

- [Code of conduct](https://github.com/0SFS/.github/blob/main/CODE_OF_CONDUCT.md)
- [Contributing](https://github.com/0SFS/.github/blob/main/CONTRIBUTING.md)
- [License](LICENSE)
- [Security](https://github.com/0SFS/.github/blob/main/SECURITY.md)
## Mod

This repository is a 0SFS mod. `public/0sfs-mod.json` is the manifest. GitHub Pages serves the `public/` directory at the site root.

Fork the repository, edit the manifest and the files it names, push, then add the GitHub URL in the simulator's Mods tab.

Topics: `0sfs-mod` and `0sfs-aircraft`.

## Community

- [Code of conduct](https://github.com/0SFS/.github/blob/main/CODE_OF_CONDUCT.md)
- [Contributing](https://github.com/0SFS/.github/blob/main/CONTRIBUTING.md)
- [License](LICENSE)
- [Security](https://github.com/0SFS/.github/blob/main/SECURITY.md)

The C172 declares `camera.follow: "aircraft"` and depends on `0SFS/rotating-prop`. Its propeller rig uses the shared frame-rate-aware rotation and alias limit: above it, the blades hide behind the authored semi-transparent 3D swept volume (`Propeller_Disc`). **Aircraft → Flat propeller discs** (Off by default) swaps in a cheaper flat disc.
