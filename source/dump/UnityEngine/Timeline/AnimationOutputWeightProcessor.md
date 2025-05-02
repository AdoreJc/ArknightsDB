# AnimationOutputWeightProcessor

**Namespace:** `UnityEngine.Timeline`


## Fields

- `AnimationPlayableOutput m_Output`


## Methods

- `Void FindMixers()`

- `Void FindMixers(Playable, Int32, Playable)`

- `Void Evaluate()`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
internal class AnimationOutputWeightProcessor : ITimelineEvaluateCallback
{
	private AnimationPlayableOutput m_Output; // 0x10
	private readonly List`1 m_Mixers; // 0x20


	// RVA: 0x681b568 VA: 0x7598e33568
	public Void .ctor(AnimationPlayableOutput output) { }
	// RVA: 0x681b634 VA: 0x7598e33634
	private Void FindMixers() { }
	// RVA: 0x681b71c VA: 0x7598e3371c
	private Void FindMixers(Playable parent, Int32 port, Playable node) { }
	// RVA: 0x681ba08 VA: 0x7598e33a08
	public Void Evaluate() { }
}
```