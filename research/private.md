# Private

Analysis of the `private` property

## Analysis

- The `private` property is optional and defaults to `false`.<sup>[1]</sup>
  - If `true`, the package will not be published to the registry.
  - If `false`, the package will be published to the registry.
  - If not present, the package will be published to the registry.

## Platform Specific Behavior

### npm

- The `private` property is supported by npm.<sup>[1]</sup>

## Sources

1. [npm `private` field documentation][1]

[1]: <https://docs.npmjs.com/cli/configuring-npm/package-json#private>
