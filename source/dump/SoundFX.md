# SoundFX

**Namespace:** ` `


## Fields

- `SoundFXBank m_runtimeBank`

- `String asset`

- `Single weight`

- `Boolean important`

- `Boolean is2D`

- `Single delay`

- `Single minPitch`

- `Single maxPitch`

- `Single minVolume`

- `Single maxVolume`

- `Boolean ignoreTimeScale`


## Properties

- `Single randomVolume`

- `Single randomPitch`


## Methods

- `Single get_randomVolume()`

- `Single get_randomPitch()`

- `String GetAsset()`

- `MixerDesc GetMixer()`

- `Boolean Loop()`

- `Single SpatialBlend()`

- `Boolean IsSameAudio(IAudioInfo)`

- `AudioChannel Play(SoundFXBank, Vector3)`

- `Void Preload(SoundFXBank, String)`

- `Void _SetAudioChannel(AudioChannel, Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SoundFX : ISoundInfo, IAudioInfo
{
	private SoundFXBank m_runtimeBank; // 0x10
	public String asset; // 0x18
	public Single weight; // 0x20
	public Boolean important; // 0x24
	public Boolean is2D; // 0x25
	public Single delay; // 0x28
	public Single minPitch; // 0x2c
	public Single maxPitch; // 0x30
	public Single minVolume; // 0x34
	public Single maxVolume; // 0x38
	public Boolean ignoreTimeScale; // 0x3c

	public Single randomVolume { get; }
	public Single randomPitch { get; }

	// RVA: 0x3ee21cc VA: 0x75964fa1cc
	public Single get_randomVolume() { }
	// RVA: 0x3ee21d8 VA: 0x75964fa1d8
	public Single get_randomPitch() { }
	// RVA: 0x3ee21e4 VA: 0x75964fa1e4
	public String GetAsset() { }
	// RVA: 0x3ee21ec VA: 0x75964fa1ec
	public MixerDesc GetMixer() { }
	// RVA: 0x3ee22c0 VA: 0x75964fa2c0
	public Boolean Loop() { }
	// RVA: 0x3ee22e0 VA: 0x75964fa2e0
	public Single SpatialBlend() { }
	// RVA: 0x3ee22f8 VA: 0x75964fa2f8
	public Boolean IsSameAudio(IAudioInfo other) { }
	// RVA: 0x3ee1af4 VA: 0x75964f9af4
	public AudioChannel Play(SoundFXBank bank, Vector3 position) { }
	// RVA: 0x3ee1e34 VA: 0x75964f9e34
	public Void Preload(SoundFXBank bank, String persistTag) { }
	// RVA: 0x3ee23cc VA: 0x75964fa3cc
	private Void _SetAudioChannel(AudioChannel audioChannel, Vector3 position) { }
	// RVA: 0x3ee26d4 VA: 0x75964fa6d4
	public Void .ctor() { }
}
```