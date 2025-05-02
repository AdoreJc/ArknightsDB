# OptionsWindows

**Namespace:** ` `


## Fields

- `VideoApi videoApi`

- `Boolean useHardwareDecoding`

- `Boolean useUnityAudio`

- `Boolean forceAudioResample`

- `Boolean useTextureMips`

- `Boolean hintAlphaChannel`

- `Boolean useLowLatency`

- `String forceAudioOutputDeviceName`

- `Boolean enableAudio360`

- `Audio360ChannelMode audio360ChannelMode`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class OptionsWindows : PlatformOptions
{
	public VideoApi videoApi; // 0x20
	public Boolean useHardwareDecoding; // 0x24
	public Boolean useUnityAudio; // 0x25
	public Boolean forceAudioResample; // 0x26
	public Boolean useTextureMips; // 0x27
	public Boolean hintAlphaChannel; // 0x28
	public Boolean useLowLatency; // 0x29
	public String forceAudioOutputDeviceName; // 0x30
	public List`1 preferredFilters; // 0x38
	public Boolean enableAudio360; // 0x40
	public Audio360ChannelMode audio360ChannelMode; // 0x44


	// RVA: 0x6684eec VA: 0x7598c9ceec
	public override Boolean IsModified() { }
	// RVA: 0x66844d0 VA: 0x7598c9c4d0
	public Void .ctor() { }
}
```