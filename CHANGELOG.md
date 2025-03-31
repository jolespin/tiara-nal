# Change Log
- `1.0.4rc3` - Added support for Python 3.12
- `1.0.4rc2` - Adding dependency version flexibility and stdin support for sequences
- `1.0.3` – Added `pyproject.toml`, updated dependencies to `python<3.10`. Added option to use gzipped fasta file as input (automatically identified by `.gz` suffix).
- `1.0.2` – Added `Python 3.9` compatibility, added an option to gzip the results. 
- `1.0.0`, `1.0.1` – Initial releases.

# Pending:
* Replace Biopython with PyFastx (This will remove functionality for stdin)

# Bugs:
* Compatibility issues `torch 1.7.0` and `Python >= 3.9`?