# CharacterCardSortTypeViewModel

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_customTypeSet`

- `Int32 m_customSortType`

- `CharacterSortType m_sortType`

- `Boolean m_hasCustomSortType`

- `Boolean m_starMarkTop`

- `String m_customSortTypeCachedKey`


## Properties

- `CharacterSortType sortType`

- `Boolean customTypeSet`

- `Int32 customSortType`

- `Boolean isStarMarkTopMode`


## Methods

- `Void LoadCache(String, CharacterSortType, Boolean)`

- `CharacterSortType get_sortType()`

- `Void set_sortType(CharacterSortType)`

- `Boolean get_customTypeSet()`

- `Int32 get_customSortType()`

- `Boolean get_isStarMarkTopMode()`

- `Void TryUpdateCustomSortType(CharacterSortType)`

- `Void TryUpdateStarMarkTop(Boolean)`

- `Void _TryLoadCustomSortTypeCache()`

- `Void _TrySaveCustomSortTypeCache()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CharacterCardSortTypeViewModel : IHotfixable
{
	private Boolean m_customTypeSet; // 0x10
	private Int32 m_customSortType; // 0x14
	private CharacterSortType m_sortType; // 0x18
	private Boolean m_hasCustomSortType; // 0x1c
	private Boolean m_starMarkTop; // 0x1d
	private String m_customSortTypeCachedKey; // 0x20
	private static DelegateBridge __Hotfix0_LoadCache; // 0x0
	private static DelegateBridge __Hotfix0_get_sortType; // 0x8
	private static DelegateBridge __Hotfix0_set_sortType; // 0x10
	private static DelegateBridge __Hotfix0_get_customTypeSet; // 0x18
	private static DelegateBridge __Hotfix0_get_customSortType; // 0x20
	private static DelegateBridge __Hotfix0_get_isStarMarkTopMode; // 0x28
	private static DelegateBridge __Hotfix0_TryUpdateCustomSortType; // 0x30
	private static DelegateBridge __Hotfix0_TryUpdateStarMarkTop; // 0x38
	private static DelegateBridge __Hotfix0__TryLoadCustomSortTypeCache; // 0x40
	private static DelegateBridge __Hotfix0__TrySaveCustomSortTypeCache; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CharacterSortType sortType { get; set; }
	public Boolean customTypeSet { get; }
	public Int32 customSortType { get; }
	public Boolean isStarMarkTopMode { get; }

	// RVA: 0x212136c VA: 0x759473936c
	public Void LoadCache(String pageName, CharacterSortType defaultType, Boolean hasCustomSortType) { }
	// RVA: 0x212155c VA: 0x759473955c
	public CharacterSortType get_sortType() { }
	// RVA: 0x21215c4 VA: 0x75947395c4
	public Void set_sortType(CharacterSortType value) { }
	// RVA: 0x2121640 VA: 0x7594739640
	public Boolean get_customTypeSet() { }
	// RVA: 0x21216a8 VA: 0x75947396a8
	public Int32 get_customSortType() { }
	// RVA: 0x2121710 VA: 0x7594739710
	public Boolean get_isStarMarkTopMode() { }
	// RVA: 0x2121778 VA: 0x7594739778
	public Void TryUpdateCustomSortType(CharacterSortType sortType) { }
	// RVA: 0x21218f4 VA: 0x75947398f4
	public Void TryUpdateStarMarkTop(Boolean isStarMarkTop) { }
	// RVA: 0x212149c VA: 0x759473949c
	private Void _TryLoadCustomSortTypeCache() { }
	// RVA: 0x2121860 VA: 0x7594739860
	private Void _TrySaveCustomSortTypeCache() { }
	// RVA: 0x21219a8 VA: 0x75947399a8
	public Void .ctor() { }
}
```