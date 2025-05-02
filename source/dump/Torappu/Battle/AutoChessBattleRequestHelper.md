# AutoChessBattleRequestHelper

**Namespace:** `Torappu.Battle`


## Fields

- `AutoChessService m_service`

- `String m_actId`

- `IMsgListener m_pushMsgListener`


## Properties

- `AutoChessService service`


## Methods

- `AutoChessService get_service()`

- `Void Init(String)`

- `Void SetCallbackListener(IMsgListener)`

- `Void RemoveCallbackListener(IMsgListener)`

- `Void SendChooseTalentRequest(String)`

- `Void SendBuyRequest(AutoChessServiceBuyParam)`

- `Void SendSaleRequest(AutoChessServiceSaleParam)`

- `Void SendFreezeOrUnfreezeRequest(Int32)`

- `Void SendRefreshStoreRequest()`

- `Void SendUpdateStoreRequest()`

- `Void SendWearEquipItemRequest(AutoChessServiceWearEquipmentParam)`

- `Void SendUseSpellRequest(AutoChessServiceUseSpellParam)`

- `Void SendRoundBattleStartRequest(AutoChessRoundStartBattleParam)`

- `Void SendRoundBattleFinishRequest(String)`

- `Void OnMessage(AutoChessServiceMsg, ValueBundle)`

- `Boolean OnFail(AutoChessServiceMsg, ValueBundle)`

- `Boolean _CheckIsPushMsg(AutoChessServiceMsg)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoChessBattleRequestHelper : IMsgListener, IHotfixable, IDisposable
{
	private AutoChessService m_service; // 0x10
	private String m_actId; // 0x18
	private List`1 m_callbackListeners; // 0x20
	private IMsgListener m_pushMsgListener; // 0x28
	private static readonly AutoChessServiceMsg[] s_pushMsgTypes; // 0x0
	private static DelegateBridge __Hotfix0_get_service; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_SetCallbackListener; // 0x18
	private static DelegateBridge __Hotfix0_RemoveCallbackListener; // 0x20
	private static DelegateBridge __Hotfix0_SendChooseTalentRequest; // 0x28
	private static DelegateBridge __Hotfix0_SendBuyRequest; // 0x30
	private static DelegateBridge __Hotfix0_SendSaleRequest; // 0x38
	private static DelegateBridge __Hotfix0_SendFreezeOrUnfreezeRequest; // 0x40
	private static DelegateBridge __Hotfix0_SendRefreshStoreRequest; // 0x48
	private static DelegateBridge __Hotfix0_SendUpdateStoreRequest; // 0x50
	private static DelegateBridge __Hotfix0_SendWearEquipItemRequest; // 0x58
	private static DelegateBridge __Hotfix0_SendUseSpellRequest; // 0x60
	private static DelegateBridge __Hotfix0_SendRoundBattleStartRequest; // 0x68
	private static DelegateBridge __Hotfix0_SendRoundBattleFinishRequest; // 0x70
	private static DelegateBridge __Hotfix0_OnMessage; // 0x78
	private static DelegateBridge __Hotfix0_OnFail; // 0x80
	private static DelegateBridge __Hotfix0__CheckIsPushMsg; // 0x88
	private static DelegateBridge __Hotfix0_Dispose; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public AutoChessService service { get; }

	// RVA: 0x1c3f6c4 VA: 0x75942576c4
	public AutoChessService get_service() { }
	// RVA: 0x1c3f73c VA: 0x759425773c
	public Void Init(String actId) { }
	// RVA: 0x1c3f894 VA: 0x7594257894
	public Void SetCallbackListener(IMsgListener listener) { }
	// RVA: 0x1c3f9dc VA: 0x75942579dc
	public Void RemoveCallbackListener(IMsgListener listener) { }
	// RVA: 0x1c3fa8c VA: 0x7594257a8c
	public Void SendChooseTalentRequest(String effectId) { }
	// RVA: 0x1c3fb7c VA: 0x7594257b7c
	public Void SendBuyRequest(AutoChessServiceBuyParam param) { }
	// RVA: 0x1c3fc68 VA: 0x7594257c68
	public Void SendSaleRequest(AutoChessServiceSaleParam param) { }
	// RVA: 0x1c3fd54 VA: 0x7594257d54
	public Void SendFreezeOrUnfreezeRequest(Int32 opt) { }
	// RVA: 0x1c3fe38 VA: 0x7594257e38
	public Void SendRefreshStoreRequest() { }
	// RVA: 0x1c3fef8 VA: 0x7594257ef8
	public Void SendUpdateStoreRequest() { }
	// RVA: 0x1c3ffb8 VA: 0x7594257fb8
	public Void SendWearEquipItemRequest(AutoChessServiceWearEquipmentParam param) { }
	// RVA: 0x1c400a4 VA: 0x75942580a4
	public Void SendUseSpellRequest(AutoChessServiceUseSpellParam param) { }
	// RVA: 0x1c40190 VA: 0x7594258190
	public Void SendRoundBattleStartRequest(AutoChessRoundStartBattleParam param) { }
	// RVA: 0x1c4027c VA: 0x759425827c
	public Void SendRoundBattleFinishRequest(String data) { }
	// RVA: 0x1c4036c VA: 0x759425836c
	public Void OnMessage(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c4082c VA: 0x759425882c
	public Boolean OnFail(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c406d0 VA: 0x75942586d0
	private Boolean _CheckIsPushMsg(AutoChessServiceMsg msg) { }
	// RVA: 0x1c40a8c VA: 0x7594258a8c
	public Void Dispose() { }
	// RVA: 0x1c40b4c VA: 0x7594258b4c
	public Void .ctor() { }
	// RVA: 0x1c40c20 VA: 0x7594258c20
	private static Void .cctor() { }
}
```