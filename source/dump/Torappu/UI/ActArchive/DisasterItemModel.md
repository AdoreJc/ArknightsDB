# DisasterItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String disasterId`

- `Int32 level`

- `String name`

- `String desc`

- `Int32 sortId`

- `String typeSmallIconId`

- `String typeBigActiveIconId`

- `String typeBigInactiveIconId`

- `String levelName`

- `String effect`

- `Boolean isAttained`


## Methods

- `Int32 CompareTo(DisasterItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DisasterItemModel : ArchiveItemModel, IComparable`1, IHotfixable
{
	public String disasterId; // 0x30
	public Int32 level; // 0x38
	public String name; // 0x40
	public String desc; // 0x48
	public Int32 sortId; // 0x50
	public String typeSmallIconId; // 0x58
	public String typeBigActiveIconId; // 0x60
	public String typeBigInactiveIconId; // 0x68
	public String levelName; // 0x70
	public String effect; // 0x78
	public Boolean isAttained; // 0x80
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3049d60 VA: 0x7595661d60
	public Int32 CompareTo(DisasterItemModel obj) { }
	// RVA: 0x3049e18 VA: 0x7595661e18
	public override String GetDesc() { }
	// RVA: 0x3049e80 VA: 0x7595661e80
	public override String GetFuncId() { }
	// RVA: 0x3049ee8 VA: 0x7595661ee8
	public Void .ctor() { }
}
```