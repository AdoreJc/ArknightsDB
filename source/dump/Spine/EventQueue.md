# EventQueue

**Namespace:** `Spine`


## Fields

- `Action AnimationsChanged`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
internal class EventQueue
{
	private readonly List`1 eventQueueEntries; // 0x10
	internal Boolean drainDisabled; // 0x18
	private readonly AnimationState state; // 0x20
	private readonly Pool`1 trackEntryPool; // 0x28
	private Action AnimationsChanged; // 0x30


	// RVA: 0x61cf200 VA: 0x75987e7200
	internal Void add_AnimationsChanged(Action value) { }
	// RVA: 0x61cf29c VA: 0x75987e729c
	internal Void remove_AnimationsChanged(Action value) { }
	// RVA: 0x61ca318 VA: 0x75987e2318
	internal Void .ctor(AnimationState state, Action HandleAnimationsChanged, Pool`1 trackEntryPool) { }
	// RVA: 0x61cce40 VA: 0x75987e4e40
	internal Void Start(TrackEntry entry) { }
	// RVA: 0x61ccd20 VA: 0x75987e4d20
	internal Void Interrupt(TrackEntry entry) { }
	// RVA: 0x61ca780 VA: 0x75987e2780
	internal Void End(TrackEntry entry) { }
	// RVA: 0x61cd8fc VA: 0x75987e58fc
	internal Void Dispose(TrackEntry entry) { }
	// RVA: 0x61cc9ac VA: 0x75987e49ac
	internal Void Complete(TrackEntry entry) { }
	// RVA: 0x61cc880 VA: 0x75987e4880
	internal Void Event(TrackEntry entry, Event e) { }
	// RVA: 0x61caa08 VA: 0x75987e2a08
	internal Void Drain() { }
	// RVA: 0x61cdf1c VA: 0x75987e5f1c
	internal Void Clear() { }
}
```