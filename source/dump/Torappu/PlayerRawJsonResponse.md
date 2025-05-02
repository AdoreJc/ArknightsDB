# PlayerRawJsonResponse

**Namespace:** `Torappu`


## Fields

- `JObject content`


## Methods

- `PlayerDataDelta ConsumePlayerDataDelta()`

- `Void Deserialize(String, JsonSerializerSettings)`

- `String Serialize(JsonSerializerSettings)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerRawJsonResponse : ICustomizedBundleData, IPlayerPushMsgResponse
{
	public JObject content; // 0x10


	// RVA: 0x32c9364 VA: 0x75958e1364
	public PlayerDataDelta ConsumePlayerDataDelta() { }
	// RVA: 0x32c94f4 VA: 0x75958e14f4
	public List`1 AchievePushMessages() { }
	// RVA: 0x32c97a4 VA: 0x75958e17a4
	public Void Deserialize(String data, JsonSerializerSettings setting) { }
	// RVA: 0x32c9834 VA: 0x75958e1834
	public String Serialize(JsonSerializerSettings setting) { }
	// RVA: 0x32c98a0 VA: 0x75958e18a0
	public Void .ctor() { }
}
```