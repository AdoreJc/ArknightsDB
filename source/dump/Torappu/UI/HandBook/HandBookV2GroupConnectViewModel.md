# HandBookV2GroupConnectViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Connection connection`

- `HandBookV2GroupCharViewModel targetChar`

- `String forceId`


## Properties

- `String targetForceId`


## Methods

- `String get_targetForceId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2GroupConnectViewModel
{
	public Connection connection; // 0x10
	public HandBookV2GroupCharViewModel targetChar; // 0x18
	public String forceId; // 0x20

	public String targetForceId { get; }

	// RVA: 0x2ede1f8 VA: 0x75954f61f8
	public String get_targetForceId() { }
	// RVA: 0x2eddfac VA: 0x75954f5fac
	public Void .ctor() { }
}
```