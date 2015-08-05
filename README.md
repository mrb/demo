# requireSafe (+) demo 
Contains various vulnerable dependencies useful for demonstration purposes.

## Command Line Interface Demo

```
git clone git@github.com:requiresafe/demo.git
npm i -g requiresafe
cd demo
requiresafe check
```

### Sample Output
This output may differ slightly as things are patched or the format changes.

```
Name    Installed  Patched  Location       Advisory Details
marked      0.3.3        x  demo > marked  https://requiresafe.com/advisories/marked_redos
```

