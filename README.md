# Servcat
```shell
 |\_/|
 `o.o'
 c(_) Servcat is a simple HTTP server with a flavor of cats
```

by James Chuang
## Description
Servcat is a minimal HTTP server designed following the [Luke Francl's Tutorial][1] with a twist
## Usage
To run the server navigate to the servcat folder through the terminal and enter the following:
```shell
$ ruby servcat.rb
```

You can use the servcat to run a minimal server. It will prompt you when the server is started along with a little ACSII style cat.
```shell
 |\_/|
 `o.o'
 c(_) Meow Port 3003 Now Open
```

It will also prompt you for every HTTP request in the terminal like this:
```shell
 |\_/|
 `o.o'
 c(_) Kitty trying to GET / HTTP/1.1
```

## Known Issues

There are currently no known issues.

## Authors

* [James Chuang](https://github.com/hiddensanctum)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

[MIT][2]

[1]: https://practicingruby.com/articles/implementing-an-http-file-server?u=2c59db4496
[2]: http://opensource.org/licenses/MIT