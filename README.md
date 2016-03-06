# slides

```bash
sudo aptitude install haskell-platform
cabal update
cabal install pandoc
cabal install pandoc-citeproc

pandoc -t dzslides \
	--self-contained \
	--include-in-header=../style.html \
	-s slides.md \
	-o slides.html
```