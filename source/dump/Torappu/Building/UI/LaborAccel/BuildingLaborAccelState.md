# BuildingLaborAccelState

**Namespace:** `Torappu.Building.UI.LaborAccel`


## Fields

- `Image _imgLaborIcon`

- `Text _textTitle`

- `Text _textAccelTime`

- `Text _costLabor`

- `UILongPressButton _pressPlus`

- `UILongPressButton _pressMinus`

- `TextDataBinder _curLabor`

- `TextDataBinder _textRemainTime`

- `TextDataBinder _textTimeWasteAlert`

- `BuildingLaborAccelResultView _accelResultView`

- `LaborAccelStateBean m_stateBean`

- `UIItemViewModel m_laborIconModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnPlayerDataChanged(Object)`

- `Void _Render()`

- `Void Update()`

- `Void EventOnMinClicked()`

- `Void EventOnMaxClicked()`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`

- `Void _OnAccelCountPlus()`

- `Void _OnAccelCountMinus()`

- `Void _OnMaxAccelCountChanged()`

- `Boolean <OnEnter>b__22_0()`

- `Boolean <OnEnter>b__22_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.LaborAccel
public class BuildingLaborAccelState : PopupFloatState
{
	private Image _imgLaborIcon; // 0x70
	private Text _textTitle; // 0x78
	private Text _textAccelTime; // 0x80
	private Text _costLabor; // 0x88
	private Button[] _btnNegativeChange; // 0x90
	private Button[] _btnPositiveChange; // 0x98
	private UILongPressButton _pressPlus; // 0xa0
	private UILongPressButton _pressMinus; // 0xa8
	private TextDataBinder _curLabor; // 0xb0
	private TextDataBinder _textRemainTime; // 0xb8
	private TextDataBinder _textTimeWasteAlert; // 0xc0
	private BuildingLaborAccelResultView _accelResultView; // 0xc8
	private RectTransform[] _autoLayouts; // 0xd0
	private LaborAccelStateBean m_stateBean; // 0xd8
	private UIItemViewModel m_laborIconModel; // 0xe0
	private Boolean m_isInited; // 0xe8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0_EventOnMinClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnMaxClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnAccelCountPlus; // 0x58
	private static DelegateBridge __Hotfix0__OnAccelCountMinus; // 0x60
	private static DelegateBridge __Hotfix0__OnMaxAccelCountChanged; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x3e0ed88 VA: 0x7596426d88
	private Void _InitIfNot() { }
	// RVA: 0x3e0ee88 VA: 0x7596426e88
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3e0eef0 VA: 0x7596426ef0
	protected override Void OnEnter() { }
	// RVA: 0x3e0fe88 VA: 0x7596427e88
	protected override Void OnExit() { }
	// RVA: 0x3e1008c VA: 0x759642808c
	private Void _OnPlayerDataChanged(Object arg) { }
	// RVA: 0x3e0fbac VA: 0x7596427bac
	private Void _Render() { }
	// RVA: 0x3e102b8 VA: 0x75964282b8
	private Void Update() { }
	// RVA: 0x3e103ac VA: 0x75964283ac
	public Void EventOnMinClicked() { }
	// RVA: 0x3e104c4 VA: 0x75964284c4
	public Void EventOnMaxClicked() { }
	// RVA: 0x3e10540 VA: 0x7596428540
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3e1070c VA: 0x759642870c
	public Void EventOnCancelClicked() { }
	// RVA: 0x3e10780 VA: 0x7596428780
	private Void _OnAccelCountPlus() { }
	// RVA: 0x3e10870 VA: 0x7596428870
	private Void _OnAccelCountMinus() { }
	// RVA: 0x3e108f8 VA: 0x75964288f8
	private Void _OnMaxAccelCountChanged() { }
	// RVA: 0x3e10970 VA: 0x7596428970
	public Void .ctor() { }
	// RVA: 0x3e10c08 VA: 0x7596428c08
	private Boolean <OnEnter>b__22_0() { }
	// RVA: 0x3e10c1c VA: 0x7596428c1c
	private Boolean <OnEnter>b__22_1() { }
	// RVA: 0x3e10c30 VA: 0x7596428c30
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e10c38 VA: 0x7596428c38
	private Void <>xLuaBaseProxy_OnExit() { }
}
```