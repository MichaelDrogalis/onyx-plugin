# onyx-plugin

A Leiningen template for creating Onyx 0.12.7 plugins.

## Usage

Specify the project name, which conventionally starts with `onyx-`, then specify a medium.

```
lein new onyx-plugin onyx-whatever --template-version 0.12.7.1 whatever
```

For example, to create a Kafka plugin:

```
lein new onyx-plugin onyx-kafka --template-version 0.12.7.1 kafka
```

## License

Copyright © 2015 Distributed Masonry LLC

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
