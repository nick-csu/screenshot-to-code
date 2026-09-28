# About this demo

This is an unofficial documentation preview prepared by Cortex. The upstream maintainers did not endorse this preview.

## Source and attribution

- Original project: [Screenshot to Code](https://github.com/abi/screenshot-to-code)
- Source snapshot: [d026163f586d](https://github.com/abi/screenshot-to-code/tree/d026163f586dfa8c5c10d28c36edd59a9d3b0e88)
- Demo fork: [nick-csu/screenshot-to-code](https://github.com/nick-csu/screenshot-to-code)

The selected Markdown guides remain in the fork. Cortex uses them to build the site and provide local MCP documentation tools.

The preview follows the demo fork. It does not automatically track new commits in the upstream repository.
The troubleshooting guide includes older provider instructions. This demo reproduces the upstream guide; it does not validate those instructions. Internal design notes are excluded.

## Reproduce the demo

Use Node.js 20 or later. Sign in with GitHub CLI using an account with write access to the demo fork.

```bash
npx -y @cortex-docs/cli deploy https://github.com/nick-csu/screenshot-to-code
```

To read the same documentation from an MCP client, use:

```bash
npx -y @cortex-docs/cli mcp-serve https://github.com/nick-csu/screenshot-to-code
```

The MCP server runs locally and exposes documentation. It does not run the project or connect to its application services.

If the maintainers adopt the integration, the configuration and MCP setup can point to the upstream repository. Cortex offers free documentation hosting for public open-source projects.

## License

The original project license follows. Existing copyright notices and attribution remain in the source files.

```text
MIT License

Copyright (c) 2023 Abi Raja

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
