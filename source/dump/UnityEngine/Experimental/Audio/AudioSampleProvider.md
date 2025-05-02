# AudioSampleProvider

**Namespace:** `UnityEngine.Experimental.Audio`


## Fields

- `SampleFramesHandler sampleFramesAvailable`

- `SampleFramesHandler sampleFramesOverflow`


## Methods

- `Void InvokeSampleFramesAvailable(Int32)`

- `Void InvokeSampleFramesOverflow(Int32)`


## Dump
```C#
// Dll : UnityEngine.AudioModule.dll
// Namespace : UnityEngine.Experimental.Audio
public class AudioSampleProvider
{
	private SampleFramesHandler sampleFramesAvailable; // 0x10
	private SampleFramesHandler sampleFramesOverflow; // 0x18


	// RVA: 0x684ea10 VA: 0x7598e66a10
	private Void InvokeSampleFramesAvailable(Int32 sampleFrameCount) { }
	// RVA: 0x684ea38 VA: 0x7598e66a38
	private Void InvokeSampleFramesOverflow(Int32 droppedSampleFrameCount) { }
}
```