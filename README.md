# Swift Version Action

![CI](https://github.com/sersoft-gmbh/swift-version-action/workflows/Deploy/badge.svg)

This action reads the current Swift version.

_Note_: 
    This action does not install or change the current Swift version. It just reads it.
    To change the Swift version on macOS, use `xcode-select` to select the corresponding Xcode version (or use an action like [maxim-lobanov/setup-xcode](https://github.com/maxim-lobanov/setup-xcode)).
    To install Swift on Linux, you can use our [SwiftyActions](https://github.com/sersoft-gmbh/SwiftyActions) action.

## Inputs

_None_

## Outputs

### `version`

The version of Swift that's currently active (e.g. `5.4.2`).

## Example Usage

Use the following snippet to read the current swift version:
```yaml
uses: sersoft-gmbh/swift-version-action@v1
```
