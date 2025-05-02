# AssetMusicInfo

**Namespace:** `Torappu.Audio.Engine`


## Fields

- `String intro`

- `String loop`


## Methods

- `String GetIntroAsset()`

- `String GetLoopAsset()`

- `Boolean IsSameAudio(IAudioInfo)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Audio.Engine
public class AssetMusicInfo : IMusicInfo, IAudioInfo
{
	public String intro; // 0x10
	public String loop; // 0x18


	// RVA: 0x67bb4dc VA: 0x7598dd34dc
	public String GetIntroAsset() { }
	// RVA: 0x67bb4e4 VA: 0x7598dd34e4
	public String GetLoopAsset() { }
	// RVA: 0x67bb4ec VA: 0x7598dd34ec
	public Boolean IsSameAudio(IAudioInfo other) { }
	// RVA: 0x67bb6a8 VA: 0x7598dd36a8
	public static AssetMusicInfo EngineOnly_Create(String intro, String loop) { }
	// RVA: 0x67bb734 VA: 0x7598dd3734
	private Void .ctor() { }
	// RVA: 0x67bb500 VA: 0x7598dd3500
	public static Boolean IsSameMusic(String intro, String loop, IAudioInfo other) { }
}
```