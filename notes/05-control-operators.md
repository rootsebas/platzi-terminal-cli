# ⚙️ Control Operators in Linux

## Commands Used

- `;` (sequential execution)
- `&&` (AND conditional execution)
- `||` (OR conditional execution)

## Description

- `;` → executes commands sequentially, regardless of success or failure
- `&&` → executes the next command only if the previous one succeeds
- `||` → executes the next command only if the previous one fails

## Examples

- `echo first; ls -la; echo third` → runs all commands in order, even if one fails
- `ls -la && echo "listing successful"` → runs the second command only if `ls` succeeds
- `ls missing_file || touch error.log` → creates a file only if the first command fails
- `ls && echo success || echo failure` → handles both success and failure cases

## Key Learnings

- Control operators allow you to chain commands efficiently
- `;` is useful when execution order matters but not the result
- `&&` is ideal for dependent operations (success-based flow)
- `||` helps handle errors or fallback logic
- Combining operators gives you fine control over execution flow
- These operators are essential for scripting, automation, and error handling