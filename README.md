# YARA Python Parser
This provides a thoroughly-tested `pip` package for parsing, modifying, and generating YARA rules.
Both Python 2.7 and 3+ are supported.

## Example Use Cases
* Easily aggregate and analyze YARA data from large rulesets.
* Transform YARA rules into JSON for easier downstream processing.
* Automatically catalog, organize, and lint YARA rules.
* Compute a hash over rule logic to know when a rule's content changes.
* Write YARA rule files from your Python code.

## Roadmap
The plan is to publish a production-ready `pip` package by the end of Q3 2017.

## See Also
* The [YARA](http://virustotal.github.io/yara/) tool itself
* [yara-python](http://yara.readthedocs.io/en/latest/yarapython.html) provides a simple Python
wrapper around the `yara` tool. `yara-python` allows you to compile YARA rules and match them
against files, but it does not provide access to the underlying rule logic.
* [ply](http://www.dabeaz.com/ply/ply.html), the underlying Python tokenization/parsing library.
* [plyara](https://github.com/8u1a/plyara) is a simple Python YARA parser which transforms YARA
files into Python dictionaries. This project is in many ways the next generation of `plyara`.
* [YaGo](https://github.com/Yara-Rules/yago) is a Go library which transforms YARA rules into JSON,
but does not expose an intermediate representation which can be modified.
