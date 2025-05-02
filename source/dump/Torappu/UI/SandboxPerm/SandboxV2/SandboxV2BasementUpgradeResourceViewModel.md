# SandboxV2BasementUpgradeResourceViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String itemId`

- `UIItemViewModel item`

- `Int32 itemNeed`

- `Int32 itemCount`


## Methods

- `Void LoadData(String, ItemType, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementUpgradeResourceViewModel : IHotfixable
{
	public String itemId; // 0x10
	public UIItemViewModel item; // 0x18
	public Int32 itemNeed; // 0x20
	public Int32 itemCount; // 0x24
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x250f344 VA: 0x7594b27344
	public Void LoadData(String id, ItemType type, Int32 need, Int32 count) { }
	// RVA: 0x250f450 VA: 0x7594b27450
	public Void .ctor() { }
}
```