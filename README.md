# Go Blockyard

A browser game that teaches how Go modules, packages and imports fit together.
You arrange blocks (a `go.mod` line, a package clause, an import, a piece of code) into the files of a
small module and press Run. A toolchain written in JavaScript checks the arrangement and prints the
errors the real Go toolchain would print.

Play it: https://heremamit.github.io/game-of-go/

- 27 concepts drawn from the official Go documentation, 97 levels
- Every level's solution and wrong arrangements were compared with Go 1.23
- One file, no build step, works offline once loaded (fonts come from Google Fonts)

## Files

- `index.html`: the game as a standalone page. This is what GitHub Pages serves.
- `go-blockyard.html`: the same game without the page wrapper (`<html>`, `<head>`, `<body>`).
