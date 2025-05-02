# RuntimeClip

**Namespace:** `UnityEngine.Timeline`


## Fields

- `TimelineClip m_Clip`

- `Playable m_Playable`

- `Playable m_ParentMixer`


## Properties

- `TimelineClip clip`

- `Playable mixer`

- `Playable playable`


## Methods

- `Void Create(TimelineClip, Playable, Playable)`

- `TimelineClip get_clip()`

- `Playable get_mixer()`

- `Playable get_playable()`

- `Void SetTime(Double)`

- `Void SetDuration(Double)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
internal class RuntimeClip : RuntimeClipBase
{
	private TimelineClip m_Clip; // 0x18
	private Playable m_Playable; // 0x20
	private Playable m_ParentMixer; // 0x30

	public override Double start { get; }
	public override Double duration { get; }
	public TimelineClip clip { get; }
	public Playable mixer { get; }
	public Playable playable { get; }
	public override Boolean enable { set; }

	// RVA: 0x682f4bc VA: 0x7598e474bc
	public override Double get_start() { }
	// RVA: 0x682f4e8 VA: 0x7598e474e8
	public override Double get_duration() { }
	// RVA: 0x681e4f8 VA: 0x7598e364f8
	public Void .ctor(TimelineClip clip, Playable clipPlayable, Playable parentMixer) { }
	// RVA: 0x682f508 VA: 0x7598e47508
	private Void Create(TimelineClip clip, Playable clipPlayable, Playable parentMixer) { }
	// RVA: 0x682f598 VA: 0x7598e47598
	public TimelineClip get_clip() { }
	// RVA: 0x682f5a0 VA: 0x7598e475a0
	public Playable get_mixer() { }
	// RVA: 0x682f5ac VA: 0x7598e475ac
	public Playable get_playable() { }
	// RVA: 0x682f5b8 VA: 0x7598e475b8
	public override Void set_enable(Boolean value) { }
	// RVA: 0x682f6ec VA: 0x7598e476ec
	public Void SetTime(Double time) { }
	// RVA: 0x682f744 VA: 0x7598e47744
	public Void SetDuration(Double duration) { }
	// RVA: 0x682f79c VA: 0x7598e4779c
	public override Void EvaluateAt(Double localTime, FrameData frameData) { }
	// RVA: 0x682f994 VA: 0x7598e47994
	public override Void DisableAt(Double localTime, Double rootDuration, FrameData frameData) { }
}
```