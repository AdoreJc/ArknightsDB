# AssetSoundInfo

**Namespace:** `Torappu.Audio.Engine`


## Fields

- `String path`

- `Boolean loop`

- `Category category`


## Methods

- `String GetAsset()`

- `MixerDesc GetMixer()`

- `Boolean IsSameAudio(IAudioInfo)`

- `Boolean Loop()`

- `Single SpatialBlend()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Audio.Engine
public class AssetSoundInfo : ISoundInfo, IAudioInfo
{
	public String path; // 0x10
	public Boolean loop; // 0x18
	public Category category; // 0x1c


	// RVA: 0x67bb73c VA: 0x7598dd373c
	public String GetAsset() { }
	// RVA: 0x67bb744 VA: 0x7598dd3744
	public MixerDesc GetMixer() { }
	// RVA: 0x67bb75c VA: 0x7598dd375c
	public Boolean IsSameAudio(IAudioInfo other) { }
	// RVA: 0x67bb838 VA: 0x7598dd3838
	public Boolean Loop() { }
	// RVA: 0x67bb840 VA: 0x7598dd3840
	public Single SpatialBlend() { }
	// RVA: 0x67bb848 VA: 0x7598dd3848
	public static AssetSoundInfo EngineOnly_Create(String path, Boolean loop) { }
	// RVA: 0x67bb8cc VA: 0x7598dd38cc
	private Void .ctor() { }
}
```