# ClimbTowerBuffSelectView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _stepList`

- `SimpleLayoutContent _buffList`

- `UIAtlasImage _logoPlan`

- `UIAtlasObject _logoAtlas`

- `Text _textPlan`

- `Boolean m_hasInited`

- `ClimbTowerInitStepListAdapter m_stepAdapter`

- `Adapter m_adapter`

- `TacticalBuffGroupModel m_buffGroupModel`


## Methods

- `Void set_onBuffToggle(Action`1)`

- `Void _InitIfNot()`

- `Void UpdatePlan(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBuffSelectView : DataBinder`1
{
	private SimpleLayoutContent _stepList; // 0x20
	private SimpleLayoutContent _buffList; // 0x28
	private UIAtlasImage _logoPlan; // 0x30
	private UIAtlasObject _logoAtlas; // 0x38
	private Text _textPlan; // 0x40
	public const String LOGO_PLAN_PREFERRED_NAME; // 0x0
	public const String LOGO_PLAN_FREE_NAME; // 0x0
	private Boolean m_hasInited; // 0x48
	private ClimbTowerInitStepListAdapter m_stepAdapter; // 0x50
	private Adapter m_adapter; // 0x58
	private TacticalBuffGroupModel m_buffGroupModel; // 0x60
	private Action`1 <onBuffToggle>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onBuffToggle; // 0x0
	private static DelegateBridge __Hotfix0_set_onBuffToggle; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePlan; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onBuffToggle { get; set; }

	// RVA: 0x2c8c5a0 VA: 0x75952a45a0
	private Action`1 get_onBuffToggle() { }
	// RVA: 0x2c89c98 VA: 0x75952a1c98
	public Void set_onBuffToggle(Action`1 value) { }
	// RVA: 0x2c8c608 VA: 0x75952a4608
	public override Void OnValueChanged(TacticalBuffGroupProp property) { }
	// RVA: 0x2c8c724 VA: 0x75952a4724
	private Void _InitIfNot() { }
	// RVA: 0x2c89aa0 VA: 0x75952a1aa0
	public Void UpdatePlan(Boolean isPlanFree) { }
	// RVA: 0x2c8c8dc VA: 0x75952a48dc
	public Void .ctor() { }
}
```