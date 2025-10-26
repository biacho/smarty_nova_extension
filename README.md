# Smarty Templates for Nova

**Smarty Templates** provides comprehensive syntax highlighting for Smarty template files (.tpl) in Nova.

<img width="644" height="732" alt="image" src="https://github.com/user-attachments/assets/2cc8ebd8-7322-4f9b-b621-5af0f5e7ad7b" />


## Features

This extension provides full syntax highlighting support for:

### Smarty Template Syntax
- Control structures (`{if}`, `{else}`, `{elseif}`, `{foreach}`, `{for}`, `{while}`, `{switch}`, `{case}`)
- Variables and properties (`{$variable}`, `{$user.name}`, `{$item.id}`)
- Built-in functions (`{assign}`, `{block}`, `{capture}`, `{include}`, `{extends}`)
- Variable modifiers/filters (`|upper`, `|lower`, `|date_format`, `|escape`, etc.)
- Comments (`{* Smarty comment *}`)
- Literal blocks (`{literal}...{/literal}`)
- Double and single brace syntax (`{{variable}}` and `{variable}`)

### Embedded Language Support
- **HTML** - Full support for HTML tags, attributes, and entities
- **CSS** - Syntax highlighting for styles within `<style>` tags
- **JavaScript** - Syntax highlighting for scripts within `<script>` tags

## Installation

### From Extension Library
1. Open Nova
2. Go to **Extensions → Extension Library**
3. Search for "Smarty Templates"
4. Click **Install**

### Manual Installation
1. Download the latest release
2. Double-click the `.novaextension` file
3. Nova will install it automatically

## Usage

Files with the `.tpl` extension will automatically use Smarty syntax highlighting.

## Issues & Contributions

Found a bug or have a feature request? Please open an issue on [GitHub](https://github.com/biacho/smarty_nova_extension/issues).

## License

MIT License - see LICENSE file for details.
