# Hello, World

## Install Elm

- https://github.com/elm/compiler/releases
- Download binary `.gz` and place in `$PATH` as `elm`
- Use `elm init` to start a new Elm project

**Note:** `.elm` files can't include literal tabs. 

## Build

	elm make src/Main.elm
	# Produces 'index.html' as output

## Development

	elm reactor .
	# Opens listener on 'http://localhost:8000'
	# Clicking on a '.elm' file compiles the file and renders the output

## References

- https://guide.elm-lang.org/

