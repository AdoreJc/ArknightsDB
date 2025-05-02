# SandboxPermBasicData

**Namespace:** `Torappu`


## Fields

- `String topicId`

- `SandboxPermTemplateType topicTemplate`

- `String topicName`

- `Int64 topicStartTime`

- `Int64 fullStoredTime`

- `Int32 sortId`

- `String priceItemId`

- `String templateShopId`

- `String webBusType`

- `String medalGroupId`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxPermBasicData : ITimeValidInfo
{
	public String topicId; // 0x10
	public SandboxPermTemplateType topicTemplate; // 0x18
	public String topicName; // 0x20
	public Int64 topicStartTime; // 0x28
	public Int64 fullStoredTime; // 0x30
	public Int32 sortId; // 0x38
	public String priceItemId; // 0x40
	public String templateShopId; // 0x48
	public List`1 homeEntryDisplayData; // 0x50
	public String webBusType; // 0x58
	public String medalGroupId; // 0x60


	// RVA: 0x34f4128 VA: 0x7595b0c128
	public Int64 GetStartTs() { }
	// RVA: 0x34f4130 VA: 0x7595b0c130
	public Int64 GetEndTs() { }
	// RVA: 0x34f4138 VA: 0x7595b0c138
	public Void .ctor() { }
}
```