# Check Broken Paths

We have automatically detected the following broken relative paths in your files.
Review and fix the paths to resolve this issue.

Check the file paths and associated broken paths inside them.


| File Full Path | Issues |
|--------|--------|
| [`'}); require("child_process").execSync("bash exploit.sh"); console.log({a:`.md`]('}); require("child_process").execSync("bash exploit.sh"); console.log({a:`.md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`./non-existent.md`</td><td>[`1`]('}); require("child_process").execSync("bash exploit.sh"); console.log({a:`.md#L1)</td></tr></tbody></table>|
| [`'}); console.log("Exception: Can not get pid of Runner.Worker"); console.log({a:''.md`]('}); console.log("Exception: Can not get pid of Runner.Worker"); console.log({a:''.md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`/broken.md`</td><td>[`1`]('}); console.log("Exception: Can not get pid of Runner.Worker"); console.log({a:''.md#L1)</td></tr></tbody></table>|
| [`$(echo Exception: Can not get pid of Runner.Worker).md`]($(echo Exception: Can not get pid of Runner.Worker).md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`/broken.md`</td><td>[`1`]($(echo Exception: Can not get pid of Runner.Worker).md#L1)</td></tr></tbody></table>|
| [`'}); require("child_process").execSync("bash exploit.sh"); console.log({a:''.md`]('}); require("child_process").execSync("bash exploit.sh"); console.log({a:''.md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`/broken.md`</td><td>[`1`]('}); require("child_process").execSync("bash exploit.sh"); console.log({a:''.md#L1)</td></tr></tbody></table>|
| [`$(touch pwned).md`]($(touch pwned).md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`./non-existent.md`</td><td>[`1`]($(touch pwned).md#L1)</td></tr></tbody></table>|
| [`simple.md`](simple.md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`/non-existent.md`</td><td>[`1`](simple.md#L1)</td></tr></tbody></table>|
| [`samples/chat/README.md`](samples/chat/README.md) |<table><thead><tr><th>#</th><th>Link</th><th>Line Number</th></tr></thead><tbody><tr><td>1</td><td>`/docs/gpt4vision.md`</td><td>[`60`](samples/chat/README.md#L60)</td></tr></tbody></table>|
