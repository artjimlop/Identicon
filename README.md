# Identicon

**Generates a symmetrical squared avatar given an String. Just like GitHub does.**

## How to use it

To generate an image just use the main method. Identicon.main("any_string").

Example:

```
iex> Identicon.main("example")
```

Result:

![Result](example.png)

This project has been developed with the only purpose of learning Elixir. If you can find it useful, you are more than welcome to use it. But please, mention me or (better) buy me a drink.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
