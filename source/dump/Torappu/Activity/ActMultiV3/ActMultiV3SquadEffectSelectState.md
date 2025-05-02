# ActMultiV3SquadEffectSelectState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadEffectSelectView _view`

- `RectTransform _topMenuContainer`

- `Boolean m_hasInited`

- `ActMultiV3SquadEffectSelectStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnBtnBack()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnSelectEffect(String)`

- `Void EventOnBtnConfirm()`

- `Void _TryUnlockEffect(ActMultiV3SquadEffectSelectModel, ActMultiV3SquadEffectModel)`

- `Void _TryEquipEffect(ActMultiV3SquadEffectSelectModel, ActMultiV3SquadEffectModel)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectSelectState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_SELECT_EFFECT; // 0x0
	private ActMultiV3SquadEffectSelectView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Boolean m_hasInited; // 0x80
	private ActMultiV3SquadEffectSelectStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__EventOnSelectEffect; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnConfirm; // 0x38
	private static DelegateBridge __Hotfix0__TryUnlockEffect; // 0x40
	private static DelegateBridge __Hotfix0__TryEquipEffect; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x313a4b8 VA: 0x75957524b8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x313a520 VA: 0x7595752520
	protected override Void OnEnter() { }
	// RVA: 0x313a738 VA: 0x7595752738
	protected override Void OnResume() { }
	// RVA: 0x313a65c VA: 0x759575265c
	private Void _InitIfNot() { }
	// RVA: 0x313a7ac VA: 0x75957527ac
	private Void _EventOnBtnBack() { }
	// RVA: 0x313a820 VA: 0x7595752820
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x313a8cc VA: 0x75957528cc
	private Void _EventOnSelectEffect(String effectId) { }
	// RVA: 0x313a9b0 VA: 0x75957529b0
	public Void EventOnBtnConfirm() { }
	// RVA: 0x313ad70 VA: 0x7595752d70
	private Void _TryUnlockEffect(ActMultiV3SquadEffectSelectModel viewModel, ActMultiV3SquadEffectModel currEffectModel) { }
	// RVA: 0x313aac4 VA: 0x7595752ac4
	private Void _TryEquipEffect(ActMultiV3SquadEffectSelectModel viewModel, ActMultiV3SquadEffectModel currEffectModel) { }
	// RVA: 0x313b00c VA: 0x759575300c
	public Void .ctor() { }
	// RVA: 0x313b0b8 VA: 0x75957530b8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x313b0c0 VA: 0x75957530c0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```