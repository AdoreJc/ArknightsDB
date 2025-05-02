# CharSelectCardListAdapter

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `GameObject _cardPrefab`

- `Boolean m_showSelectOrder`

- `IPlugin m_statePlugin`

- `CharacterSortType m_currentSortType`

- `String m_pageName`

- `Boolean m_AVGIsFirstItemRegistered`


## Methods

- `Void SetParams(CharSelectParam, IPlugin)`

- `Void NotifyCharChanged(Int32)`

- `Void _TryRegisterAVGFirstItem(CharSelectCardView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectCardListAdapter : UICharacterCardScrollAdapter`1
{
	private GameObject _cardPrefab; // 0x60
	private List`1 m_selectedChrInstIds; // 0x68
	private Boolean m_showSelectOrder; // 0x70
	private IPlugin m_statePlugin; // 0x78
	private CharacterSortType m_currentSortType; // 0x80
	private String m_pageName; // 0x88
	private Boolean m_AVGIsFirstItemRegistered; // 0x90
	private static DelegateBridge __Hotfix0_SetParams; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x10
	private static DelegateBridge __Hotfix0_NotifyCharChanged; // 0x18
	private static DelegateBridge __Hotfix0_CreateView; // 0x20
	private static DelegateBridge __Hotfix0__TryRegisterAVGFirstItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2cf54e8 VA: 0x759530d4e8
	public Void SetParams(CharSelectParam param, IPlugin plugin) { }
	// RVA: 0x2cf5684 VA: 0x759530d684
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, CharacterCardViewModel data) { }
	// RVA: 0x2cf5fc0 VA: 0x759530dfc0
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x2cf50e0 VA: 0x759530d0e0
	public Void NotifyCharChanged(Int32 chrInstId) { }
	// RVA: 0x2cf6044 VA: 0x759530e044
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2cf5e7c VA: 0x759530de7c
	private Void _TryRegisterAVGFirstItem(CharSelectCardView cardView) { }
	// RVA: 0x2cf6104 VA: 0x759530e104
	public Void .ctor() { }
}
```