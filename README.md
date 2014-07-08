# chomp

This gem simply provides a command-line tool for removing the trailing newline from stdin if it exists and outputting it back to stdout.

This gem exists because I wanted to write something shorter than `ruby -pe chomp` in the middle of my pipes.

## Installation

```ruby
$ gem install chomp
```

## Usage

```
$ echo hello | chomp
$ echo -n hello | chomp
```

## License

MIT

## Authors

- Ben Scott (<gamepoet@gmail.com>)
