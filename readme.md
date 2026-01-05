

```python
#!/usr/bin/env python3

__author__	= "Ankit Kachhap"
__copyright__   = f"Copyright (c) 2026 {__author__}"
__license__ 	= "All Rights Reserved"
__version__	= "0.1.1"

import subprocess
res = subprocess.run(["python3" , "-c" , "print('Code. Debug. Repeat.')"],
		capture_output=True, text=True
		)

print("standard output:", res.stdout)	# Output
if res.stderr != "" : print("standard error:", res.stderr)	# Error

```
