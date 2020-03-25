Parse HL7 MDM messages

Install lib from mylanconnolly :
https://github.com/mylanconnolly/hl7

Then
```
export GOPATH=~/src/go
go run mdm-parser.go -file ~/src/go/HL7_MDM_T11_02.hl7 |less

```

