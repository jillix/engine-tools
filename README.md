# Engine Tools
Engine Tools library and CLI app.

## Installation

```sh
$ npm install -g engine-tools
```

## CLI Usage
```sh
$ engine-tools generateModuleService <optional-path-to-package.json>
```

## Documentation
### `generateModuleService(path, callback)`
Generates content for .service.json file.

#### Params
- **String** `path`: The path to the package.json file.
- **Function** `callback`: A function called with error and .serivce.json file content.

#### Return
- **Promise** A promise used to run the function steps.

## How to contribute
1. File an issue in the repository, using the bug tracker, describing the
   contribution you'd like to make. This will help us to get you started on the
   right foot.
2. Fork the project in your account and create a new branch:
   `your-great-feature`.
3. Commit your changes in that branch.
4. Open a pull request, and reference the initial issue in the pull request
   message.

## License
See the [LICENSE](./LICENSE) file.
