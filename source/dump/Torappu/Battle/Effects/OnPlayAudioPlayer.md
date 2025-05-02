# OnPlayAudioPlayer

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _audioSignal`

- `Single _delayToEmit`

- `Coroutine m_coroutine`


## Methods

- `Void _OnPlayInternal()`

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class OnPlayAudioPlayer : Behaviour, IHotfixable, IAudioSource
{
	private String _audioSignal; // 0x20
	private Single _delayToEmit; // 0x28
	private Coroutine m_coroutine; // 0x30


	// RVA: 0x200222c VA: 0x759461a22c
	public override Void OnPlay() { }
	// RVA: 0x20023f0 VA: 0x759461a3f0
	public override Void OnFinish() { }
	// RVA: 0x2002328 VA: 0x759461a328
	private Void _OnPlayInternal() { }
	// RVA: 0x200246c VA: 0x759461a46c
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x2002530 VA: 0x759461a530
	public Void .ctor() { }
}
```