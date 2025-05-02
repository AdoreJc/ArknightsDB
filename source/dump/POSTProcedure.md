# POSTProcedure

**Namespace:** ` `


## Fields

- `TResp <response>k__BackingField`


## Properties

- `TResp response`


## Methods

- `TResp get_response()`

- `Void set_response(TResp)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class POSTProcedure`1 : POSTProcedure
{
	private TResp <response>k__BackingField; // 0x0

	public TResp response { get; set; }

	// RVA: 0x VA: 0x0
	public TResp get_response() { }
	// RVA: 0x VA: 0x0
	private Void set_response(TResp value) { }
	// RVA: 0x VA: 0x0
	protected override Void HandleServiceResponse(POSTResult postRet) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```