Static Application Security Testing (Semgrep)

For the SAST portion of the project, I configured GitHub Actions to automatically run Semgrep using the returntocorp/semgrep-action@v1 workflow with the default p/ci ruleset.

Scan Details
Files scanned: 45
Rules applied: 145
Languages detected: Multilang, JavaScript, HTML, YAML
Skipped files: 1 file ignored (due to .semgrepignore, expected behavior)

Results
0 findings detected
0 blocking issues

Semgrep completed successfully with exit code 0

Conclusion
Semgrep found no vulnerabilities based on the selected ruleset. This indicates that the scanned files do not contain patterns commonly associated with security weaknesses. 
  
