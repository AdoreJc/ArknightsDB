# SandboxV2BaseUpdateData

**Namespace:** `Torappu`


## Fields

- `String baseLevelId`

- `Int32 baseLevel`

- `String scoreFactor`

- `Int32 portableRepairCost`

- `Int32 entryCount`

- `Int32 repairCost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2BaseUpdateData
{
	public String baseLevelId; // 0x10
	public Int32 baseLevel; // 0x18
	public SandboxV2BaseUpdateCondition[] conditions; // 0x20
	public Dictionary`2 items; // 0x28
	public SandboxV2BaseFunctionPreviewData[] previewDatas; // 0x30
	public String scoreFactor; // 0x38
	public Int32 portableRepairCost; // 0x40
	public Int32 entryCount; // 0x44
	public Int32 repairCost; // 0x48


	// RVA: 0x34f2534 VA: 0x7595b0a534
	public Void .ctor() { }
}
```