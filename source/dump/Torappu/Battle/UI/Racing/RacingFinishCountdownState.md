# RacingFinishCountdownState

**Namespace:** `Torappu.Battle.UI.Racing`


## Fields

- `Text _textCountdownNum`

- `Image _coutdownCircle`

- `GameObject _finishCountdownInfoHolder`

- `UIAnimationLocation _finishAnim`

- `RacingUIPlugin m_plugin`

- `Int32 m_remainingTimeNum`

- `Tween m_tween`

- `PeriodicTimer periodicTimer`


## Methods

- `Void FixedUpdate()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Racing
public class RacingFinishCountdownState : UIStateNode
{
	private Text _textCountdownNum; // 0x20
	private Image _coutdownCircle; // 0x28
	private GameObject _finishCountdownInfoHolder; // 0x30
	private UIAnimationLocation _finishAnim; // 0x38
	private RacingUIPlugin m_plugin; // 0x48
	private Int32 m_remainingTimeNum; // 0x50
	private Tween m_tween; // 0x58
	private PeriodicTimer periodicTimer; // 0x60
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x18
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override UIStateEnum uiState { get; }

	// RVA: 0x20f09a0 VA: 0x75947089a0
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20f0a34 VA: 0x7594708a34
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20f0d0c VA: 0x7594708d0c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20f0d84 VA: 0x7594708d84
	private Void FixedUpdate() { }
	// RVA: 0x20f1274 VA: 0x7594709274
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20f1334 VA: 0x7594709334
	public Void .ctor() { }
	// RVA: 0x20f13e4 VA: 0x75947093e4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20f13ec VA: 0x75947093ec
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```