## FIXED:

1. Use a unique `--user-data-dir` path for each screenshot to prevent profile conflicts in [url_screenshotter.go](https://github.com/ayusheek/aquatone/blob/master/agents/url_screenshotter.go)
2. Accessing `xurls.Relaxed` directly in [regex.go](https://github.com/ayusheek/aquatone/blob/master/parsers/regex.go)
