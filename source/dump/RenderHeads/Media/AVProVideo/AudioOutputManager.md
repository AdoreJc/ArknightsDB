# AudioOutputManager

**Namespace:** `RenderHeads.Media.AVProVideo`


## Methods

- `Void RequestAudio(AudioOutput, MediaPlayer, Single[], Int32, Int32, AudioOutputMode)`

- `Void GrabAudio(MediaPlayer, Single[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class AudioOutputManager
{
	private static AudioOutputManager _instance; // 0x0
	private Dictionary`2 _accessTrackers; // 0x10
	private Dictionary`2 _pcmData; // 0x18

	public static AudioOutputManager Instance { get; }

	// RVA: 0x6690724 VA: 0x7598ca8724
	public static AudioOutputManager get_Instance() { }
	// RVA: 0x66907b0 VA: 0x7598ca87b0
	private Void .ctor() { }
	// RVA: 0x6690888 VA: 0x7598ca8888
	public Void RequestAudio(AudioOutput _outputComponent, MediaPlayer mediaPlayer, Single[] data, Int32 channelMask, Int32 totalChannels, AudioOutputMode audioOutputMode) { }
	// RVA: 0x6690ed8 VA: 0x7598ca8ed8
	private Void GrabAudio(MediaPlayer player, Single[] data, Int32 channels) { }
}
```