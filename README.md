# Morphr Figma

A library for interacting with Figma APIs with typed responses and data structures.
This repo is a fork of this [this amazing library][old_library] from [Arne Molland][arne_molland].

## Usage

A simple usage example:

```dart
import 'package:morphr_figma/morphr_figma.dart';

main() {
  final file = FigmaClient('token').getFile('key');
}
```

More intricate and detail usage can be found in the [examples](https://github.com/intales/morphr_figma/blob/main/example).

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/intales/morphr_figma/issues
[old_library]: https://github.com/arnemolland/figma
[arne_molland]: https://github.com/arnemolland
