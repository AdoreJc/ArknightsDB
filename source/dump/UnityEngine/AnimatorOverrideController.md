# AnimatorOverrideController

**Namespace:** `UnityEngine`


## Properties

- `RuntimeAnimatorController runtimeAnimatorController`

- `AnimationClip Item`

- `AnimationClip Item`

- `Int32 overridesCount`


## Methods

- `RuntimeAnimatorController get_runtimeAnimatorController()`

- `Void set_runtimeAnimatorController(RuntimeAnimatorController)`

- `AnimationClip get_Item(String)`

- `Void set_Item(String, AnimationClip)`

- `AnimationClip Internal_GetClipByName(String, Boolean)`

- `Void Internal_SetClipByName(String, AnimationClip)`

- `AnimationClip get_Item(AnimationClip)`

- `Void set_Item(AnimationClip, AnimationClip)`

- `AnimationClip GetClip(AnimationClip, Boolean)`

- `Void SetClip(AnimationClip, AnimationClip, Boolean)`

- `Void SendNotification()`

- `AnimationClip GetOriginalClip(Int32)`

- `AnimationClip GetOverrideClip(AnimationClip)`

- `Int32 get_overridesCount()`

- `Void GetOverrides(List`1)`

- `Void ApplyOverrides(IList`1)`

- `Void set_clips(AnimationClipPair[])`


## Dump
```C#
// Dll : UnityEngine.AnimationModule.dll
// Namespace : UnityEngine
public class AnimatorOverrideController : RuntimeAnimatorController
{
	internal OnOverrideControllerDirtyCallback OnOverrideControllerDirty; // 0x18

	public RuntimeAnimatorController runtimeAnimatorController { get; set; }
	public AnimationClip Item { get; set; }
	public AnimationClip Item { get; set; }
	public Int32 overridesCount { get; }
	public AnimationClipPair[] clips { get; set; }

	// RVA: 0x6847f48 VA: 0x7598e5ff48
	public Void .ctor() { }
	// RVA: 0x6848038 VA: 0x7598e60038
	public Void .ctor(RuntimeAnimatorController controller) { }
	// RVA: 0x6847ff4 VA: 0x7598e5fff4
	private static Void Internal_Create(AnimatorOverrideController self, RuntimeAnimatorController controller) { }
	// RVA: 0x6848090 VA: 0x7598e60090
	public RuntimeAnimatorController get_runtimeAnimatorController() { }
	// RVA: 0x68480cc VA: 0x7598e600cc
	public Void set_runtimeAnimatorController(RuntimeAnimatorController value) { }
	// RVA: 0x6848110 VA: 0x7598e60110
	public AnimationClip get_Item(String name) { }
	// RVA: 0x68481ac VA: 0x7598e601ac
	public Void set_Item(String name, AnimationClip value) { }
	// RVA: 0x6848158 VA: 0x7598e60158
	private AnimationClip Internal_GetClipByName(String name, Boolean returnEffectiveClip) { }
	// RVA: 0x6848200 VA: 0x7598e60200
	private Void Internal_SetClipByName(String name, AnimationClip clip) { }
	// RVA: 0x6848254 VA: 0x7598e60254
	public AnimationClip get_Item(AnimationClip clip) { }
	// RVA: 0x68482f0 VA: 0x7598e602f0
	public Void set_Item(AnimationClip clip, AnimationClip value) { }
	// RVA: 0x684829c VA: 0x7598e6029c
	private AnimationClip GetClip(AnimationClip originalClip, Boolean returnEffectiveClip) { }
	// RVA: 0x6848348 VA: 0x7598e60348
	private Void SetClip(AnimationClip originalClip, AnimationClip overrideClip, Boolean notify) { }
	// RVA: 0x68483a4 VA: 0x7598e603a4
	private Void SendNotification() { }
	// RVA: 0x68483e0 VA: 0x7598e603e0
	private AnimationClip GetOriginalClip(Int32 index) { }
	// RVA: 0x6848424 VA: 0x7598e60424
	private AnimationClip GetOverrideClip(AnimationClip originalClip) { }
	// RVA: 0x6848468 VA: 0x7598e60468
	public Int32 get_overridesCount() { }
	// RVA: 0x68484a4 VA: 0x7598e604a4
	public Void GetOverrides(List`1 overrides) { }
	// RVA: 0x6848718 VA: 0x7598e60718
	public Void ApplyOverrides(IList`1 overrides) { }
	// RVA: 0x6848978 VA: 0x7598e60978
	public AnimationClipPair[] get_clips() { }
	// RVA: 0x6848b58 VA: 0x7598e60b58
	public Void set_clips(AnimationClipPair[] value) { }
	// RVA: 0x6848c24 VA: 0x7598e60c24
	internal Void PerformOverrideClipListCleanup() { }
	// RVA: 0x6848c60 VA: 0x7598e60c60
	internal static Void OnInvalidateOverrideController(AnimatorOverrideController controller) { }
}
```