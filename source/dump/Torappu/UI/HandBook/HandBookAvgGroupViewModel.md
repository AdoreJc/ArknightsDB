# HandBookAvgGroupViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandbookAvgGroupData data`

- `Boolean isAvail`


## Properties

- `Boolean isGet`


## Methods

- `Boolean get_isGet()`

- `Void InitData(HandbookAvgGroupData)`

- `HandbookAvgData FindAvgData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookAvgGroupViewModel : IHotfixable
{
	public HandbookAvgGroupData data; // 0x10
	public Boolean isAvail; // 0x18
	public List`1 unlockList; // 0x20
	private static DelegateBridge __Hotfix0_get_isGet; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_FindAvgData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isGet { get; }

	// RVA: 0x2ebec24 VA: 0x75954d6c24
	public Boolean get_isGet() { }
	// RVA: 0x2ebc518 VA: 0x75954d4518
	public Void InitData(HandbookAvgGroupData groupData) { }
	// RVA: 0x2ebce20 VA: 0x75954d4e20
	public HandbookAvgData FindAvgData(String storyId) { }
	// RVA: 0x2ebc4a8 VA: 0x75954d44a8
	public Void .ctor() { }
}
```