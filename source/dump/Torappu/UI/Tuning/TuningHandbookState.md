# TuningHandbookState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningHandbookView _view`

- `Boolean m_inited`

- `TuningHandbookStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnBackClick()`

- `Void _SelectEmotion(String)`

- `Void _SelectLockEmotion(String)`

- `Void _PlayBgm(String, String, Boolean)`

- `Void _OnTransToPlayState(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookState : PopupFadeState, IValueMsgReceiver
{
	private TuningHandbookView _view; // 0x70
	private Boolean m_inited; // 0x78
	private TuningHandbookStateBean m_stateBean; // 0x80
	public const Int32 SELECT_EMOTION; // 0x0
	public const Int32 SELECT_LOCK_EMOTION; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x10
	private static DelegateBridge __Hotfix0__SelectEmotion; // 0x18
	private static DelegateBridge __Hotfix0__SelectLockEmotion; // 0x20
	private static DelegateBridge __Hotfix0__PlayBgm; // 0x28
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x30
	private static DelegateBridge __Hotfix0__OnTransToPlayState; // 0x38
	private static DelegateBridge __Hotfix0_OnMessage; // 0x40
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2322944 VA: 0x759493a944
	private Void _InitIfNot() { }
	// RVA: 0x2322a60 VA: 0x759493aa60
	protected override Void OnEnter() { }
	// RVA: 0x2322c5c VA: 0x759493ac5c
	private Void _OnBackClick() { }
	// RVA: 0x2322d70 VA: 0x759493ad70
	private Void _SelectEmotion(String eID) { }
	// RVA: 0x2323258 VA: 0x759493b258
	private Void _SelectLockEmotion(String eID) { }
	// RVA: 0x23230b4 VA: 0x759493b0b4
	private Void _PlayBgm(String bgmID, String orcheId, Boolean isPlayFromStart) { }
	// RVA: 0x2323308 VA: 0x759493b308
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2323480 VA: 0x759493b480
	private Void _OnTransToPlayState(IStateBean stateBean) { }
	// RVA: 0x2323584 VA: 0x759493b584
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2323688 VA: 0x759493b688
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23236f0 VA: 0x759493b6f0
	public Void .ctor() { }
	// RVA: 0x2323848 VA: 0x759493b848
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2323850 VA: 0x759493b850
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```