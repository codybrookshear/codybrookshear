Generate PDF:

```
pandoc resume.md \
  -f markdown+hard_line_breaks \
  --pdf-engine=xelatex \
  -V mainfont="Helvetica Neue" \
  -V geometry=margin=1in \
  -o resume.pdf
```
