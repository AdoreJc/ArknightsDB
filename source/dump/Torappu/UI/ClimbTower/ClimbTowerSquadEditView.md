# ClimbTowerSquadEditView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadEditGroupItemView _groupItemView`

- `UIRecycleHorizonLayoutGroup _recycleSquadList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `ClimbTowerSquadEditRecylceAdapter m_adapter`

- `Boolean m_hasInited`

- `Tween m_tween`

- `Int64 m_cachedGameStartTs`


## Properties

- `ClimbTowerSquadEditGroupItemView itemPrefab`

- `Int64 gameStartTs`


## Methods

- `ClimbTowerSquadEditGroupItemView get_itemPrefab()`

- `Int64 get_gameStartTs()`

- `Void set_onCharSelect(Action`1)`

- `Void Render(List`1, FocusParams, ClimbTowerSquadItemModel, Int64, Boolean)`

- `Void _InitIfNot()`

- `Single _GetPositionFromIndex(Int32, Single)`

- `Void _FocusToCharCard(ClimbTowerSquadItemModel, Boolean)`

- `Void _FocusToPos(Single, Boolean)`

- `Void OnProfessionClicked(ProfessionCategory)`

- `Int32 GetCurrIndex(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadEditView : MonoBehaviour, IHotfixable
{
	private const Single FOCUS_TWEEN_DURATION; // 0x0
	private const Single CHAR_CARD_BOUNDS_MARGIN; // 0x0
	private const Single GROUP_VIEW_ELEMENT_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_SPACING; // 0x0
	private const Single GROUP_VIEW_HEADER_WIDTH; // 0x0
	private ClimbTowerSquadEditGroupItemView _groupItemView; // 0x18
	private UIRecycleHorizonLayoutGroup _recycleSquadList; // 0x20
	private RectTransform _viewport; // 0x28
	private ScrollRect _scrollView; // 0x30
	private ClimbTowerSquadEditRecylceAdapter m_adapter; // 0x38
	private Boolean m_hasInited; // 0x40
	private Tween m_tween; // 0x48
	private Int64 m_cachedGameStartTs; // 0x50
	private Action`1 <onCharSelect>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_itemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_gameStartTs; // 0x8
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__CalculateVisibleColumnInsideChild; // 0x30
	private static DelegateBridge __Hotfix0__GetPositionInsideChild; // 0x38
	private static DelegateBridge __Hotfix0__GetPositionFromIndex; // 0x40
	private static DelegateBridge __Hotfix0__FocusToCharCard; // 0x48
	private static DelegateBridge __Hotfix0__FocusToPos; // 0x50
	private static DelegateBridge __Hotfix0_OnProfessionClicked; // 0x58
	private static DelegateBridge __Hotfix0_GetCurrIndex; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public ClimbTowerSquadEditGroupItemView itemPrefab { get; }
	public Int64 gameStartTs { get; }
	public Action`1 onCharSelect { get; set; }

	// RVA: 0x2cb9cb0 VA: 0x75952d1cb0
	public ClimbTowerSquadEditGroupItemView get_itemPrefab() { }
	// RVA: 0x2cb9d80 VA: 0x75952d1d80
	public Int64 get_gameStartTs() { }
	// RVA: 0x2cb9d18 VA: 0x75952d1d18
	public Action`1 get_onCharSelect() { }
	// RVA: 0x2cbc640 VA: 0x75952d4640
	public Void set_onCharSelect(Action`1 value) { }
	// RVA: 0x2cbb284 VA: 0x75952d3284
	public Void Render(List`1 charList, FocusParams focusParams, ClimbTowerSquadItemModel focusCharModel, Int64 gameStartTs, Boolean backFromStack) { }
	// RVA: 0x2cc0a98 VA: 0x75952d8a98
	private Void _InitIfNot() { }
	// RVA: 0x2cc1104 VA: 0x75952d9104
	private static Single _CalculateVisibleColumnInsideChild(Bounds elementBounds, Single viewportMin) { }
	// RVA: 0x2cc1204 VA: 0x75952d9204
	private static Single _GetPositionInsideChild(Single columnIndex) { }
	// RVA: 0x2cc0b68 VA: 0x75952d8b68
	private Single _GetPositionFromIndex(Int32 viewIndex, Single columnIndex) { }
	// RVA: 0x2cc0e58 VA: 0x75952d8e58
	private Void _FocusToCharCard(ClimbTowerSquadItemModel focusCharModel, Boolean fastMode) { }
	// RVA: 0x2cc0c1c VA: 0x75952d8c1c
	private Void _FocusToPos(Single pos, Boolean fastMode) { }
	// RVA: 0x2cbc0e8 VA: 0x75952d40e8
	public Void OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2cbbbf4 VA: 0x75952d3bf4
	public Int32 GetCurrIndex(out Single columnIndex) { }
	// RVA: 0x2cc12bc VA: 0x75952d92bc
	public Void .ctor() { }
}
```