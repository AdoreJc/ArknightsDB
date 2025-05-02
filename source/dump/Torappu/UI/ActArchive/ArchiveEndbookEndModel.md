# ArchiveEndbookEndModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Boolean hasExtendingItem`

- `String title`

- `String endBgId`

- `String endCardImgId`

- `Boolean hasAvg`

- `Boolean unlocked`

- `String avgId`

- `Single collectPercent`

- `Int32 sortOrder`

- `Boolean hasNew`

- `String endCgId`

- `String textId`

- `Int32 selectedGroupIndex`


## Methods

- `Int32 CompareTo(ArchiveEndbookEndModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookEndModel : IHotfixable, IComparable`1
{
	public List`1 endbookItems; // 0x10
	public Boolean hasExtendingItem; // 0x18
	public String title; // 0x20
	public String endBgId; // 0x28
	public String endCardImgId; // 0x30
	public Boolean hasAvg; // 0x38
	public Boolean unlocked; // 0x39
	public String avgId; // 0x40
	public Single collectPercent; // 0x48
	public Int32 sortOrder; // 0x4c
	public Boolean hasNew; // 0x50
	public String endCgId; // 0x58
	public String textId; // 0x60
	public Int32 selectedGroupIndex; // 0x68
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3051830 VA: 0x7595669830
	public Int32 CompareTo(ArchiveEndbookEndModel other) { }
	// RVA: 0x30518d0 VA: 0x75956698d0
	public Void .ctor() { }
}
```