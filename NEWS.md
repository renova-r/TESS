# TESS 2.1.2.9001

Renova release, based on CRAN TESS 2.1.2 (archived on CRAN 2025-12-04).

- `man/cettiidae.Rd`, `man/conifers.Rd`, `man/mammalia.Rd`: `\link{read.tree}`/`\link{ape}` -> `\link[ape]{read.tree}`/`\link[ape]{ape}` (documentation only).
- `man/tess.plot.output.Rd`, `man/tess.plot.multichain.diagnostics.Rd`, `man/tess.plot.singlechain.diagnostics.Rd`: two-argument `\item{}{}` entries inside `\itemize` rewritten as `\item label: text` (documentation only).
- `DESCRIPTION`: `Authors@R` added and `Author` lists Sebastian Hoehna [aut, cre] and Michael R. May [aut] (metadata only).
- `DESCRIPTION`: stale optional `Date` field removed (metadata only).
- No R or C++ code changed; `inst/CITATION` retains the same bibliographic fields.

Release preparation:

- `DESCRIPTION`: `Version` set to `2.1.2.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 3 text) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added for this release and is excluded from the R build; the existing `NEWS` file is unchanged.

### Metadata compatibility

Updated CITATION constructors while preserving the citation text and bibliographic fields.
