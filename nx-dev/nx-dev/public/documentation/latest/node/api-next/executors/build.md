# @nrwl/next:build

Build a Next.js app

Options can be configured in `workspace.json` when defining the executor, or when invoking it.
Read more about how to use executors and the CLI here: https://nx.dev/getting-started/nx-cli#common-commands.

## Options

### buildLibsFromSource

Default: `true`

Type: `boolean`

Read buildable libraries from source instead of building them separately.

### fileReplacements

Type: `object[]`

Replace files with other files in the build.

#### replace

Type: `string`

The file to be replaced.

#### with

Type: `string`

The file to replace with.

### nextConfig

Type: `string`

Path (relative to workspace root) to a function which takes phase, config, and builder options, and returns the resulting config. This is an advanced option and should not be used with a normal Next.js config file (i.e. next.config.js).

### outputPath

Type: `string`

The output path of the generated files.

### root

Type: `string`

The source root
