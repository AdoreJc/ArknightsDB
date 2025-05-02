# ArchiveEndbookItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String endbookId`

- `String textId`

- `String textTitle`

- `String unlockDesc`

- `Int32 sortOrder`


## Methods

- `Int32 CompareTo(ArchiveEndbookItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookItemModel : ArchiveItemModel, IComparable`1
{
	public String endbookId; // 0x30
	public String textId; // 0x38
	public String textTitle; // 0x40
	public String unlockDesc; // 0x48
	public Int32 sortOrder; // 0x50
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30514f0 VA: 0x75956694f0
	public override String GetFuncId() { }
	// RVA: 0x3051558 VA: 0x7595669558
	public override String GetDesc() { }
	// RVA: 0x30515dc VA: 0x75956695dc
	public Int32 CompareTo(ArchiveEndbookItemModel other) { }
	// RVA: 0x305167c VA: 0x759566967c
	public Void .ctor() { }
}
```