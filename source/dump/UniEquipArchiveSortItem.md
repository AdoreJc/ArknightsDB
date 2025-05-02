# UniEquipArchiveSortItem

**Namespace:** ` `


## Fields

- `GameObject _panelDisable`

- `GameObject _panelUp`

- `GameObject _panelDown`

- `UniEquipSortType m_sortTypeUp`

- `UniEquipSortType m_sortTypeDown`


## Methods

- `Void Init(UniEquipSortType, UniEquipSortType)`

- `Void Render(UniEquipSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UniEquipArchiveSortItem : IHotfixable
{
	private GameObject _panelDisable; // 0x10
	private GameObject _panelUp; // 0x18
	private GameObject _panelDown; // 0x20
	private UniEquipSortType m_sortTypeUp; // 0x28
	private UniEquipSortType m_sortTypeDown; // 0x2c
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22f1400 VA: 0x7594909400
	public Void Init(UniEquipSortType typeUp, UniEquipSortType typeDown) { }
	// RVA: 0x22f1600 VA: 0x7594909600
	public Void Render(UniEquipSortType sortType) { }
	// RVA: 0x22f1a9c VA: 0x7594909a9c
	public Void .ctor() { }
}
```