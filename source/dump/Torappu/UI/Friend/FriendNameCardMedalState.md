# FriendNameCardMedalState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendNameCardMedalHolder _holder`

- `FriendNameCardMedalStateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnClickEvent(NameCardMedalType, String)`

- `Void OnClickSendNewState()`

- `Void <OnClickSendNewState>b__7_0(SetCardShowMedalResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendNameCardMedalState : PopupFloatState
{
	private FriendNameCardMedalHolder _holder; // 0x70
	private FriendNameCardMedalStateBean m_stateBean; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnClickSendNewState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28b1cf0 VA: 0x7594ec9cf0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b1d58 VA: 0x7594ec9d58
	private Void _InitIfNot() { }
	// RVA: 0x28b1e58 VA: 0x7594ec9e58
	protected override Void OnEnter() { }
	// RVA: 0x28b1f0c VA: 0x7594ec9f0c
	public Void OnClickEvent(NameCardMedalType type, String groupId) { }
	// RVA: 0x28b1fec VA: 0x7594ec9fec
	public Void OnClickSendNewState() { }
	// RVA: 0x28b2284 VA: 0x7594eca284
	public Void .ctor() { }
	// RVA: 0x28b2330 VA: 0x7594eca330
	private Void <OnClickSendNewState>b__7_0(SetCardShowMedalResponse response) { }
	// RVA: 0x28b2360 VA: 0x7594eca360
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```