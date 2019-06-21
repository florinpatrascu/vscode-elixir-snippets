# Change Log

## v0.2.30

- replace `defmod` with `dmod`, for inserting `defmodule ...`
- replace `defm` with `dmac`, for inserting `defmacro ...`
- new snippet: `mfs`, Map from Struct
- new snippet: `msan`, sanitize a Map, by dropping some of its keys

## v0.2.29

- New snippet: `iill`
  An `IO.inspect` with an optional custom message, displaying the file path relative to the app's root folder and the line number in the code where the inspect is defined. If your shell supports it, i.e. iTerm2, then you're just one-click away from jumping to the exact line in the code, where the inspect is. No more searching for forgotten inspects!

## v0.2.28

- Merge pull request #5 from ZachParsons/location-inspect. Thank you!

## v0.2.27

- add "p" for pipeline operator |> Thank you: @crunchysoul

## v0.2.26

- long time waiting for it .. `with` and `with/else` :)

## v0.2.25

- genserver, try/catch/rescue, snippets for {:ok/error, ... } and so much more. Please see the README, from more details. Enjoy!

## v0.0.17

- fixes #1, the `defmod` snippet is now able to transform the current file name to an Elixir module name i.e. my_module.exs to MyModule. Requires the latest VSCode ~> 1.18.0

## v0.0.16

- new snippets: `fori`, `iip`, `iil`
- short index of every snippet; see the README, fro more details
- corrections

## v0.0.15

improve a bit the `defmod` snippet until better support from VSCode?! See issue #1, for more details

- v0.0.11 change the extension's display name to: `Elixir snippets`
- v0.0.10 first public release

## [Unpublished]

- Initial release
