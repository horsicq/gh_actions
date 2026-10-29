# Supported Arguments

Use the following arguments to specify the CI workflow.

| Short | Long | Description |
| :---: | :--- | :--- |
| `-x` | `--xml` | Output results in XML format |
| `-j` | `--json` | Output results in JSON format |
| `-c` | `--csv` | Output results in CSV format |
| `-t` | `--tsv` | Output results in TSV format |
| `-p` | `--plaintext` | Output results as plain text |
| `-b` | `--verbose` | Show verbose output with detailed information |
| `-u` | `--heuristicscan` | Enable heuristic scanning methods |
| `-U` | `--hideunknown` | Hide unknown file types from results |
| `-e` | `--entropy` | Display file entropy information |


## Example Usage

```bash
# Output as JSON
scan_tool -j ./target_file.exe