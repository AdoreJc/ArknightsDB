# LocalCharSortFilterSetting

**Namespace:** ` `


## Fields

- `CharacterSortType m_cachedSortType`

- `Int32 m_isCharStarMarkTop`

- `Boolean m_isDefault`

- `UInt32 m_loginHash`

- `DefaultType m_defaultType`


## Methods

- `Void _EnsureData()`

- `Void _ClearInvalidCache()`

- `Boolean _UpdateSessionIfDirty()`

- `CharacterSortType GetCharSortTypeCache()`

- `Void SetCharSortTypeCache(CharacterSortType)`

- `Boolean GetIsStarMarkTopMode()`

- `Void SetIsStarMarkTopMode(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LocalCharSortFilterSetting : IHotfixable
{
	private CharacterSortType m_cachedSortType; // 0x10
	private Int32 m_isCharStarMarkTop; // 0x14
	private Boolean m_isDefault; // 0x18
	private UInt32 m_loginHash; // 0x1c
	private DefaultType m_defaultType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureData; // 0x8
	private static DelegateBridge __Hotfix0__ClearInvalidCache; // 0x10
	private static DelegateBridge __Hotfix0__UpdateSessionIfDirty; // 0x18
	private static DelegateBridge __Hotfix0_GetCharSortTypeCache; // 0x20
	private static DelegateBridge __Hotfix0_SetCharSortTypeCache; // 0x28
	private static DelegateBridge __Hotfix0_GetIsStarMarkTopMode; // 0x30
	private static DelegateBridge __Hotfix0_SetIsStarMarkTopMode; // 0x38


	// RVA: 0x21d9700 VA: 0x75947f1700
	public Void .ctor(DefaultType defaultType) { }
	// RVA: 0x21ddb60 VA: 0x75947f5b60
	private Void _EnsureData() { }
	// RVA: 0x21ddbd8 VA: 0x75947f5bd8
	private Void _ClearInvalidCache() { }
	// RVA: 0x21ddc68 VA: 0x75947f5c68
	private Boolean _UpdateSessionIfDirty() { }
	// RVA: 0x21db130 VA: 0x75947f3130
	public CharacterSortType GetCharSortTypeCache() { }
	// RVA: 0x21db03c VA: 0x75947f303c
	public Void SetCharSortTypeCache(CharacterSortType sortType) { }
	// RVA: 0x21dbcf4 VA: 0x75947f3cf4
	public Boolean GetIsStarMarkTopMode() { }
	// RVA: 0x21dbdf4 VA: 0x75947f3df4
	public Void SetIsStarMarkTopMode(Boolean isStarMarkTop) { }
}
```