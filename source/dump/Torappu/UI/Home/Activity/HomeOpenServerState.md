# HomeOpenServerState

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `RectTransform _viewContainer`

- `OpenServerMainAbstractView m_mainView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SendGetChain(Int32)`

- `Void _SendGetCheckIn(Int32)`

- `Void _SendConfirmMissionRequest(String)`

- `Void _ShowCharDetail(String)`

- `Void <_SendGetChain>b__12_0(GetChainLogInRewardResponse)`

- `Void <_SendGetCheckIn>b__13_0(GetOpenServerCheckInRewardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class HomeOpenServerState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MSG_DISMISS; // 0x0
	public const Int32 MSG_TOTAL_LOGIN_ITEM_CLICK; // 0x0
	public const Int32 MSG_CHAIN_LOGIN_ITEM_CLICK; // 0x0
	public const Int32 MSG_MISSION_ITEM_CLICK; // 0x0
	public const Int32 MSG_CHAR_DETAIL_CLICK; // 0x0
	private RectTransform _viewContainer; // 0x70
	private OpenServerMainAbstractView m_mainView; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__SendGetChain; // 0x20
	private static DelegateBridge __Hotfix0__SendGetCheckIn; // 0x28
	private static DelegateBridge __Hotfix0__SendConfirmMissionRequest; // 0x30
	private static DelegateBridge __Hotfix0__ShowCharDetail; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x284f1c8 VA: 0x7594e671c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x284f22c VA: 0x7594e6722c
	private Void _InitIfNot() { }
	// RVA: 0x284f32c VA: 0x7594e6732c
	protected override Void OnEnter() { }
	// RVA: 0x284f4e0 VA: 0x7594e674e0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x284f7fc VA: 0x7594e677fc
	public Void _SendGetChain(Int32 rewardIndex) { }
	// RVA: 0x284f61c VA: 0x7594e6761c
	private Void _SendGetCheckIn(Int32 rewardIndex) { }
	// RVA: 0x284f9dc VA: 0x7594e679dc
	public Void _SendConfirmMissionRequest(String missionID_) { }
	// RVA: 0x284fc48 VA: 0x7594e67c48
	private Void _ShowCharDetail(String charId) { }
	// RVA: 0x284fd60 VA: 0x7594e67d60
	public Void .ctor() { }
	// RVA: 0x284fdd0 VA: 0x7594e67dd0
	private Void <_SendGetChain>b__12_0(GetChainLogInRewardResponse response) { }
	// RVA: 0x284ff00 VA: 0x7594e67f00
	private Void <_SendGetCheckIn>b__13_0(GetOpenServerCheckInRewardResponse response) { }
	// RVA: 0x2850030 VA: 0x7594e68030
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```