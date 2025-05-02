# InfiniteRuntimeClip

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Playable m_Playable`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
internal class InfiniteRuntimeClip : RuntimeElement
{
	private Playable m_Playable; // 0x18
	private static readonly Int64 kIntervalEnd; // 0x0

	public override Int64 intervalStart { get; }
	public override Int64 intervalEnd { get; }
	public override Boolean enable { set; }

	// RVA: 0x682035c VA: 0x7598e3835c
	public Void .ctor(Playable playable) { }
	// RVA: 0x682f274 VA: 0x7598e47274
	public override Int64 get_intervalStart() { }
	// RVA: 0x682f27c VA: 0x7598e4727c
	public override Int64 get_intervalEnd() { }
	// RVA: 0x682f2d4 VA: 0x7598e472d4
	public override Void set_enable(Boolean value) { }
	// RVA: 0x682f348 VA: 0x7598e47348
	public override Void EvaluateAt(Double localTime, FrameData frameData) { }
	// RVA: 0x682f3a0 VA: 0x7598e473a0
	public override Void DisableAt(Double localTime, Double rootDuration, FrameData frameData) { }
	// RVA: 0x682f40c VA: 0x7598e4740c
	private static Void .cctor() { }
}
```