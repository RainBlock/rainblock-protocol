# Rainblock Protobuf Specification

This package includes protobufs for the RainBlock project.

To run tests, run
```
$ npm install
```
To install `prototool` and git hooks if you are running from a git repository.


```
$ npm test
```

Will run the linter with the correct configuration and check that the protobuf can be generated.
 
If there are linting errors, you can try running:

```
$ npm run format
```

Which will attempt to format the file so it passes the linter.


# Typescript Usage

This repository automatically generates a npm package with typings you can import into your project.

After running
```
$ npm install @rainblock/protocol
```
on your project, you can import the protocol definitions, which are usable by libraries such as gRPC,
like in the example below:

```
import { rainblock } from '@rainblock/protocol';

```