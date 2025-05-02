# FragmentItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String fragmentId`

- `RoguelikeFragmentType type`

- `Int32 weight`

- `Int32 value`

- `String name`

- `String iconId`

- `String desc`

- `String usage`

- `Int32 sortId`

- `RoguelikeArchiveItemUnlockStatus status`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class FragmentItemModel : ArchiveItemModel, IComparable
{
	public String fragmentId; // 0x30
	public RoguelikeFragmentType type; // 0x38
	public Int32 weight; // 0x3c
	public Int32 value; // 0x40
	public String name; // 0x48
	public String iconId; // 0x50
	public String desc; // 0x58
	public String usage; // 0x60
	public Int32 sortId; // 0x68
	public RoguelikeArchiveItemUnlockStatus status; // 0x6c
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge __Hotfix0__TypeComparison; // 0x18
	private static DelegateBridge __Hotfix0__GetFragmentTypeValue; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30554ec VA: 0x759566d4ec
	public override String GetFuncId() { }
	// RVA: 0x3055554 VA: 0x759566d554
	public override String GetDesc() { }
	// RVA: 0x30555bc VA: 0x759566d5bc
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x30556d8 VA: 0x759566d6d8
	private static Int32 _TypeComparison(RoguelikeFragmentType x, RoguelikeFragmentType y) { }
	// RVA: 0x3055770 VA: 0x759566d770
	private static Int32 _GetFragmentTypeValue(RoguelikeFragmentType type) { }
	// RVA: 0x30557f4 VA: 0x759566d7f4
	public Void .ctor() { }
}
```