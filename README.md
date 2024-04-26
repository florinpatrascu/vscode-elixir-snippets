# Elixir code snippets for VS Code

Graciously borrowed all the snippets from the [TextMate bundle for Elixir](https://github.com/elixir-editors/elixir-tmbundle) and refactored them to work with VS Code.

## Snippets

| prefix             | description                                                                                              |
| ------------------ | -------------------------------------------------------------------------------------------------------- |
| case               | case                                                                                                     |
| cond               | cond                                                                                                     |
| def                | def                                                                                                      |
| df                 | def (one line)                                                                                           |
| defc               | defcallback                                                                                              |
| defd               | defdelegate                                                                                              |
| defe               | defexception                                                                                             |
| defi               | defimpl                                                                                                  |
| dmod               | defmodule                                                                                                |
| defmc              | defmacrocallback                                                                                         |
| defmp              | defmacrop                                                                                                |
| describe           | describe ".." do ..                                                                                      |
| dmac               | defmacro                                                                                                 |
| defp               | defp                                                                                                     |
| defpro             | defprotocol                                                                                              |
| defs               | defstruct                                                                                                |
| do                 | do                                                                                                       |
| doc                | doc                                                                                                      |
| ee                 | embed_eex                                                                                                |
| ok                 | {:ok, ..} ...                                                                                            |
| err                | {:error, ..} ...                                                                                         |
| oke                | {:ok, ..} = ...                                                                                          |
| erre               | {:error, ..} = ...                                                                                       |
| trc                | try do catch                                                                                             |
| exu, ex_unit       | ExUnit template                                                                                          |
| trr                | try do rescue (everything!)                                                                              |
| fn                 | fn                                                                                                       |
| for                | for                                                                                                      |
| fori               | for into                                                                                                 |
| if                 | if                                                                                                       |
| ife                | if else                                                                                                  |
| ife:               | if else (one line)                                                                                       |
| if:                | if (one line)                                                                                            |
| imp                | import                                                                                                   |
| i                  | inspect                                                                                                  |
| ii                 | IO.inspect                                                                                               |
| iib                | IO.inspect(binding(), module:line)                                                                       |
| iil                | IO.inspect(label: ..)                                                                                    |
| iill               | IO.inspect with label incl. the line number                                                              |
| iins               | `IO.inspect` with a label containing relative path and line number. Label string can easily be discarded |
| ist                | `IO.inspect` the current stacktrace                                                                      |
| iip                | pipe to IO.inspect(module:line)                                                                          |
| ip                 | IO.puts( ..)                                                                                             |
| p                  | the pipeline operator                                                                                    |
| pry                | IEx.pry                                                                                                  |
| %                  | map/struct                                                                                               |
| mdoc               | moduledoc                                                                                                |
| mfs                | map from struct                                                                                          |
| mp                 | Map.put/3 - puts the given value under key in map                                                        |
| mpn                | Map.put_new/3 - puts the given value under key unless the entry key already exists in map                |
| msan               | sanitize a Map by dropping some of its keys                                                              |
| pe                 | print_eex                                                                                                |
| rec                | receive                                                                                                  |
| req                | require                                                                                                  |
| test               | test ".." do ..                                                                                          |
| testc              | test "..", %{..} do ..                                                                                   |
| unless             | unless                                                                                                   |
| unlesse            | unless else                                                                                              |
| unlesse:           | unless else (one line)                                                                                   |
| unless:            | unless (one line)                                                                                        |
| supervisor         | OTP Supervisor module                                                                                    |
| gen_server         | OTP GenServer module                                                                                     |
| dynamic_supervisor | Elixir DynamicSupervisor module                                                                          |
| wt                 | with .. do ..                                                                                            |
| wte                | with .. do .. else ..                                                                                    |

## Quick setup

Install it from: [florinpatrascu.vscode-elixir-snippets](https://marketplace.visualstudio.com/items?itemName=florinpatrascu.vscode-elixir-snippets)

Or if you want to contribute with updates:

```sh

git clone https://github.com/florinpatrascu/vscode-elixir-snippets.git
```

And copy the `vscode-elixir-snippets` folder into the `<user home>/.vscode/extensions` folder. Restart Code.

**Enjoy!**

## License

[MIT](LICENSE) License

Copyright (c) 2017-2024 Florin T. PATRASCU
