Fixed version of vscode-textmate that compiles with vite;

Use commonjs instead of non-standard umd.

To use it in your repo add the following resolution

```json
{
    "resolutions": {
        "vscode-textmate": "git+https://git@github.com/xzdarcy/vscode-textmate-fix-output.git#4.4.0"
    }
}
```