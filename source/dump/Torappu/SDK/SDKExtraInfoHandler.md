# SDKExtraInfoHandler

**Namespace:** `Torappu.SDK`


## Fields

- `String m_tpHeartBeat`


## Methods

- `Void add_eventGT3Message(Action`1)`

- `Void remove_eventGT3Message(Action`1)`

- `Void add_eventCloudAuthMessage(Action`1)`

- `Void remove_eventCloudAuthMessage(Action`1)`

- `Void add_eventUnbindGrantMessage(Action`1)`

- `Void remove_eventUnbindGrantMessage(Action`1)`

- `Void add_eventHGSDKInitMessage(Action`1)`

- `Void remove_eventHGSDKInitMessage(Action`1)`

- `Void add_eventLicenseRetMessage(Action`1)`

- `Void remove_eventLicenseRetMessage(Action`1)`

- `Void add_m_eventShareCallBackMessage(Action`1)`

- `Void remove_m_eventShareCallBackMessage(Action`1)`

- `Void add_eventSubscribeRetMessage(Action`1)`

- `Void remove_eventSubscribeRetMessage(Action`1)`

- `Void HandleExtraInfo(SDKExtraData)`

- `Void _HandleMessageMTP(JObject)`

- `Void _HandleMessageGT3(JObject)`

- `Void _HandleMessageXDQuerry(JObject)`

- `Void _HandleMessageCloudAuth(JObject)`

- `Void _HandleMessageUnbindGrant(JObject)`

- `Void _HandleMessageHGSDKInit(JObject)`

- `Void _HandleMessageLicenseRet(JObject)`

- `Void _HandleSubscription(SDKExtraData)`

- `Void _HandleRequestLogout(JObject)`

- `Void _HandleShareCallBackRet(JObject)`

- `Void BindShareCallBack(Action`1)`

- `Void _CleanShareCallBack()`

- `Void _AddWarning(TPMessage)`

- `String GetTPHeartBeat()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKExtraInfoHandler : Singleton`1
{
	private String m_tpHeartBeat; // 0x10
	private Dictionary`2 m_warnings; // 0x18
	private Action`1 eventGT3Message; // 0x20
	private Action`1 eventCloudAuthMessage; // 0x28
	private Action`1 eventUnbindGrantMessage; // 0x30
	private Action`1 eventHGSDKInitMessage; // 0x38
	private Action`1 eventLicenseRetMessage; // 0x40
	private Action`1 m_eventShareCallBackMessage; // 0x48
	private Action`1 eventSubscribeRetMessage; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_add_eventGT3Message; // 0x8
	private static DelegateBridge __Hotfix0_remove_eventGT3Message; // 0x10
	private static DelegateBridge __Hotfix0_add_eventCloudAuthMessage; // 0x18
	private static DelegateBridge __Hotfix0_remove_eventCloudAuthMessage; // 0x20
	private static DelegateBridge __Hotfix0_add_eventUnbindGrantMessage; // 0x28
	private static DelegateBridge __Hotfix0_remove_eventUnbindGrantMessage; // 0x30
	private static DelegateBridge __Hotfix0_add_eventHGSDKInitMessage; // 0x38
	private static DelegateBridge __Hotfix0_remove_eventHGSDKInitMessage; // 0x40
	private static DelegateBridge __Hotfix0_add_eventLicenseRetMessage; // 0x48
	private static DelegateBridge __Hotfix0_remove_eventLicenseRetMessage; // 0x50
	private static DelegateBridge __Hotfix0_add_m_eventShareCallBackMessage; // 0x58
	private static DelegateBridge __Hotfix0_remove_m_eventShareCallBackMessage; // 0x60
	private static DelegateBridge __Hotfix0_add_eventSubscribeRetMessage; // 0x68
	private static DelegateBridge __Hotfix0_remove_eventSubscribeRetMessage; // 0x70
	private static DelegateBridge __Hotfix0_HandleExtraInfo; // 0x78
	private static DelegateBridge __Hotfix0__HandleMessageMTP; // 0x80
	private static DelegateBridge __Hotfix0__HandleMessageGT3; // 0x88
	private static DelegateBridge __Hotfix0__HandleMessageXDQuerry; // 0x90
	private static DelegateBridge __Hotfix0__HandleMessageCloudAuth; // 0x98
	private static DelegateBridge __Hotfix0__HandleMessageUnbindGrant; // 0xa0
	private static DelegateBridge __Hotfix0__HandleMessageHGSDKInit; // 0xa8
	private static DelegateBridge __Hotfix0__HandleMessageLicenseRet; // 0xb0
	private static DelegateBridge __Hotfix0__HandleSubscription; // 0xb8
	private static DelegateBridge __Hotfix0__HandleRequestLogout; // 0xc0
	private static DelegateBridge __Hotfix0__HandleShareCallBackRet; // 0xc8
	private static DelegateBridge __Hotfix0_BindShareCallBack; // 0xd0
	private static DelegateBridge __Hotfix0__CleanShareCallBack; // 0xd8
	private static DelegateBridge __Hotfix0__AddWarning; // 0xe0
	private static DelegateBridge __Hotfix0_GetTPHeartBeat; // 0xe8
	private static DelegateBridge __Hotfix0_GetWarnings; // 0xf0
	private static DelegateBridge __Hotfix0_GenExtraInfoToLog; // 0xf8
	private static DelegateBridge __Hotfix0__GenHeartBeat; // 0x100


	// RVA: 0x3578e14 VA: 0x7595b90e14
	private Void .ctor() { }
	// RVA: 0x35781bc VA: 0x7595b901bc
	public Void add_eventGT3Message(Action`1 value) { }
	// RVA: 0x35780c8 VA: 0x7595b900c8
	public Void remove_eventGT3Message(Action`1 value) { }
	// RVA: 0x35783a4 VA: 0x7595b903a4
	public Void add_eventCloudAuthMessage(Action`1 value) { }
	// RVA: 0x35782b0 VA: 0x7595b902b0
	public Void remove_eventCloudAuthMessage(Action`1 value) { }
	// RVA: 0x357858c VA: 0x7595b9058c
	public Void add_eventUnbindGrantMessage(Action`1 value) { }
	// RVA: 0x3578498 VA: 0x7595b90498
	public Void remove_eventUnbindGrantMessage(Action`1 value) { }
	// RVA: 0x3578f24 VA: 0x7595b90f24
	public Void add_eventHGSDKInitMessage(Action`1 value) { }
	// RVA: 0x3579018 VA: 0x7595b91018
	public Void remove_eventHGSDKInitMessage(Action`1 value) { }
	// RVA: 0x357910c VA: 0x7595b9110c
	public Void add_eventLicenseRetMessage(Action`1 value) { }
	// RVA: 0x3579200 VA: 0x7595b91200
	public Void remove_eventLicenseRetMessage(Action`1 value) { }
	// RVA: 0x35792f4 VA: 0x7595b912f4
	private Void add_m_eventShareCallBackMessage(Action`1 value) { }
	// RVA: 0x35793e8 VA: 0x7595b913e8
	private Void remove_m_eventShareCallBackMessage(Action`1 value) { }
	// RVA: 0x35794dc VA: 0x7595b914dc
	public Void add_eventSubscribeRetMessage(Action`1 value) { }
	// RVA: 0x35795d0 VA: 0x7595b915d0
	public Void remove_eventSubscribeRetMessage(Action`1 value) { }
	// RVA: 0x35796c4 VA: 0x7595b916c4
	public Void HandleExtraInfo(SDKExtraData extraData) { }
	// RVA: 0x35798a0 VA: 0x7595b918a0
	private Void _HandleMessageMTP(JObject msg) { }
	// RVA: 0x3579978 VA: 0x7595b91978
	private Void _HandleMessageGT3(JObject msg) { }
	// RVA: 0x3579a50 VA: 0x7595b91a50
	private Void _HandleMessageXDQuerry(JObject msg) { }
	// RVA: 0x3579af0 VA: 0x7595b91af0
	private Void _HandleMessageCloudAuth(JObject msg) { }
	// RVA: 0x3579bcc VA: 0x7595b91bcc
	private Void _HandleMessageUnbindGrant(JObject msg) { }
	// RVA: 0x3579c80 VA: 0x7595b91c80
	private Void _HandleMessageHGSDKInit(JObject msg) { }
	// RVA: 0x3579d2c VA: 0x7595b91d2c
	private Void _HandleMessageLicenseRet(JObject msg) { }
	// RVA: 0x3579df8 VA: 0x7595b91df8
	private Void _HandleSubscription(SDKExtraData extraData) { }
	// RVA: 0x3579ea4 VA: 0x7595b91ea4
	private Void _HandleRequestLogout(JObject msg) { }
	// RVA: 0x3579f58 VA: 0x7595b91f58
	private Void _HandleShareCallBackRet(JObject msg) { }
	// RVA: 0x357ad80 VA: 0x7595b92d80
	public Void BindShareCallBack(Action`1 handler) { }
	// RVA: 0x357ae5c VA: 0x7595b92e5c
	public Void _CleanShareCallBack() { }
	// RVA: 0x357a230 VA: 0x7595b92230
	private Void _AddWarning(TPMessage msg) { }
	// RVA: 0x357aecc VA: 0x7595b92ecc
	public String GetTPHeartBeat() { }
	// RVA: 0x357af34 VA: 0x7595b92f34
	public Dictionary`2 GetWarnings() { }
	// RVA: 0x357af9c VA: 0x7595b92f9c
	public Dictionary`2 GenExtraInfoToLog() { }
	// RVA: 0x357b090 VA: 0x7595b93090
	private static String _GenHeartBeat() { }
}
```