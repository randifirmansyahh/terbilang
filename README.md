## Install

```
go get -u github.com/randifirmansyahh/terbilang
```

## Usage

```
import (
    terbilang "github.com/randifirmansyahh/terbilang"
)

wordResultFromString := terbilang.FromString{"1999"}.ToWord()
// Result
// Seribu sembilan ratus sembilan puluh sembilan

wordResultFromInt := terbilang.FromInt{1525000}.ToWord()
// Result
// Satu juta lima ratus dua puluh lima ribu

wordResultFromInt := terbilang.FromFloat{153.192311}.ToWord()
// Result
// Seratus lima puluh tiga koma satu sembilan dua tiga satu satu


```
