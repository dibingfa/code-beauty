# code-beauty

.clang-format
https://clang.llvm.org/docs/ClangFormatStyleOptions.html#bracewrapping
```
BreakBeforeBraces: Custom
BraceWrapping:
  AfterEnum: false
  AfterStruct: false
  SplitEmptyFunction: false
  AfterControlStatement: Never
```

settings.json
```
"clang-format.executable": "${workspaceRoot}/.clang-format",
"C_Cpp.clang_format_style": "file:${workspaceRoot}/.clang-format"
```
