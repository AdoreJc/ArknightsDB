# Act24sideBattleTrapState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideBattleTrapView _view`

- `RectTransform _btnExitRt`

- `Boolean m_hasInited`

- `Act24sideBattleTrapViewProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void _SendSetTrapConfirmRequest()`

- `Void _Close()`

- `Boolean _CheckIsTransiting()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnBtnExit()`

- `Void _EventOnConfirmClick()`

- `Void _EventOnTrapClick(String)`

- `Void <_SendSetTrapConfirmRequest>b__9_0(Act24SideSetToolResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapState : PopupFadeState, IValueMsgReceiver
{
	private Act24sideBattleTrapView _view; // 0x70
	private RectTransform _btnExitRt; // 0x78
	public const Int32 MSG_CONFIRM_CLICKED; // 0x0
	public const Int32 MSG_TRAP_CLICKED; // 0x0
	private Boolean m_hasInited; // 0x80
	private Act24sideBattleTrapViewProperty m_property; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SendSetTrapConfirmRequest; // 0x18
	private static DelegateBridge __Hotfix0__Close; // 0x20
	private static DelegateBridge __Hotfix0__CheckIsTransiting; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnExit; // 0x38
	private static DelegateBridge __Hotfix0__EventOnConfirmClick; // 0x40
	private static DelegateBridge __Hotfix0__EventOnTrapClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x329544c VA: 0x75958ad44c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32954b0 VA: 0x75958ad4b0
	protected override Void OnEnter() { }
	// RVA: 0x3295610 VA: 0x75958ad610
	private Void _InitIfNot() { }
	// RVA: 0x3295ca8 VA: 0x75958adca8
	private Void _SendSetTrapConfirmRequest() { }
	// RVA: 0x3296114 VA: 0x75958ae114
	private Void _Close() { }
	// RVA: 0x32962e0 VA: 0x75958ae2e0
	private Boolean _CheckIsTransiting() { }
	// RVA: 0x329646c VA: 0x75958ae46c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x329689c VA: 0x75958ae89c
	public Void EventOnBtnExit() { }
	// RVA: 0x3296534 VA: 0x75958ae534
	private Void _EventOnConfirmClick() { }
	// RVA: 0x32965ec VA: 0x75958ae5ec
	private Void _EventOnTrapClick(String trapId) { }
	// RVA: 0x3296e30 VA: 0x75958aee30
	public Void .ctor() { }
	// RVA: 0x3296ea0 VA: 0x75958aeea0
	private Void <_SendSetTrapConfirmRequest>b__9_0(Act24SideSetToolResponse response) { }
	// RVA: 0x3296ea4 VA: 0x75958aeea4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```