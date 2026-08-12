# Contributing to 42006-Lego-Model

Thanks for your interest in this project! This started as an academic CAD modeling exercise for the *Graphic Design* course at UC3M, but corrections, improvements, and new formats are welcome from anyone.

## Ways to Contribute

- **Report a modeling error** — a piece that doesn't fit, a wrong dimension, a broken mechanical linkage.
- **Report a broken link or file** — dead download links, corrupted exports, missing files.
- **Add or fix an export format** — e.g. filling in an empty format folder (`3MF/`, `IGES/`, etc.) for an existing part or assembly.
- **Improve documentation** — clarify the README, fix typos, improve the technical drawings in `Drafts/`.
- **Improve renders** — better lighting, materials, or additional angles in `Renders/`.

## Reporting an Issue

Before opening an issue, please check [existing issues](https://github.com/Himalia13/42006-Lego-Model/issues) to avoid duplicates.

When reporting, please include:
- **Which file(s)** are affected (e.g. `Assembly/ARM/STEP/Arm3.step`)
- **What's wrong** — as specific as possible (e.g. "part doesn't align with Arm2 at the pivot point")
- **Software/version used** to open the file, if relevant (e.g. "Fusion 360 2025", "Solid Edge 2024")
- Screenshots, if the issue is visual

## Submitting Changes

1. **Fork** the repository.
2. **Create a branch** for your change:
   ```
   git checkout -b fix/arm-pivot-alignment
   ```
3. Make your changes, keeping the existing folder structure and naming conventions (see below).
4. **Commit** with a clear, descriptive message:
   ```
   git commit -m "Fix ARM pivot misalignment in Arm3.step"
   ```
5. **Push** your branch and open a **Pull Request** against `main`, describing what changed and why.

## File & Naming Conventions

To keep the repository consistent, please follow the existing patterns:

- **Parts** are named `<Color>_<PartNumber>_<Initials>.<ext>` (e.g. `Black_4107081_JCA.step`), matching the naming used in `Parts/` and `Renders/Parts_Images/`.
- **Assemblies** live under `Assembly/<NAME>/<FORMAT>/`, with a top-level file named after the assembly (e.g. `Assembly/ARM/STEP/ARM.step`) plus numbered sub-steps if applicable (`Arm1.step`, `Arm2.step`, ...).
- **Every format folder** under an assembly or `Parts/` should mirror the same file, just re-exported (e.g. if you add `Arm7.par`, also add the corresponding `Arm7.step`, `.stl`, etc. where feasible).
- **Drafts/technical drawings** go in `Drafts/`, matching the source part or assembly name, suffixed `_draft.pdf` or `_Page<N>.pdf`.
- Keep new renders in `Renders/Parts_Images/` (individual parts) or `Renders/Mountings/` (assembly animations), following the existing naming style.

If you're unsure where something belongs, open an issue first to discuss it before submitting a large PR.

## Packaging / Releases

If your change affects files included in a published `.zip` package (see [Downloads / Packages](README.md#downloads--packages)), please note this in your PR — packages are rebuilt manually using `prepare_release_zips.py` and published as a new GitHub Release, not automatically on every commit.

## Code of Conduct

Be respectful and constructive. This is a small educational project — please keep feedback focused on the work, not the person.

## License

By contributing, you agree that your contributions will be licensed under the same [CC BY-NC 4.0 License](LICENSE.md) that covers the rest of the repository.
