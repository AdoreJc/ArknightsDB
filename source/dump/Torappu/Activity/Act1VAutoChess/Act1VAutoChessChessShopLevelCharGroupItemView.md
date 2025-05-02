# Act1VAutoChessChessShopLevelCharGroupItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _rectLevelTagViewContainer`

- `Act1VAutoChessChessShopLevelTagView _levelTagViewPrefab`

- `SimpleLayoutContent _charList`

- `GridLayoutGroup _gridLayout`

- `IDragHandler <parentScrollHandler>k__BackingField`

- `Boolean m_hasInited`

- `Int32 m_cachedIndex`

- `Act1VAutoChessChessShopLevelTagView m_levelTagView`

- `CharListAdapter m_adapter`


## Properties

- `GridLayoutGroup gridLayout`

- `IDragHandler parentScrollHandler`


## Methods

- `GridLayoutGroup get_gridLayout()`

- `IDragHandler get_parentScrollHandler()`

- `Void set_parentScrollHandler(IDragHandler)`

- `Void Render(CharGroupViewParams)`

- `Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupItemViewModel, Int32)`

- `Int32 GetViewIndex()`

- `Act1VAutoChessChessShopLevelCharItemCardView GetLevelCharItemCardView(Int32)`

- `GameObject GetLevelLastIndexCharItemCardView()`

- `Void _InitIfNot()`

- `Void _RefreshAdapter(List`1)`

- `Void _RefreshCacheDict(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelCharGroupItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _rectLevelTagViewContainer; // 0x18
	private Act1VAutoChessChessShopLevelTagView _levelTagViewPrefab; // 0x20
	private SimpleLayoutContent _charList; // 0x28
	private GridLayoutGroup _gridLayout; // 0x30
	private IDragHandler <parentScrollHandler>k__BackingField; // 0x38
	private Boolean m_hasInited; // 0x40
	private Int32 m_cachedIndex; // 0x44
	private Act1VAutoChessChessShopLevelTagView m_levelTagView; // 0x48
	private CharListAdapter m_adapter; // 0x50
	private ListDict`2 m_cachedDict; // 0x58
	private static DelegateBridge __Hotfix0_get_gridLayout; // 0x0
	private static DelegateBridge __Hotfix0_get_parentScrollHandler; // 0x8
	private static DelegateBridge __Hotfix0_set_parentScrollHandler; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_TryRefreshCharCardViewsInfos; // 0x20
	private static DelegateBridge __Hotfix0_GetViewIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetLevelCharItemCardView; // 0x30
	private static DelegateBridge __Hotfix0_GetLevelLastIndexCharItemCardView; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__GenShowList; // 0x48
	private static DelegateBridge __Hotfix0__RefreshAdapter; // 0x50
	private static DelegateBridge __Hotfix0__RefreshCacheDict; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public GridLayoutGroup gridLayout { get; }
	private IDragHandler parentScrollHandler { get; set; }

	// RVA: 0x3319398 VA: 0x7595931398
	public GridLayoutGroup get_gridLayout() { }
	// RVA: 0x331a520 VA: 0x7595932520
	private IDragHandler get_parentScrollHandler() { }
	// RVA: 0x331a588 VA: 0x7595932588
	private Void set_parentScrollHandler(IDragHandler value) { }
	// RVA: 0x33194b0 VA: 0x75959314b0
	public Void Render(CharGroupViewParams viewParams) { }
	// RVA: 0x3319628 VA: 0x7595931628
	public Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupItemViewModel groupItemViewModel, Int32 viewIndex) { }
	// RVA: 0x3317f94 VA: 0x759592ff94
	public Int32 GetViewIndex() { }
	// RVA: 0x3319adc VA: 0x7595931adc
	public Act1VAutoChessChessShopLevelCharItemCardView GetLevelCharItemCardView(Int32 position) { }
	// RVA: 0x3319be0 VA: 0x7595931be0
	public GameObject GetLevelLastIndexCharItemCardView() { }
	// RVA: 0x331a60c VA: 0x759593260c
	private Void _InitIfNot() { }
	// RVA: 0x331a81c VA: 0x759593281c
	private List`1 _GenShowList(List`1 itemCardViewModelList) { }
	// RVA: 0x331a750 VA: 0x7595932750
	private Void _RefreshAdapter(List`1 itemCardViewModelList) { }
	// RVA: 0x331a9f4 VA: 0x75959329f4
	private Void _RefreshCacheDict(List`1 itemCardViewModelList) { }
	// RVA: 0x331ada4 VA: 0x7595932da4
	public Void .ctor() { }
}
```