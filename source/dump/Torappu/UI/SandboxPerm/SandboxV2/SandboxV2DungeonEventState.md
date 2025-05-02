# SandboxV2DungeonEventState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2EventView _eventView`

- `Boolean m_isInited`

- `String m_topicId`

- `SandboxV2DungeonPage m_page`

- `SandboxV2DungeonController m_controller`

- `SandboxV2EventProperty m_eventProp`


## Methods

- `Void _OnJumpToDungeonState(IStateBean)`

- `Void _OnJumpToCharSelectState(IStateBean)`

- `Void _InitIfNot()`

- `Void _HandleExpedition()`

- `Void _HandleChoice()`

- `Void _OpenExpeditionSquad()`

- `Void _OpenReceiveItemsDialog(List`1, Action)`

- `Void _InitNodeEventData()`

- `Void _UpdateView(Boolean, Boolean)`

- `Boolean _CheckUIStable()`

- `Void _OnBackPress()`

- `Boolean _CheckEventStatus()`

- `Void _ExitEvent()`

- `Void _NextEvent()`

- `Void OnBackPress()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnChoiceSelect(String)`

- `Void _HandleService(Action`1, Action)`

- `Void _OnSuccessNext(SandboxV2EventChoiceResponse)`

- `Void _OnSuccessLeave(SandboxV2EventChoiceResponse)`

- `Void _OnSuccessImpl(List`1, Action)`

- `Void _OnFail()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonEventState : SandboxV2TransparentState, IValueMsgReceiver
{
	private SandboxV2EventView _eventView; // 0x70
	private Boolean m_isInited; // 0x78
	private String m_topicId; // 0x80
	private SandboxV2DungeonPage m_page; // 0x88
	private SandboxV2DungeonController m_controller; // 0x90
	private SandboxV2EventProperty m_eventProp; // 0x98
	public const Int32 ON_CHOICE_SELECT; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToDungeonState; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToCharSelectState; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__HandleExpedition; // 0x38
	private static DelegateBridge __Hotfix0__HandleChoice; // 0x40
	private static DelegateBridge __Hotfix0__OpenExpeditionSquad; // 0x48
	private static DelegateBridge __Hotfix0__OpenReceiveItemsDialog; // 0x50
	private static DelegateBridge __Hotfix0__InitNodeEventData; // 0x58
	private static DelegateBridge __Hotfix0__UpdateView; // 0x60
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x68
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x70
	private static DelegateBridge __Hotfix0__CheckEventStatus; // 0x78
	private static DelegateBridge __Hotfix0__ExitEvent; // 0x80
	private static DelegateBridge __Hotfix0__NextEvent; // 0x88
	private static DelegateBridge __Hotfix0_OnBackPress; // 0x90
	private static DelegateBridge __Hotfix0_OnMessage; // 0x98
	private static DelegateBridge __Hotfix0__OnChoiceSelect; // 0xa0
	private static DelegateBridge __Hotfix0__HandleService; // 0xa8
	private static DelegateBridge __Hotfix0__OnSuccessNext; // 0xb0
	private static DelegateBridge __Hotfix0__OnSuccessLeave; // 0xb8
	private static DelegateBridge __Hotfix0__OnSuccessImpl; // 0xc0
	private static DelegateBridge __Hotfix0__OnFail; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x2545040 VA: 0x7594b5d040
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25450a4 VA: 0x7594b5d0a4
	protected override Void OnEnter() { }
	// RVA: 0x2545474 VA: 0x7594b5d474
	protected override Void OnResume() { }
	// RVA: 0x25454e0 VA: 0x7594b5d4e0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x25456d4 VA: 0x7594b5d6d4
	private Void _OnJumpToDungeonState(IStateBean stateBean) { }
	// RVA: 0x2545830 VA: 0x7594b5d830
	private Void _OnJumpToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x2545218 VA: 0x7594b5d218
	private Void _InitIfNot() { }
	// RVA: 0x2545adc VA: 0x7594b5dadc
	private Void _HandleExpedition() { }
	// RVA: 0x2546190 VA: 0x7594b5e190
	private Void _HandleChoice() { }
	// RVA: 0x25466ac VA: 0x7594b5e6ac
	private Void _OpenExpeditionSquad() { }
	// RVA: 0x2546834 VA: 0x7594b5e834
	private Void _OpenReceiveItemsDialog(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x254534c VA: 0x7594b5d34c
	private Void _InitNodeEventData() { }
	// RVA: 0x2546000 VA: 0x7594b5e000
	private Void _UpdateView(Boolean isEnter, Boolean playAnim) { }
	// RVA: 0x2546ab0 VA: 0x7594b5eab0
	private Boolean _CheckUIStable() { }
	// RVA: 0x2546bb4 VA: 0x7594b5ebb4
	private Void _OnBackPress() { }
	// RVA: 0x2545e88 VA: 0x7594b5de88
	private Boolean _CheckEventStatus() { }
	// RVA: 0x2546c40 VA: 0x7594b5ec40
	private Void _ExitEvent() { }
	// RVA: 0x2546d24 VA: 0x7594b5ed24
	private Void _NextEvent() { }
	// RVA: 0x2546dd4 VA: 0x7594b5edd4
	public Void OnBackPress() { }
	// RVA: 0x2546e3c VA: 0x7594b5ee3c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2546f0c VA: 0x7594b5ef0c
	private Void _OnChoiceSelect(String choiceId) { }
	// RVA: 0x2546340 VA: 0x7594b5e340
	private Void _HandleService(Action`1 onSuccess, Action onFail) { }
	// RVA: 0x254707c VA: 0x7594b5f07c
	private Void _OnSuccessNext(SandboxV2EventChoiceResponse response) { }
	// RVA: 0x2547334 VA: 0x7594b5f334
	private Void _OnSuccessLeave(SandboxV2EventChoiceResponse response) { }
	// RVA: 0x25471b0 VA: 0x7594b5f1b0
	private Void _OnSuccessImpl(List`1 rewards, Action callBack) { }
	// RVA: 0x2547414 VA: 0x7594b5f414
	private Void _OnFail() { }
	// RVA: 0x25474e8 VA: 0x7594b5f4e8
	public Void .ctor() { }
	// RVA: 0x2547604 VA: 0x7594b5f604
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2547608 VA: 0x7594b5f608
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2547610 VA: 0x7594b5f610
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```