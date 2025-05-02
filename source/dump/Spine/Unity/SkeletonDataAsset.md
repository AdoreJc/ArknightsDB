# SkeletonDataAsset

**Namespace:** `Spine.Unity`


## Fields

- `Single scale`

- `TextAsset skeletonJSON`

- `Boolean isUpgradingBlendModeMaterials`

- `BlendModeMaterials blendModeMaterials`

- `Single defaultMix`

- `RuntimeAnimatorController controller`

- `SkeletonData skeletonData`

- `AnimationStateData stateData`


## Properties

- `Boolean IsLoaded`


## Methods

- `Boolean get_IsLoaded()`

- `Void Reset()`

- `Void Clear()`

- `AnimationStateData GetAnimationStateData()`

- `SkeletonData GetSkeletonData(Boolean)`

- `Void FillStateData()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonDataAsset : ScriptableObject
{
	public AtlasAssetBase[] atlasAssets; // 0x18
	public Single scale; // 0x20
	public TextAsset skeletonJSON; // 0x28
	public Boolean isUpgradingBlendModeMaterials; // 0x30
	public BlendModeMaterials blendModeMaterials; // 0x38
	public List`1 skeletonDataModifiers; // 0x40
	public String[] fromAnimation; // 0x48
	public String[] toAnimation; // 0x50
	public Single[] duration; // 0x58
	public Single defaultMix; // 0x60
	public RuntimeAnimatorController controller; // 0x68
	private SkeletonData skeletonData; // 0x70
	private AnimationStateData stateData; // 0x78

	public Boolean IsLoaded { get; }

	// RVA: 0x61f8f8c VA: 0x7598810f8c
	public Boolean get_IsLoaded() { }
	// RVA: 0x61f8f9c VA: 0x7598810f9c
	private Void Reset() { }
	// RVA: 0x61f8fec VA: 0x7598810fec
	public static SkeletonDataAsset CreateRuntimeInstance(TextAsset skeletonDataFile, AtlasAssetBase atlasAsset, Boolean initialize, Single scale) { }
	// RVA: 0x61f90b0 VA: 0x75988110b0
	public static SkeletonDataAsset CreateRuntimeInstance(TextAsset skeletonDataFile, AtlasAssetBase[] atlasAssets, Boolean initialize, Single scale) { }
	// RVA: 0x61f8fc4 VA: 0x7598810fc4
	public Void Clear() { }
	// RVA: 0x61f9178 VA: 0x7598811178
	public AnimationStateData GetAnimationStateData() { }
	// RVA: 0x61f7a10 VA: 0x759880fa10
	public SkeletonData GetSkeletonData(Boolean quiet) { }
	// RVA: 0x61f95e4 VA: 0x75988115e4
	internal Void InitializeWithData(SkeletonData sd) { }
	// RVA: 0x61f967c VA: 0x759881167c
	public Void FillStateData() { }
	// RVA: 0x61f91a0 VA: 0x75988111a0
	internal Atlas[] GetAtlasArray() { }
	// RVA: 0x61f9340 VA: 0x7598811340
	internal static SkeletonData ReadSkeletonData(Byte[] bytes, AttachmentLoader attachmentLoader, Single scale) { }
	// RVA: 0x61f952c VA: 0x759881152c
	internal static SkeletonData ReadSkeletonData(String text, AttachmentLoader attachmentLoader, Single scale) { }
	// RVA: 0x61f9750 VA: 0x7598811750
	public Void .ctor() { }
}
```