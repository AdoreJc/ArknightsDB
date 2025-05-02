# SDKCore

**Namespace:** ` `


## Fields

- `SubscribeStatus m_status`

- `String <msgType>k__BackingField`


## Properties

- `String msgType`

- `SubscribeStatus status`


## Methods

- `String get_msgType()`

- `Void set_msgType(String)`

- `SubscribeStatus get_status()`

- `Void StartCenter(ISubMsgCenter)`

- `Void StopCenter(ISubMsgCenter)`

- `Void _HandleSDKExtraInfo(SDKExtraData)`

- `Void _HandleSubRet(JObject)`

- `Void _HandleUnsubRet(JObject)`

- `Void _LogError(SubscribeMessage, String)`

- `Void _HandleMsgPush(JObject)`

- `Void _UpdateSubStatus()`

- `Void _DoSubToSDK()`

- `Void _DoUnsubToSDK()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class SDKCore
{
	private readonly ErrorCode[] SILENT_ERRORS; // 0x10
	private HashSet`1 m_centers; // 0x18
	private SubscribeStatus m_status; // 0x20
	private String <msgType>k__BackingField; // 0x28

	public String msgType { get; set; }
	public SubscribeStatus status { get; }

	// RVA: 0x35ac85c VA: 0x7595bc485c
	public String get_msgType() { }
	// RVA: 0x35ac864 VA: 0x7595bc4864
	private Void set_msgType(String value) { }
	// RVA: 0x35ac86c VA: 0x7595bc486c
	public SubscribeStatus get_status() { }
	// RVA: 0x35ac874 VA: 0x7595bc4874
	public Void .ctor(String msgt) { }
	// RVA: 0x35ac920 VA: 0x7595bc4920
	public Void StartCenter(ISubMsgCenter center) { }
	// RVA: 0x35acbd8 VA: 0x7595bc4bd8
	public Void StopCenter(ISubMsgCenter center) { }
	// RVA: 0x35acc40 VA: 0x7595bc4c40
	private Void _HandleSDKExtraInfo(SDKExtraData extraData) { }
	// RVA: 0x35acc74 VA: 0x7595bc4c74
	private Void _HandleSubRet(JObject msg) { }
	// RVA: 0x35acd18 VA: 0x7595bc4d18
	private Void _HandleUnsubRet(JObject msg) { }
	// RVA: 0x35ad164 VA: 0x7595bc5164
	private Void _LogError(SubscribeMessage msg, String title) { }
	// RVA: 0x35acdb8 VA: 0x7595bc4db8
	private Void _HandleMsgPush(JObject msg) { }
	// RVA: 0x35acb40 VA: 0x7595bc4b40
	private Void _UpdateSubStatus() { }
	// RVA: 0x35ad388 VA: 0x7595bc5388
	private Void _DoSubToSDK() { }
	// RVA: 0x35ad270 VA: 0x7595bc5270
	private Void _DoUnsubToSDK() { }
}
```