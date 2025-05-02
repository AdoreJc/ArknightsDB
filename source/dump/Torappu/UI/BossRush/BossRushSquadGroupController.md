# BossRushSquadGroupController

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `SimpleLayoutContent _squadLayout`

- `GameObject _panelSingleTeamTips`

- `GameObject _leftbtn`

- `GameObject _rightbtn`

- `RectTransform _rectMiddleControl`

- `SimpleLayoutContent _squadTabLayout`

- `Boolean m_isInited`

- `BossRushSquadGroupViewModel m_squadGroupModel`

- `SquadViewModel m_squadModel`

- `String m_teamId`

- `SpriteHub m_professionHub`

- `SquadAdapter m_squadAdapter`

- `SquadTabAdapter m_squadTabAdapter`

- `SquadHomePlugin m_statePlugin`


## Methods

- `Void set_onSlotClicked(Action`1)`

- `Void set_onTabClicked(Action`1)`

- `Void InjectPlugin(SquadHomePlugin)`

- `Void _InitIfNot()`

- `Void _OnShowLeftArrow(Boolean)`

- `Void _OnCharCardClicked(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadGroupController : DataBinder`1
{
	private SimpleLayoutContent _squadLayout; // 0x20
	private GameObject _panelSingleTeamTips; // 0x28
	private GameObject _leftbtn; // 0x30
	private GameObject _rightbtn; // 0x38
	private RectTransform _rectMiddleControl; // 0x40
	private SimpleLayoutContent _squadTabLayout; // 0x48
	private Boolean m_isInited; // 0x50
	private BossRushSquadGroupViewModel m_squadGroupModel; // 0x58
	private SquadViewModel m_squadModel; // 0x60
	private String m_teamId; // 0x68
	private SpriteHub m_professionHub; // 0x70
	private SquadAdapter m_squadAdapter; // 0x78
	private SquadTabAdapter m_squadTabAdapter; // 0x80
	private SquadHomePlugin m_statePlugin; // 0x88
	private const Single MIDDLE_CONTROL_POS_Y_TEAM; // 0x0
	private Action`1 <onSlotClicked>k__BackingField; // 0x90
	private Action`1 <onTabClicked>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onSlotClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onTabClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onTabClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnShowLeftArrow; // 0x38
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onSlotClicked { get; set; }
	private Action`1 onTabClicked { get; set; }

	// RVA: 0x2e61cb0 VA: 0x7595479cb0
	private Action`1 get_onSlotClicked() { }
	// RVA: 0x2e61d18 VA: 0x7595479d18
	public Void set_onSlotClicked(Action`1 value) { }
	// RVA: 0x2e61d9c VA: 0x7595479d9c
	private Action`1 get_onTabClicked() { }
	// RVA: 0x2e61e04 VA: 0x7595479e04
	public Void set_onTabClicked(Action`1 value) { }
	// RVA: 0x2e61e88 VA: 0x7595479e88
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x2e62378 VA: 0x759547a378
	public Void InjectPlugin(SquadHomePlugin statePlugin) { }
	// RVA: 0x2e6214c VA: 0x759547a14c
	private Void _InitIfNot() { }
	// RVA: 0x2e622f4 VA: 0x759547a2f4
	private Void _OnShowLeftArrow(Boolean isShow) { }
	// RVA: 0x2e625c4 VA: 0x759547a5c4
	private Void _OnCharCardClicked(Options options) { }
	// RVA: 0x2e62698 VA: 0x759547a698
	public Void .ctor() { }
}
```