# query_epo

[![License](https://img.shields.io/github/license/ownjoo/query_epo)](LICENSE)
[![Top language](https://img.shields.io/github/languages/top/ownjoo/query_epo)](https://github.com/ownjoo/query_epo) [![Stars](https://img.shields.io/github/stars/ownjoo/query_epo)](https://github.com/ownjoo/query_epo/stargazers) [![Forks](https://img.shields.io/github/forks/ownjoo/query_epo)](https://github.com/ownjoo/query_epo/forks) [![Issues](https://img.shields.io/github/issues/ownjoo/query_epo)](https://github.com/ownjoo/query_epo/issues) [![Pull requests](https://img.shields.io/github/issues-pr/ownjoo/query_epo)](https://github.com/ownjoo/query_epo/pulls)
Queries McAfee ePolicy Orchestrator (ePO) for endpoint/policy data via ePO's remote
command invocation interface, parsing the `OK:`/`Error #:` response envelope ePO's
command API wraps every result in.

# SECURITY NOTE:
I wrote the .py files.  You have my word that they don't do anything nefarious.  Even so, I recommend that you perform
your own static analysis and supply chain testing before use.  Many libraries are imported that are not in my own control.

# usage
```
$ python main.py --help
```
