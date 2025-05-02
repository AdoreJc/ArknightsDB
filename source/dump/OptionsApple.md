# OptionsApple

**Namespace:** ` `


## Fields

- `AudioMode audioMode`

- `String httpHeaderJson`

- `String keyServerURLOverride`

- `String keyServerAuthToken`

- `String base64EncodedKeyBlob`


## Methods

- `String GetHTTPHeadersAsJSON()`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class OptionsApple : PlatformOptions, ISerializationCallbackReceiver
{
	public AudioMode audioMode; // 0x20
	public List`1 httpHeaders; // 0x28
	private String httpHeaderJson; // 0x30
	public String keyServerURLOverride; // 0x38
	public String keyServerAuthToken; // 0x40
	public String base64EncodedKeyBlob; // 0x48


	// RVA: 0x6684fa4 VA: 0x7598c9cfa4
	public String GetHTTPHeadersAsJSON() { }
	// RVA: 0x668519c VA: 0x7598c9d19c
	public override Boolean IsModified() { }
	// RVA: 0x6685244 VA: 0x7598c9d244
	public override String GetKeyServerURL() { }
	// RVA: 0x668524c VA: 0x7598c9d24c
	public override String GetKeyServerAuthToken() { }
	// RVA: 0x6685254 VA: 0x7598c9d254
	public override String GetDecryptionKey() { }
	// RVA: 0x668525c VA: 0x7598c9d25c
	public Void OnBeforeSerialize() { }
	// RVA: 0x66852d8 VA: 0x7598c9d2d8
	public Void OnAfterDeserialize() { }
	// RVA: 0x6685338 VA: 0x7598c9d338
	public Void .ctor() { }
}
```