# CharacterShowEquipModel

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `UniEquipData m_equipData`

- `Int32 m_level`

- `Boolean m_isUnlock`


## Properties

- `Boolean isUnlock`

- `UniEquipData equipData`

- `String equipId`

- `Int32 sortId`

- `Int32 level`


## Methods

- `Boolean get_isUnlock()`

- `UniEquipData get_equipData()`

- `String get_equipId()`

- `Int32 get_sortId()`

- `Int32 get_level()`

- `Void LoadData(UniEquipData, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowEquipModel : IHotfixable
{
	private UniEquipData m_equipData; // 0x10
	private Int32 m_level; // 0x18
	private Boolean m_isUnlock; // 0x1c
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x0
	private static DelegateBridge __Hotfix0_get_equipData; // 0x8
	private static DelegateBridge __Hotfix0_get_equipId; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_level; // 0x20
	private static DelegateBridge __Hotfix0_CreateUniEquipList; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isUnlock { get; }
	public UniEquipData equipData { get; }
	public String equipId { get; }
	public Int32 sortId { get; }
	public Int32 level { get; }

	// RVA: 0x2ce2d10 VA: 0x75952fad10
	public Boolean get_isUnlock() { }
	// RVA: 0x2ce3b14 VA: 0x75952fbb14
	public UniEquipData get_equipData() { }
	// RVA: 0x2ce2d78 VA: 0x75952fad78
	public String get_equipId() { }
	// RVA: 0x2ce4ff8 VA: 0x75952fcff8
	public Int32 get_sortId() { }
	// RVA: 0x2ce3b7c VA: 0x75952fbb7c
	public Int32 get_level() { }
	// RVA: 0x2ce3544 VA: 0x75952fb544
	public List`1 CreateUniEquipList() { }
	// RVA: 0x2ce3f20 VA: 0x75952fbf20
	public Void LoadData(UniEquipData equipData, Int32 level, Boolean isUnlock) { }
	// RVA: 0x2ce3eb0 VA: 0x75952fbeb0
	public Void .ctor() { }
}
```