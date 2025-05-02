# OptionsAndroid

**Namespace:** ` `


## Fields

- `VideoApi videoApi`

- `Boolean useFastOesPath`

- `Boolean showPosterFrame`

- `Boolean enableAudio360`

- `Audio360ChannelMode audio360ChannelMode`

- `Boolean preferSoftwareDecoder`

- `String httpHeaderJson`

- `Int32 fileOffset`


## Methods

- `String GetHTTPHeadersAsJSON()`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class OptionsAndroid : PlatformOptions, ISerializationCallbackReceiver
{
	public VideoApi videoApi; // 0x20
	public Boolean useFastOesPath; // 0x24
	public Boolean showPosterFrame; // 0x25
	public Boolean enableAudio360; // 0x26
	public Audio360ChannelMode audio360ChannelMode; // 0x28
	public Boolean preferSoftwareDecoder; // 0x2c
	public List`1 httpHeaders; // 0x30
	private String httpHeaderJson; // 0x38
	public Int32 fileOffset; // 0x40


	// RVA: 0x668261c VA: 0x7598c9a61c
	public String GetHTTPHeadersAsJSON() { }
	// RVA: 0x66853fc VA: 0x7598c9d3fc
	public override Boolean IsModified() { }
	// RVA: 0x6685498 VA: 0x7598c9d498
	public Void OnBeforeSerialize() { }
	// RVA: 0x6685514 VA: 0x7598c9d514
	public Void OnAfterDeserialize() { }
	// RVA: 0x66845bc VA: 0x7598c9c5bc
	public Void .ctor() { }
}
```