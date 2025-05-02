# ItemRepoChooseCharEvolveState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `SimpleLayoutContent _layoutContent`

- `CharClickEvent _itemEvent`

- `CancelDragIfFits _cancelDragIfFits`

- `Text _titleText`

- `GameObject _emptyPart`

- `Text _emptyText`

- `ItemRepoChooseCharEvolveAdapter m_adapter`

- `ItemRepoChooseCharEvolveStateBean m_stateBean`


## Methods

- `Void OnCharClick(CharacterCardViewModel)`

- `Void _InitListData(List`1, Boolean, CharCardType)`

- `Void OnEnable()`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <OnEnable>b__14_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharEvolveState : PopupFloatState
{
	private SimpleLayoutContent _layoutContent; // 0x70
	private CharClickEvent _itemEvent; // 0x78
	private CancelDragIfFits _cancelDragIfFits; // 0x80
	private Text _titleText; // 0x88
	private GameObject _emptyPart; // 0x90
	private Text _emptyText; // 0x98
	private ItemRepoChooseCharEvolveAdapter m_adapter; // 0xa0
	private ItemRepoChooseCharEvolveStateBean m_stateBean; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnCharClick; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__GeneDataList; // 0x20
	private static DelegateBridge __Hotfix0__InitListData; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2d1c124 VA: 0x7595334124
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d1c18c VA: 0x759533418c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d1c304 VA: 0x7595334304
	public Void OnCharClick(CharacterCardViewModel charViewModel) { }
	// RVA: 0x2d1c640 VA: 0x7595334640
	protected override Void OnEnter() { }
	// RVA: 0x2d1c864 VA: 0x7595334864
	private List`1 _GeneDataList() { }
	// RVA: 0x2d1cbe4 VA: 0x7595334be4
	private Void _InitListData(List`1 itemList, Boolean clickable, CharCardType cardType) { }
	// RVA: 0x2d1cd1c VA: 0x7595334d1c
	private Void OnEnable() { }
	// RVA: 0x2d1cdec VA: 0x7595334dec
	public Void .ctor() { }
	// RVA: 0x2d1ce98 VA: 0x7595334e98
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x2d1cf44 VA: 0x7595334f44
	private Void <OnEnable>b__14_0() { }
	// RVA: 0x2d1cfc8 VA: 0x7595334fc8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2d1cfd0 VA: 0x7595334fd0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```