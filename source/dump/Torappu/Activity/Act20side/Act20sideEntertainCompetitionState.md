# Act20sideEntertainCompetitionState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `UIFullScreenImage _fullScreenImage`

- `Act20sideEntertainCompetitionView _view`

- `Boolean m_hasInited`

- `Act20sideEntertainCompViewModel m_viewModel`


## Methods

- `Void EventOnBackBtnClick()`

- `Void EventOnStage1StartBtnClick()`

- `Void EventOnStage2StartBtnClick()`

- `Void _InitIfNot()`

- `Void _StartBattle(String)`

- `Boolean _CheckIfStartBattleValid()`

- `Param _CreateParamToStartBattle(String)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntertainCompetitionState : PopupFadeState
{
	private UIFullScreenImage _fullScreenImage; // 0x70
	private Act20sideEntertainCompetitionView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private Act20sideEntertainCompViewModel m_viewModel; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnStage1StartBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_EventOnStage2StartBtnClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__StartBattle; // 0x30
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x38
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x32f6cc8 VA: 0x759590ecc8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f6d2c VA: 0x759590ed2c
	protected override Void OnEnter() { }
	// RVA: 0x32f7814 VA: 0x759590f814
	public Void EventOnBackBtnClick() { }
	// RVA: 0x32f7888 VA: 0x759590f888
	public Void EventOnStage1StartBtnClick() { }
	// RVA: 0x32f7a80 VA: 0x759590fa80
	public Void EventOnStage2StartBtnClick() { }
	// RVA: 0x32f6f34 VA: 0x759590ef34
	private Void _InitIfNot() { }
	// RVA: 0x32f7914 VA: 0x759590f914
	private Void _StartBattle(String stageId) { }
	// RVA: 0x32f7b14 VA: 0x759590fb14
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x32f7bac VA: 0x759590fbac
	private Param _CreateParamToStartBattle(String stageId) { }
	// RVA: 0x32f80e4 VA: 0x75959100e4
	public Void .ctor() { }
	// RVA: 0x32f8208 VA: 0x7595910208
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```