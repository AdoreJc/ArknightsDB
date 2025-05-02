# TrapItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String trapId`

- `Int32 sortId`

- `String name`

- `String usage`

- `String description`

- `String orderId`

- `RoguelikeArchiveItemUnlockStatus status`

- `String subDescription`

- `String subIcon`


## Methods

- `Int32 CompareTo(TrapItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TrapItemModel : ArchiveItemModel
{
	public String trapId; // 0x30
	public Int32 sortId; // 0x38
	public String name; // 0x40
	public String usage; // 0x48
	public String description; // 0x50
	public String orderId; // 0x58
	public RoguelikeArchiveItemUnlockStatus status; // 0x60
	public String subDescription; // 0x68
	public String subIcon; // 0x70
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x308fb04 VA: 0x75956a7b04
	public override String GetFuncId() { }
	// RVA: 0x308fb6c VA: 0x75956a7b6c
	public override String GetDesc() { }
	// RVA: 0x308fbd4 VA: 0x75956a7bd4
	public Int32 CompareTo(TrapItemModel value) { }
	// RVA: 0x308fc60 VA: 0x75956a7c60
	public Void .ctor() { }
}
```