# Enflame eflib user guide

eflib use Enflame Management Library (EFML) to manage enflame gcu information.


## go.mod

Add `github.com/zxldev/eflib v1.0.0` in `go.mod`, for example:

```
module modulename

go 1.18

require (
	github.com/zxldev/eflib v1.0.0
)

```

## vendor/modules.txt

Add `github.com/zxldev/eflib` in `vendor/modules.txt`, for example:

```
# github.com/zxldev/eflib v1.0.0
## explicit
github.com/zxldev/eflib
github.com/zxldev/eflib/efml

```


## import

import in go file, for example:

```
import (
	"github.com/zxldev/eflib"
	"github.com/zxldev/eflib/efml"
)
```
