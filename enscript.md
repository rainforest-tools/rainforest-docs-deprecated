# enscript

> [Document](https://www.ibm.com/docs/en/aix/7.1?topic=e-enscript-command)

### Install

```bash
brew install enscript
```

### Python Script

```bash
enscript --line-numbers -p - --highlight=python --color=1 -c [PATH/TO/NAME].py | ps2pdf - [NAME].pdf
```

