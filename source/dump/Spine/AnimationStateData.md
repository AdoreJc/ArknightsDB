# AnimationStateData

**Namespace:** `Spine`


## Properties

- `SkeletonData SkeletonData`

- `Single DefaultMix`


## Methods

- `SkeletonData get_SkeletonData()`

- `Single get_DefaultMix()`

- `Void set_DefaultMix(Single)`

- `Void SetMix(String, String, Single)`

- `Void SetMix(Animation, Animation, Single)`

- `Single GetMix(Animation, Animation)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class AnimationStateData
{
	internal SkeletonData skeletonData; // 0x10
	private readonly Dictionary`2 animationToMixTime; // 0x18
	internal Single defaultMix; // 0x20

	public SkeletonData SkeletonData { get; }
	public Single DefaultMix { get; set; }

	// RVA: 0x61cf370 VA: 0x75987e7370
	public SkeletonData get_SkeletonData() { }
	// RVA: 0x61cf378 VA: 0x75987e7378
	public Single get_DefaultMix() { }
	// RVA: 0x61cf380 VA: 0x75987e7380
	public Void set_DefaultMix(Single value) { }
	// RVA: 0x61cf388 VA: 0x75987e7388
	public Void .ctor(SkeletonData skeletonData) { }
	// RVA: 0x61cf4c4 VA: 0x75987e74c4
	public Void SetMix(String fromName, String toName, Single duration) { }
	// RVA: 0x61cf5e8 VA: 0x75987e75e8
	public Void SetMix(Animation from, Animation to, Single duration) { }
	// RVA: 0x61cd5c0 VA: 0x75987e55c0
	public Single GetMix(Animation from, Animation to) { }
}
```