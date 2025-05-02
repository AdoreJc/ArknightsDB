# CriAtomCueSheet

**Namespace:** `CriWare`


## Fields

- `String name`

- `String acbFile`

- `String awbFile`

- `CriAtomExAcb acb`

- `Status loaderStatus`


## Properties

- `Boolean IsLoading`

- `Boolean IsError`


## Methods

- `Boolean get_IsLoading()`

- `Boolean get_IsError()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomCueSheet
{
	public String name; // 0x10
	public String acbFile; // 0x18
	public String awbFile; // 0x20
	public CriAtomExAcb acb; // 0x28
	public Status loaderStatus; // 0x30

	public Boolean IsLoading { get; }
	public Boolean IsError { get; }

	// RVA: 0x410dd70 VA: 0x7596725d70
	public Boolean get_IsLoading() { }
	// RVA: 0x4114f28 VA: 0x759672cf28
	public Boolean get_IsError() { }
	// RVA: 0x410f5ac VA: 0x75967275ac
	public Void .ctor() { }
}
```