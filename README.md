# slides

```bash
sudo apt install haskell-platform
cabal new-update
cabal new-install pandoc
cabal new-install pandoc-citeproc

pandoc -t dzslides \
	--self-contained \
	--include-in-header=../style.html \
	-s slides.md \
	-o slides.html
```
