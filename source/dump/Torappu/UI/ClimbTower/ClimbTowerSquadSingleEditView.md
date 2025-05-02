# ClimbTowerSquadSingleEditView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadSingleEditGroupItemView _groupItemPrefab`

- `UIRecycleHorizonLayoutGroup _recycleSquadList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `Boolean m_hasInited`

- `ClimbTowerSquadSingleEditAdapter m_adapter`

- `Tween m_tween`

- `Boolean <needRebuild>k__BackingField`


## Properties

- `ClimbTowerSquadSingleEditGroupItemView groupItemPrefab`

- `Boolean needRebuild`


## Methods

- `ClimbTowerSquadSingleEditGroupItemView get_groupItemPrefab()`

- `Boolean get_needRebuild()`

- `Void set_needRebuild(Boolean)`

- `Void set_onCharSelect(Action`1)`

- `Void _InitIfNot()`

- `Void _FocusToCharCard(ClimbTowerSquadSingleEditModel)`

- `Void _FocusToPos(Single, Boolean)`

- `Void OnProfessionClicked(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditView : DataBinder`1
{
	private const Single FOCUS_TWEEN_DURATION; // 0x0
	private ClimbTowerSquadSingleEditGroupItemView _groupItemPrefab; // 0x20
	private UIRecycleHorizonLayoutGroup _recycleSquadList; // 0x28
	private RectTransform _viewport; // 0x30
	private ScrollRect _scrollView; // 0x38
	private Boolean m_hasInited; // 0x40
	private ClimbTowerSquadSingleEditAdapter m_adapter; // 0x48
	private Tween m_tween; // 0x50
	private Boolean <needRebuild>k__BackingField; // 0x58
	private Action`1 <onCharSelect>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_groupItemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_needRebuild; // 0x8
	private static DelegateBridge __Hotfix0_set_needRebuild; // 0x10
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x18
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__FocusToCharCard; // 0x38
	private static DelegateBridge __Hotfix0__FocusToPos; // 0x40
	private static DelegateBridge __Hotfix0_OnProfessionClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public ClimbTowerSquadSingleEditGroupItemView groupItemPrefab { get; }
	public Boolean needRebuild { get; set; }
	public Action`1 onCharSelect { get; set; }

	// RVA: 0x2cc873c VA: 0x75952e073c
	public ClimbTowerSquadSingleEditGroupItemView get_groupItemPrefab() { }
	// RVA: 0x2ccc9d8 VA: 0x75952e49d8
	public Boolean get_needRebuild() { }
	// RVA: 0x2cca674 VA: 0x75952e2674
	public Void set_needRebuild(Boolean value) { }
	// RVA: 0x2cc87a4 VA: 0x75952e07a4
	public Action`1 get_onCharSelect() { }
	// RVA: 0x2ccabb8 VA: 0x75952e2bb8
	public Void set_onCharSelect(Action`1 value) { }
	// RVA: 0x2ccca40 VA: 0x75952e4a40
	public override Void OnValueChanged(ClimbTowerSquadSingleEditProp property) { }
	// RVA: 0x2cccb38 VA: 0x75952e4b38
	private Void _InitIfNot() { }
	// RVA: 0x2cccc08 VA: 0x75952e4c08
	private Void _FocusToCharCard(ClimbTowerSquadSingleEditModel editModel) { }
	// RVA: 0x2cccd28 VA: 0x75952e4d28
	private Void _FocusToPos(Single pos, Boolean fastMode) { }
	// RVA: 0x2ccb190 VA: 0x75952e3190
	public Void OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2cccf64 VA: 0x75952e4f64
	public Void .ctor() { }
}
```