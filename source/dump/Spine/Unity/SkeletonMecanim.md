# SkeletonMecanim

**Namespace:** `Spine.Unity`


## Fields

- `MecanimTranslator translator`

- `Boolean wasUpdatedAfterInit`

- `UpdateBonesDelegate _BeforeApply`

- `UpdateBonesDelegate _UpdateLocal`

- `UpdateBonesDelegate _UpdateWorld`

- `UpdateBonesDelegate _UpdateComplete`


## Properties

- `MecanimTranslator Translator`


## Methods

- `MecanimTranslator get_Translator()`

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

- `Void Update()`

- `Void ApplyAnimation()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonMecanim : SkeletonRenderer, ISkeletonAnimation
{
	protected MecanimTranslator translator; // 0xf0
	private Boolean wasUpdatedAfterInit; // 0xf8
	private UpdateBonesDelegate _BeforeApply; // 0x100
	private UpdateBonesDelegate _UpdateLocal; // 0x108
	private UpdateBonesDelegate _UpdateWorld; // 0x110
	private UpdateBonesDelegate _UpdateComplete; // 0x118

	public MecanimTranslator Translator { get; }

	// RVA: 0x6207b3c VA: 0x759881fb3c
	public MecanimTranslator get_Translator() { }
	// RVA: 0x6207b44 VA: 0x759881fb44
	protected Void add__BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6207be4 VA: 0x759881fbe4
	protected Void remove__BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6207c84 VA: 0x759881fc84
	protected Void add__UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6207d24 VA: 0x759881fd24
	protected Void remove__UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6207dc4 VA: 0x759881fdc4
	protected Void add__UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6207e64 VA: 0x759881fe64
	protected Void remove__UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6207f04 VA: 0x759881ff04
	protected Void add__UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6207fa4 VA: 0x759881ffa4
	protected Void remove__UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6208044 VA: 0x7598820044
	public Void add_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x6208048 VA: 0x7598820048
	public Void remove_BeforeApply(UpdateBonesDelegate value) { }
	// RVA: 0x620804c VA: 0x759882004c
	public Void add_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6208050 VA: 0x7598820050
	public Void remove_UpdateLocal(UpdateBonesDelegate value) { }
	// RVA: 0x6208054 VA: 0x7598820054
	public Void add_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x6208058 VA: 0x7598820058
	public Void remove_UpdateWorld(UpdateBonesDelegate value) { }
	// RVA: 0x620805c VA: 0x759882005c
	public Void add_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6208060 VA: 0x7598820060
	public Void remove_UpdateComplete(UpdateBonesDelegate value) { }
	// RVA: 0x6208064 VA: 0x7598820064
	public override Void Initialize(Boolean overwrite, Boolean quiet) { }
	// RVA: 0x62085d0 VA: 0x75988205d0
	public Void Update() { }
	// RVA: 0x62085f4 VA: 0x75988205f4
	protected Void ApplyAnimation() { }
	// RVA: 0x6209558 VA: 0x7598821558
	public override Void LateUpdate() { }
	// RVA: 0x620959c VA: 0x759882159c
	public Void .ctor() { }
}
```