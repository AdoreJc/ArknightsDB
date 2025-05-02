# ClimbTowerSquadMultiEditView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadMultiEditGroupItemView _groupItemPrefab`

- `UIRecycleHorizonLayoutGroup _recycleSquadList`

- `UIAnimationLocation _switchAnim`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `Boolean m_hasInited`

- `ClimbTowerSquadMultiEditAdapter m_adapter`

- `AnimationSwitchTween m_switchTween`

- `Tween m_tween`

- `Boolean <needRebuild>k__BackingField`


## Properties

- `ClimbTowerSquadMultiEditGroupItemView itemPrefab`

- `Boolean needRebuild`


## Methods

- `ClimbTowerSquadMultiEditGroupItemView get_itemPrefab()`

- `Boolean get_needRebuild()`

- `Void set_needRebuild(Boolean)`

- `Void set_onSkillSelect(Action`2)`

- `Void set_onEquipSelect(Action`2)`

- `Void _InitIfNot()`

- `Single _GetPositionFromIndex(Int32, Single)`

- `Void _FocusToPos(Single, Boolean)`

- `Void OnProfessionClicked(ProfessionCategory)`

- `Int32 GetCurrIndex(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditView : DataBinder`1
{
	private const Single FOCUS_TWEEN_DURATION; // 0x0
	private const Single GROUP_VIEW_ELEMENT_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_SPACING; // 0x0
	private const Single GROUP_VIEW_HEADER_WIDTH; // 0x0
	private ClimbTowerSquadMultiEditGroupItemView _groupItemPrefab; // 0x20
	private UIRecycleHorizonLayoutGroup _recycleSquadList; // 0x28
	private UIAnimationLocation _switchAnim; // 0x30
	private RectTransform _viewport; // 0x40
	private ScrollRect _scrollView; // 0x48
	private Boolean m_hasInited; // 0x50
	private ClimbTowerSquadMultiEditAdapter m_adapter; // 0x58
	private AnimationSwitchTween m_switchTween; // 0x60
	private Tween m_tween; // 0x68
	private Boolean <needRebuild>k__BackingField; // 0x70
	private Action`2 <onSkillSelect>k__BackingField; // 0x78
	private Action`2 <onEquipSelect>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_itemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_needRebuild; // 0x8
	private static DelegateBridge __Hotfix0_set_needRebuild; // 0x10
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x18
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x20
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x28
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__CalculateVisibleColumnInsideChild; // 0x48
	private static DelegateBridge __Hotfix0__GetPositionInsideChild; // 0x50
	private static DelegateBridge __Hotfix0__GetPositionFromIndex; // 0x58
	private static DelegateBridge __Hotfix0__FocusToPos; // 0x60
	private static DelegateBridge __Hotfix0_OnProfessionClicked; // 0x68
	private static DelegateBridge __Hotfix0_GetCurrIndex; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public ClimbTowerSquadMultiEditGroupItemView itemPrefab { get; }
	public Boolean needRebuild { get; set; }
	public Action`2 onSkillSelect { get; set; }
	public Action`2 onEquipSelect { get; set; }

	// RVA: 0x2cc6cc8 VA: 0x75952decc8
	public ClimbTowerSquadMultiEditGroupItemView get_itemPrefab() { }
	// RVA: 0x2cc6d30 VA: 0x75952ded30
	public Boolean get_needRebuild() { }
	// RVA: 0x2cc6d98 VA: 0x75952ded98
	public Void set_needRebuild(Boolean value) { }
	// RVA: 0x2cc6e18 VA: 0x75952dee18
	public Action`2 get_onSkillSelect() { }
	// RVA: 0x2cc6e80 VA: 0x75952dee80
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x2cc6f04 VA: 0x75952def04
	public Action`2 get_onEquipSelect() { }
	// RVA: 0x2cc6f6c VA: 0x75952def6c
	public Void set_onEquipSelect(Action`2 value) { }
	// RVA: 0x2cc6ff0 VA: 0x75952deff0
	public override Void OnValueChanged(ClimbTowerSquadMultiEditProp property) { }
	// RVA: 0x2cc7144 VA: 0x75952df144
	private Void _InitIfNot() { }
	// RVA: 0x2cc75b0 VA: 0x75952df5b0
	private static Single _CalculateVisibleColumnInsideChild(Bounds elementBounds, Single viewportMin) { }
	// RVA: 0x2cc76b0 VA: 0x75952df6b0
	private static Single _GetPositionInsideChild(Single columnIndex) { }
	// RVA: 0x2cc72c0 VA: 0x75952df2c0
	private Single _GetPositionFromIndex(Int32 viewIndex, Single columnIndex) { }
	// RVA: 0x2cc7374 VA: 0x75952df374
	private Void _FocusToPos(Single pos, Boolean fastMode) { }
	// RVA: 0x2cc7768 VA: 0x75952df768
	public Void OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2cc7828 VA: 0x75952df828
	public Int32 GetCurrIndex(out Single columnIndex) { }
	// RVA: 0x2cc7b70 VA: 0x75952dfb70
	public Void .ctor() { }
}
```