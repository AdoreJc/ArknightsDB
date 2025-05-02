# AudioMixerHolder

**Namespace:** `Torappu.Audio`


## Fields

- `AudioMixer mainMixer`

- `AudioMixerGroup musicGroup`

- `AudioMixerGroup voiceGroup`

- `AudioMixerGroup fxGroup`

- `AudioMixerGroup uiFxGroup`

- `AudioMixerGroup importantUIFxGroup`

- `AudioMixerGroup battleFxGroup`

- `AudioMixerGroup importantBattleFxGroup`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioMixerHolder : ScriptableObject, IHotfixable
{
	public AudioMixer mainMixer; // 0x18
	public AudioMixerGroup musicGroup; // 0x20
	public AudioMixerGroup voiceGroup; // 0x28
	public AudioMixerGroup fxGroup; // 0x30
	public AudioMixerGroup uiFxGroup; // 0x38
	public AudioMixerGroup importantUIFxGroup; // 0x40
	public AudioMixerGroup battleFxGroup; // 0x48
	public AudioMixerGroup importantBattleFxGroup; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x3eb75cc VA: 0x75964cf5cc
	public Void .ctor() { }
}
```