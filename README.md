# TND Console Hugo Module

This modules handles everything about handling styled and precise messages in the build console. It handles warnings and errors

## Requirements

Requirements:
- Go 1.14
- Hugo 0.61.0


## Installation

If not already, [init](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module) your project as Hugo Module:

```
$: hugo mod init {repo_url}
```

Configure your project's module to import this module:

```yaml
# config.yaml
module:
  imports:
  - path: github.com/theNewDynamic/hugo-module-tnd-console
```

## Usage

WIP

### Console

#### Examples

### Settings

Settings are added to the project's parameter under the `tnd_console` map as shown below.

```yaml
# config.yaml
params:
  tnd_console:
    warnings: mute
    errors: mute
```
If `warnings`is set to `mute`, the warnings issued by the module won't be printed.
If `errors`is set to `mute`, the warnings issued by the module won't be printed.


## theNewDynamic

This project is maintained and love by [thenewDynamic](https://www.thenewdynamic.com).