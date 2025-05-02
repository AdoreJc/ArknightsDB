# UnifiedServiceNetCoreHttp

**Namespace:** `Torappu.Common.UnifiedService`


## Fields

- `DynPushMsgHandler m_pushMsg`

- `String playerDataPath`

- `Action onPlayerDataChanged`


## Methods

- `Void add_onPlayerDataChanged(Action)`

- `Void remove_onPlayerDataChanged(Action)`

- `Request CreateRequest(String, ReqType)`

- `Void OnPlayerDataChanged()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void SetPushMsgHandler(String, MsgHandlerCallback`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Common.UnifiedService
public class UnifiedServiceNetCoreHttp : UnifiedServiceNetCore, IPlayerDataListener, IHotfixable
{
	private DynPushMsgHandler m_pushMsg; // 0x20
	public String playerDataPath; // 0x28
	private Action onPlayerDataChanged; // 0x30
	private static DelegateBridge __Hotfix0_add_onPlayerDataChanged; // 0x0
	private static DelegateBridge __Hotfix0_remove_onPlayerDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnConnectTo; // 0x10
	private static DelegateBridge __Hotfix0_OnDisConnect; // 0x18
	private static DelegateBridge __Hotfix0_CreateRequest; // 0x20
	private static DelegateBridge __Hotfix0_SendRequest; // 0x28
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x38
	private static DelegateBridge __Hotfix0_SetPushMsgHandler; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x37288e4 VA: 0x7595d408e4
	public Void add_onPlayerDataChanged(Action value) { }
	// RVA: 0x37289c0 VA: 0x7595d409c0
	public Void remove_onPlayerDataChanged(Action value) { }
	// RVA: 0x3728a9c VA: 0x7595d40a9c
	protected override Void OnConnectTo(String host, Int32 port) { }
	// RVA: 0x3728b30 VA: 0x7595d40b30
	protected override Void OnDisConnect() { }
	// RVA: 0x VA: 0x0
	public Request CreateRequest(String scode, ReqType requestData) { }
	// RVA: 0x VA: 0x0
	public ResultHandler`1 SendRequest(Request request) { }
	// RVA: 0x3728bb8 VA: 0x7595d40bb8
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3728c24 VA: 0x7595d40c24
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x VA: 0x0
	public Void SetPushMsgHandler(String path, MsgHandlerCallback`1 pHandler) { }
	// RVA: 0x3728cf4 VA: 0x7595d40cf4
	public Void .ctor() { }
}
```