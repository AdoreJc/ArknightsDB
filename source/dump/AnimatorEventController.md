# AnimatorEventController

**Namespace:** ` `


## Fields

- `AnimatorEventInfo _playInfo`

- `AnimatorEventInfo _stopInfo`

- `AnimatorEventInfo _triggerInfo`

- `VFurnitureEntity m_vFurniture`


## Properties

- `AnimatorEventInfo playInfo`

- `AnimatorEventInfo stopInfo`

- `AnimatorEventInfo triggerInfo`


## Methods

- `Void Init(VFurnitureEntity)`

- `AnimatorEventInfo get_playInfo()`

- `AnimatorEventInfo get_stopInfo()`

- `AnimatorEventInfo get_triggerInfo()`

- `Void Play()`

- `Void Stop()`

- `Void SetTrigger(String)`

- `Void OnExit()`

- `Void _EmitSignal(AnimatorEventInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AnimatorEventController
{
	private AnimatorEventInfo _playInfo; // 0x10
	private AnimatorEventInfo _stopInfo; // 0x18
	private AnimatorEventInfo _triggerInfo; // 0x20
	private List`1 _effects; // 0x28
	private VFurnitureEntity m_vFurniture; // 0x30

	public AnimatorEventInfo playInfo { get; }
	public AnimatorEventInfo stopInfo { get; }
	public AnimatorEventInfo triggerInfo { get; }

	// RVA: 0x3d06eac VA: 0x759631eeac
	public Void Init(VFurnitureEntity vFurniture) { }
	// RVA: 0x3d0874c VA: 0x759632074c
	public AnimatorEventInfo get_playInfo() { }
	// RVA: 0x3d08754 VA: 0x7596320754
	public AnimatorEventInfo get_stopInfo() { }
	// RVA: 0x3d0875c VA: 0x759632075c
	public AnimatorEventInfo get_triggerInfo() { }
	// RVA: 0x3d05f7c VA: 0x759631df7c
	public Void Play() { }
	// RVA: 0x3d060e4 VA: 0x759631e0e4
	public Void Stop() { }
	// RVA: 0x3d0624c VA: 0x759631e24c
	public Void SetTrigger(String triggerKey) { }
	// RVA: 0x3d0787c VA: 0x759631f87c
	public Void OnExit() { }
	// RVA: 0x3d08764 VA: 0x7596320764
	private Void _EmitSignal(AnimatorEventInfo animEventInfo) { }
	// RVA: 0x3d08a54 VA: 0x7596320a54
	public Void .ctor() { }
}
```