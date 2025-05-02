# SDKMeta

**Namespace:** `U8.SDK`


## Fields

- `String appID`

- `String appKey`

- `String channel`

- `String token`

- `String worldId`

- `String extension`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKMeta
{
	public String appID; // 0x10
	public String appKey; // 0x18
	public String channel; // 0x20
	public String token; // 0x28
	public String worldId; // 0x30
	public String extension; // 0x38


	// RVA: 0x67e542c VA: 0x7598dfd42c
	public Void .ctor() { }
	// RVA: 0x67e4ab4 VA: 0x7598dfcab4
	public Void .ctor(String jsonData) { }
	// RVA: 0x67e5434 VA: 0x7598dfd434
	public override String ToString() { }
}
```