# BattleInOut

**Namespace:** `Torappu.Battle`


## Fields

- `InParams <input>k__BackingField`

- `OutParams <output>k__BackingField`

- `String <sceneAssetPath>k__BackingField`


## Properties

- `InParams input`

- `Boolean hasInput`

- `OutParams output`

- `String sceneAssetPath`


## Methods

- `InParams get_input()`

- `Void set_input(InParams)`

- `Boolean get_hasInput()`

- `Void SetInParams(InParams)`

- `GameTagMeta PrepareGameTag(String)`

- `OutParams get_output()`

- `Void set_output(OutParams)`

- `Void SetOutParams(OutParams)`

- `Void Clear()`

- `String get_sceneAssetPath()`

- `Void set_sceneAssetPath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleInOut : Singleton`1
{
	private InParams <input>k__BackingField; // 0x10
	private OutParams <output>k__BackingField; // 0x2c0
	private String <sceneAssetPath>k__BackingField; // 0x350
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_input; // 0x8
	private static DelegateBridge __Hotfix0_set_input; // 0x10
	private static DelegateBridge __Hotfix0_get_hasInput; // 0x18
	private static DelegateBridge __Hotfix0_SetInParams; // 0x20
	private static DelegateBridge __Hotfix0_PrepareGameTag; // 0x28
	private static DelegateBridge __Hotfix0_get_output; // 0x30
	private static DelegateBridge __Hotfix0_set_output; // 0x38
	private static DelegateBridge __Hotfix0_SetOutParams; // 0x40
	private static DelegateBridge __Hotfix0_Clear; // 0x48
	private static DelegateBridge __Hotfix0_get_sceneAssetPath; // 0x50
	private static DelegateBridge __Hotfix0_set_sceneAssetPath; // 0x58

	public InParams input { get; set; }
	public Boolean hasInput { get; }
	public OutParams output { get; set; }
	public String sceneAssetPath { get; set; }

	// RVA: 0x3f1b3d8 VA: 0x75965333d8
	private Void .ctor() { }
	// RVA: 0x3f1b468 VA: 0x7596533468
	public InParams get_input() { }
	// RVA: 0x3f1b50c VA: 0x759653350c
	private Void set_input(InParams value) { }
	// RVA: 0x3f1b5c4 VA: 0x75965335c4
	public Boolean get_hasInput() { }
	// RVA: 0x3f1b660 VA: 0x7596533660
	public Void SetInParams(InParams inParams) { }
	// RVA: 0x3f1b708 VA: 0x7596533708
	public GameTagMeta PrepareGameTag(String gameTag) { }
	// RVA: 0x3f1b7f4 VA: 0x75965337f4
	public OutParams get_output() { }
	// RVA: 0x3f1b898 VA: 0x7596533898
	private Void set_output(OutParams value) { }
	// RVA: 0x3f1b94c VA: 0x759653394c
	public Void SetOutParams(OutParams outParams) { }
	// RVA: 0x3f1b9f4 VA: 0x75965339f4
	public Void Clear() { }
	// RVA: 0x3f1baa8 VA: 0x7596533aa8
	public String get_sceneAssetPath() { }
	// RVA: 0x3f1bb10 VA: 0x7596533b10
	public Void set_sceneAssetPath(String value) { }
}
```