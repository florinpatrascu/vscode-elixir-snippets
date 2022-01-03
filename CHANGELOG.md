# Change Log

## v0.2.40

- Add a snippet for inspecting stacktraces #21. Thank you @s3cur3

## v0.2.39

- Fix trailing comma #20. Thank you @easink

## v0.2.38

- new regex formula for using the RELATIVE_FILEPATH instead of the TM_FILEPATH variable. This matches any level of nested folders (see William's question in [StackOverflow](https://stackoverflow.com/questions/69145815/vs-code-snippet-regex-for-relative-path)). Removed the "Test" at the end of the "ExUnit" snippet because as a (opinionated) convention the file name includes "\_test" at the end of the file and included the prefix ":", useful when the key and value are the same. Thank you @williamthome

## v0.2.37

- `pry` snippet, thank you @PJUllrich

## v0.2.36

- readme format fix

## v0.2.35

- New snippet: `iins`; `IO.inspect` with a label containing relative path and line number. Label string can easily be discarded
  inspired bby this [tip](https://elixirstream.dev/tips/7bca7ae3-1431-4bb1-bf2c-1ee3c5390a40) I added my own take on it. Hopefully you can enjoy this newer version as much as I do :)
- dmod: Make more robust when used outside default folders #13
- ^^^ Thank you @sascha-wolf <3

## v0.2.34

- Reduced complexity of the syntax
- Generate module name from file path
- ^^^ PR from @marocchino Thank you <3

## v0.2.33

- bugfix: Fix comma in array for ExUnit snippet #9. Thank you @ewired

## v0.2.32

- test and describe snippets

## v0.2.31

- fix version numbering
- merge the ex_unit template from @neofelisho, thank you!
- README

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
