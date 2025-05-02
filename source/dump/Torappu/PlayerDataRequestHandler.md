# PlayerDataRequestHandler

**Namespace:** `Torappu`


## Properties

- `JsonSerializerSettings serializeSettings`


## Methods

- `JsonSerializerSettings get_serializeSettings()`

- `Void BeforeRequest(Request)`

- `Void MarkRequestFinish(Request)`

- `String SerializeRequest(Request)`

- `CustomYieldInstruction DeserializeResposne(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerDataRequestHandler : Singleton`1, IRequestHandler
{
	public static readonly JsonSerializerSettings SERIALIZE_SETTINGS; // 0x0
	private static DelegateBridge __Hotfix0_get_serializeSettings; // 0x8
	private static DelegateBridge __Hotfix0_BeforeRequest; // 0x10
	private static DelegateBridge __Hotfix0_MarkRequestFinish; // 0x18
	private static DelegateBridge __Hotfix0_SerializeRequest; // 0x20
	private static DelegateBridge __Hotfix0_DeserializeResposne; // 0x28
	private static DelegateBridge __Hotfix0_HandleResponse; // 0x30
	private static DelegateBridge __Hotfix0__DeserializeResponse; // 0x38
	private static DelegateBridge __Hotfix0__CreateRespMeta; // 0x40
	private static DelegateBridge __Hotfix0__ProcessPlayerData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public JsonSerializerSettings serializeSettings { get; }

	// RVA: 0x33b30d4 VA: 0x75959cb0d4
	public JsonSerializerSettings get_serializeSettings() { }
	// RVA: 0x33b3164 VA: 0x75959cb164
	public Void BeforeRequest(Request request) { }
	// RVA: 0x33b3234 VA: 0x75959cb234
	public Void MarkRequestFinish(Request request) { }
	// RVA: 0x33b330c VA: 0x75959cb30c
	public String SerializeRequest(Request request) { }
	// RVA: 0x VA: 0x0
	public CustomYieldInstruction DeserializeResposne(String responseText) { }
	// RVA: 0x VA: 0x0
	public RespMsgBundle`1 HandleResponse(CustomYieldInstruction deserializeTask) { }
	// RVA: 0x VA: 0x0
	private static WaitForAsyncTask`1 _DeserializeResponse(String respText, JObject rawPlayerData, PlayerDataModel prevPlayerData, Boolean useFastDelta, JsonSerializerSettings playerDataSetting) { }
	// RVA: 0x VA: 0x0
	private static PlayerResponseMeta _CreateRespMeta(RespType data, String respText, JsonSerializerSettings playerDataSetting) { }
	// RVA: 0x VA: 0x0
	private static Void _ProcessPlayerData(ResponseDeserializeResult`1 asyncResult) { }
	// RVA: 0x33b353c VA: 0x75959cb53c
	private Void .ctor() { }
	// RVA: 0x33b35dc VA: 0x75959cb5dc
	private static Void .cctor() { }
}
```