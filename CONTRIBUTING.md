# Contributing

Thanks for helping improve this list of learning-based 3D vision papers. You are welcome to open PRs, file issues, or contact me directly.

## Ways to contribute
- Add new papers or surveys
- Fix links, typos, or metadata
- Propose new categories when necessary

## Add a paper
1. Choose one primary category in `README.md` using the classification rules below.
2. Insert the entry in **reverse chronological order** (newest first) within that category, using the first public release date rather than a later arXiv revision date.
3. Keep the formatting consistent with nearby items.

### Classification rules

- **Classify by the main contribution, not the architecture.** Feed-forward inference, test-time optimization, pixel alignment, Gaussian splatting, and transformer memory are cross-cutting properties. They do not define peer task categories. If useful, describe a verified property in a short note; do not infer it from a model name or an `E2E` label.
- **Separate learning objectives, data, and diagnostics from downstream systems.** Transferable representations, pre-training, and self-supervised adaptation belong in `Geometric Representation / Pre-training` (e.g., CroCo, Gekko, Velox, and SelfEvo). Primary dataset, data-construction, or benchmark contributions belong in `Datasets / Benchmarks` (e.g., Stereo4D and PDI-Bench). Probing and failure-analysis studies belong in `Analysis / Diagnostics`.
- **Distinguish reconstruction from view synthesis and generation by the intended output.** Geometry, camera, or renderable-scene recovery from observations belongs in `3D Reconstruction` or `4D Reconstruction`. Target-view image prediction without an explicit reconstructed-scene deliverable belongs in `Novel View Synthesis`. Creating or completing assets/scenes with generative priors, including single-image asset reconstruction, belongs in `3D / 4D Generation`; image/video-output generators and relevant backbones belong in `Image / Video Generation`.
- **Keep sequential reconstruction discoverable.** Use `Streaming Reconstruction` when incremental reconstruction is the main contribution, and `SLAM` for localization-and-mapping systems. Support for dynamic content or an optional loop-closure module does not by itself require moving a streaming model to another section.
- **Separate geometric recovery from perception and reasoning.** Joint geometry/camera estimation from videos belongs in `4D Reconstruction` (e.g., PAGE-4D and ViPE). Depth-focused methods, semantic understanding, and tracking belong in `3D / 4D Perception`. Language-centered spatial reasoning belongs in `3D Vision-Language / Spatial Intelligence`; world-state prediction and robot action modeling belong in `World Models / Action Models`, subject to that subsection's scope note.
- **Give each paper one primary home.** For overlap, use the problem, main contribution, and evaluations in the original paper to choose its home. Application-specific systems primarily designed and evaluated for a domain belong in `3D Vision Applications`. Use section-level cross-links for related directions rather than duplicating full paper entries. Explain ambiguous placements in the issue or PR.

### Format with shields.io badges

Basic format (arXiv only):
```md
- **ShortName**, "Full Paper Title". [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)
```

With GitHub code link:
```md
- **ShortName**, "Full Paper Title". [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX) [![GitHub](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/org/repo)
```

If a paper is a must-read, prefix the item with `[⭐️]`:
```md
- [⭐️] **ShortName**, "Full Paper Title". [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)
```

For an official technical blog, use a `Blog` badge and state the publisher and publication date explicitly. Apply the same classification and recommendation rules; do not invent an arXiv entry or present a blog as a peer-reviewed paper.

```md
- **ShortName**, "Full Blog Title". *Publisher Blog, YYYY-MM-DD.* [![Blog](https://img.shields.io/badge/Publisher-Blog-yellow)](https://example.org/blog/post)
```

## Add or update categories

- Prefer existing categories and their scope notes. Propose a new category only for a distinct, populated research task or contribution type, not a single architectural trait.
- Keep comparable levels consistent: use a shared task parent for 3D/4D variants such as generation and editing.
- Add a short scope note that explains the new category's boundary with neighboring sections.
- Update the table of contents whenever headers change. Preserve legacy anchors when renaming or merging a category so existing links still resolve.
- When moving papers, preserve their titles, links, and recommendation markers, and check that no entries were lost or duplicated.

## Propose changes via issues
If you do not want to open a PR, create an issue with:
- Paper title and short name
- Link (arXiv, DOI, or official page)
- Suggested category and date
- Brief note on why it fits

## PR checklist
- One topic per PR
- No duplicate entries
- Links open correctly
- Formatting matches existing sections

## License
By contributing, you agree that your contributions will be licensed under the repository's MIT License.
