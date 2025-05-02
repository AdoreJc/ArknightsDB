# SortItem

**Namespace:** ` `


## Fields

- `GameObject _panelDisable`

- `GameObject _panelUp`

- `GameObject _panelDown`

- `CharacterSortType m_sortTypeUp`

- `CharacterSortType m_sortTypeDown`


## Methods

- `Void Init(CharacterSortType, CharacterSortType)`

- `Void Render(UniEquipArchiveCharacterSortViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SortItem : IHotfixable
{
	private GameObject _panelDisable; // 0x10
	private GameObject _panelUp; // 0x18
	private GameObject _panelDown; // 0x20
	private CharacterSortType m_sortTypeUp; // 0x28
	private CharacterSortType m_sortTypeDown; // 0x2c
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22ec0f4 VA: 0x75949040f4
	public Void Init(CharacterSortType typeUp, CharacterSortType typeDown) { }
	// RVA: 0x22ec240 VA: 0x7594904240
	public Void Render(UniEquipArchiveCharacterSortViewModel viewModel) { }
	// RVA: 0x22ec754 VA: 0x7594904754
	public Void .ctor() { }
}
```