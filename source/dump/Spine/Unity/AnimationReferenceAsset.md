# AnimationReferenceAsset

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonDataAsset skeletonDataAsset`

- `String animationName`

- `Animation animation`


## Properties

- `SkeletonDataAsset SkeletonDataAsset`

- `Animation Animation`


## Methods

- `SkeletonDataAsset get_SkeletonDataAsset()`

- `Animation get_Animation()`

- `Void Initialize()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class AnimationReferenceAsset : ScriptableObject, IHasSkeletonDataAsset
{
	private const Boolean QuietSkeletonData; // 0x0
	protected SkeletonDataAsset skeletonDataAsset; // 0x18
	protected String animationName; // 0x20
	private Animation animation; // 0x28

	public SkeletonDataAsset SkeletonDataAsset { get; }
	public Animation Animation { get; }

	// RVA: 0x61f782c VA: 0x759880f82c
	public SkeletonDataAsset get_SkeletonDataAsset() { }
	// RVA: 0x61f7834 VA: 0x759880f834
	public Animation get_Animation() { }
	// RVA: 0x61f7858 VA: 0x759880f858
	public Void Initialize() { }
	// RVA: 0x61f80b0 VA: 0x75988100b0
	public static Animation op_Implicit(AnimationReferenceAsset asset) { }
	// RVA: 0x61f80dc VA: 0x75988100dc
	public Void .ctor() { }
}
```