# AudioMixer

**Namespace:** `UnityEngine.Audio`


## Properties

- `AudioMixerGroup outputAudioMixerGroup`


## Methods

- `AudioMixerGroup get_outputAudioMixerGroup()`

- `AudioMixerSnapshot FindSnapshot(String)`

- `Void TransitionToSnapshots(AudioMixerSnapshot[], Single[], Single)`

- `Boolean SetFloat(String, Single)`

- `Boolean GetFloat(String, out)`


## Dump
```C#
// Dll : UnityEngine.AudioModule.dll
// Namespace : UnityEngine.Audio
public class AudioMixer : Object
{

	public AudioMixerGroup outputAudioMixerGroup { get; }

	// RVA: 0x684e500 VA: 0x7598e66500
	public AudioMixerGroup get_outputAudioMixerGroup() { }
	// RVA: 0x684e53c VA: 0x7598e6653c
	public AudioMixerSnapshot FindSnapshot(String name) { }
	// RVA: 0x684e580 VA: 0x7598e66580
	public AudioMixerGroup[] FindMatchingGroups(String subPath) { }
	// RVA: 0x684e5c4 VA: 0x7598e665c4
	public Void TransitionToSnapshots(AudioMixerSnapshot[] snapshots, Single[] weights, Single timeToReach) { }
	// RVA: 0x684e628 VA: 0x7598e66628
	public Boolean SetFloat(String name, Single value) { }
	// RVA: 0x684e67c VA: 0x7598e6667c
	public Boolean GetFloat(String name, out Single value) { }
}
```