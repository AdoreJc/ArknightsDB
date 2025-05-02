# AudioChannelMixer

**Namespace:** `RenderHeads.Media.AVProVideo`


## Methods

- `Void set_Channel(Single[])`

- `Void Reset()`

- `Void ChangeChannelCount(Int32)`

- `Void OnAudioFilterRead(Single[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class AudioChannelMixer : MonoBehaviour
{
	private const Int32 MaxChannels; // 0x0
	private Single[] _channels; // 0x18

	public Single[] Channel { get; set; }

	// RVA: 0x6677444 VA: 0x7598c8f444
	public Single[] get_Channel() { }
	// RVA: 0x667744c VA: 0x7598c8f44c
	public Void set_Channel(Single[] value) { }
	// RVA: 0x6677454 VA: 0x7598c8f454
	private Void Reset() { }
	// RVA: 0x66774e8 VA: 0x7598c8f4e8
	private Void ChangeChannelCount(Int32 numChannels) { }
	// RVA: 0x6677610 VA: 0x7598c8f610
	private Void OnAudioFilterRead(Single[] data, Int32 channels) { }
	// RVA: 0x66776dc VA: 0x7598c8f6dc
	public Void .ctor() { }
}
```