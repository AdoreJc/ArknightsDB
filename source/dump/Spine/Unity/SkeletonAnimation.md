# SkeletonAnimation

**Namespace:** `Spine.Unity`


## Fields

- `Boolean <EnableManualUpdate>k__BackingField`

- `Boolean <cacheFixedBoundsCenterOnce>k__BackingField`

- `AnimationState state`

- `Boolean wasUpdatedAfterInit`

- `UpdateBonesDelegate _BeforeApply`

- `UpdateBonesDelegate _UpdateLocal`

- `UpdateBonesDelegate _UpdateWorld`

- `UpdateBonesDelegate _UpdateComplete`

- `String _animationName`

- `Boolean loop`

- `Single timeScale`


## Properties

- `Boolean EnableManualUpdate`

- `Boolean cacheFixedBoundsCenterOnce`

- `AnimationState AnimationState`

- `String AnimationName`


## Methods

- `Boolean get_EnableManualUpdate()`

- `Void set_EnableManualUpdate(Boolean)`

- `Boolean get_cacheFixedBoundsCenterOnce()`

- `Void set_cacheFixedBoundsCenterOnce(Boolean)`

- `AnimationState get_AnimationState()`

- `Void add__BeforeApply(UpdateBonesDelegate)`

- `Void remove__BeforeApply(UpdateBonesDelegate)`

- `Void add__UpdateLocal(UpdateBonesDelegate)`

- `Void remove__UpdateLocal(UpdateBonesDelegate)`

- `Void add__UpdateWorld(UpdateBonesDelegate)`

- `Void remove__UpdateWorld(UpdateBonesDelegate)`

- `Void add__UpdateComplete(UpdateBonesDelegate)`

- `Void remove__UpdateComplete(UpdateBonesDelegate)`

- `Void add_BeforeApply(UpdateBonesDelegate)`

- `Void remove_BeforeApply(UpdateBonesDelegate)`

- `Void add_UpdateLocal(UpdateBonesDelegate)`

- `Void remove_UpdateLocal(UpdateBonesDelegate)`

- `Void add_UpdateWorld(UpdateBonesDelegate)`

- `Void remove_UpdateWorld(UpdateBonesDelegate)`

- `Void add_UpdateComplete(UpdateBonesDelegate)`

- `Void remove_UpdateComplete(UpdateBonesDelegate)`

- `String get_AnimationName()`

- `Void set_AnimationName(String)`

- `Void TorappuOnly_SetRawAnimationName(String)`

- `Void Update()`

- `Void Update(Single)`

- `Void UpdateAnimationStatus(Single)`

- `Void ApplyAnimation()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonAnimation : SkeletonRenderer, ISkeletonAnimation, IAnimationStateComponent
{
	private Boolean <EnableManualUpdate>k__BackingField; // 0xf0
	private Boolean <cacheFixedBoundsCenterOnce>k__BackingField; // 0xf1
	public AnimationState state; // 0xf8
	private Boolean wasUpdatedAfterInit; // 0x100
	private UpdateBonesDelegate _BeforeApply; // 0x108
	private UpdateBonesDelegate _UpdateLocal; // 0x110
	private UpdateBonesDelegate _UpdateWorld; // 0x118
	private UpdateBonesDelegate _UpdateComplete; // 0x120
	private String _animationName; // 0x128
	public Boolean loop; // 0x130
	public Single timeScale; // 0x134

	public Boolean EnableManualUpdate { get; set; }
	public Boolean cacheFixedBoundsCenterOnce { get; set; }
	public AnimationState AnimationState { get; }
	public String AnimationName { get; set; }

	// RVA: 0x6202830 VA: 0x759881a830
	public Boolean get_EnableManualUpdate() { }
	// RVA: 0x6202838 VA: 0x759881a838
	public Void set_EnableManualUpdate(Boolean value) { }
	// RVA: 0x6202844 VA: 0x759881a844
	public Boolean get_cacheFixedBoundsCenterOnce() { }
	// RVA: 0x620284c VA: 0x759881a84c
	public Void set_cacheFixedBoundsCenterOnce(Boolean value) { }
	// RVA: 0x6202858 VA: 0x759881a858
	public AnimationState get_AnimationState() { }
	// RVA: 0x6202880 VA: 0x759881a880
	protected Void add__BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6202920 VA: 0x759881a920
	protected Void remove__BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x62029c0 VA: 0x759881a9c0
	protected Void add__UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6202a60 VA: 0x759881aa60
	protected Void remove__UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6202b00 VA: 0x759881ab00
	protected Void add__UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6202ba0 VA: 0x759881aba0
	protected Void remove__UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6202c40 VA: 0x759881ac40
	protected Void add__UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6202ce0 VA: 0x759881ace0
	protected Void remove__UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6202d80 VA: 0x759881ad80
	public Void add_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6202d84 VA: 0x759881ad84
	public Void remove_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6202d88 VA: 0x759881ad88
	public Void add_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6202d8c VA: 0x759881ad8c
	public Void remove_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6202d90 VA: 0x759881ad90
	public Void add_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6202d94 VA: 0x759881ad94
	public Void remove_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6202d98 VA: 0x759881ad98
	public Void add_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6202d9c VA: 0x759881ad9c
	public Void remove_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6202da0 VA: 0x759881ada0
	public String get_AnimationName() { }
	// RVA: 0x6202de8 VA: 0x759881ade8
	public Void set_AnimationName(String value) { }
	// RVA: 0x6202edc VA: 0x759881aedc
	public Void TorappuOnly_SetRawAnimationName(String animationName) { }
	// RVA: 0x6202eec VA: 0x759881aeec
	public static SkeletonAnimation AddToGameObject(GameObject gameObject, SkeletonDataAsset skeletonDataAsset, Boolean quiet) { }
	// RVA: 0x6202f70 VA: 0x759881af70
	public static SkeletonAnimation NewSkeletonAnimationGameObject(SkeletonDataAsset skeletonDataAsset, Boolean quiet) { }
	// RVA: 0x6202fec VA: 0x759881afec
	public override Void ClearState() { }
	// RVA: 0x62030ec VA: 0x759881b0ec
	public override Void Initialize(Boolean overwrite, Boolean quiet) { }
	// RVA: 0x6203564 VA: 0x759881b564
	private Void Update() { }
	// RVA: 0x6203590 VA: 0x759881b590
	public Void Update(Single deltaTime) { }
	// RVA: 0x62035e4 VA: 0x759881b5e4
	protected Void UpdateAnimationStatus(Single deltaTime) { }
	// RVA: 0x620362c VA: 0x759881b62c
	protected Void ApplyAnimation() { }
	// RVA: 0x6203700 VA: 0x759881b700
	public override Void LateUpdate() { }
	// RVA: 0x6203e80 VA: 0x759881be80
	public Void .ctor() { }
}
```