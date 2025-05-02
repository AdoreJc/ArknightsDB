# Animation

**Namespace:** `Spine`


## Fields

- `SkeletonBinary _binary`

- `SkeletonData _data`


## Properties

- `Single Duration`

- `String Name`


## Methods

- `Void TORA_ReadAnimation()`

- `Void _SetTimelines(ExposedList`1)`

- `Void set_Timelines(ExposedList`1)`

- `Single get_Duration()`

- `Void set_Duration(Single)`

- `String get_Name()`

- `Boolean HasTimeline(Int32)`

- `Void Apply(Skeleton, Single, Single, Boolean, ExposedList`1, Single, MixBlend, MixDirection)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Animation
{
	internal String name; // 0x10
	private ExposedList`1 timelines; // 0x18
	internal HashSet`1 timelineIds; // 0x20
	internal Single duration; // 0x28
	private SkeletonBinary _binary; // 0x30
	private SkeletonData _data; // 0x38
	private Byte[] _buffer; // 0x40
	private ExposedList`1 _strings; // 0x48

	public ExposedList`1 Timelines { get; set; }
	public Single Duration { get; set; }
	public String Name { get; }

	// RVA: 0x61c40f4 VA: 0x75987dc0f4
	public Void .ctor(String name, ExposedList`1 timelines, Single duration) { }
	// RVA: 0x61c4364 VA: 0x75987dc364
	public Void .ctor(String name, Byte[] buffer, SkeletonBinary binary, SkeletonData data, ExposedList`1 strings) { }
	// RVA: 0x61c4444 VA: 0x75987dc444
	private Void TORA_ReadAnimation() { }
	// RVA: 0x61c452c VA: 0x75987dc52c
	private Void _SetTimelines(ExposedList`1 timelines) { }
	// RVA: 0x61c4510 VA: 0x75987dc510
	public ExposedList`1 get_Timelines() { }
	// RVA: 0x61c4528 VA: 0x75987dc528
	public Void set_Timelines(ExposedList`1 value) { }
	// RVA: 0x61c4728 VA: 0x75987dc728
	public Single get_Duration() { }
	// RVA: 0x61c4730 VA: 0x75987dc730
	public Void set_Duration(Single value) { }
	// RVA: 0x61c4738 VA: 0x75987dc738
	public String get_Name() { }
	// RVA: 0x61c4740 VA: 0x75987dc740
	public Boolean HasTimeline(Int32 id) { }
	// RVA: 0x61c47a0 VA: 0x75987dc7a0
	public Void Apply(Skeleton skeleton, Single lastTime, Single time, Boolean loop, ExposedList`1 events, Single alpha, MixBlend blend, MixDirection direction) { }
	// RVA: 0x61c498c VA: 0x75987dc98c
	public override String ToString() { }
	// RVA: 0x61c4994 VA: 0x75987dc994
	internal static Int32 BinarySearch(Single[] values, Single target, Int32 step) { }
	// RVA: 0x61c4a98 VA: 0x75987dca98
	internal static Int32 BinarySearch(Single[] values, Single target) { }
	// RVA: 0x61c4b0c VA: 0x75987dcb0c
	internal static Int32 LinearSearch(Single[] values, Single target, Int32 step) { }
}
```