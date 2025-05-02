# PostProcessEffectSettings

**Namespace:** `UnityEngine.Rendering.PostProcessing`


## Fields

- `Boolean active`

- `BoolParameter enabled`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void SetAllOverridesTo(Boolean, Boolean)`

- `Int32 GetHash()`

- `ParameterOverride <OnEnable>b__3_2(FieldInfo)`


## Dump
```C#
// Dll : Unity.Postprocessing.Runtime.dll
// Namespace : UnityEngine.Rendering.PostProcessing
public class PostProcessEffectSettings : ScriptableObject
{
	public Boolean active; // 0x18
	public BoolParameter enabled; // 0x20
	internal ReadOnlyCollection`1 parameters; // 0x28


	// RVA: 0x68070bc VA: 0x7598e1f0bc
	private Void OnEnable() { }
	// RVA: 0x68075d0 VA: 0x7598e1f5d0
	private Void OnDisable() { }
	// RVA: 0x6807858 VA: 0x7598e1f858
	public Void SetAllOverridesTo(Boolean state, Boolean excludeEnabled) { }
	// RVA: 0x6807b00 VA: 0x7598e1fb00
	public virtual Boolean IsEnabledAndSupported(PostProcessRenderContext context) { }
	// RVA: 0x6807b1c VA: 0x7598e1fb1c
	public Int32 GetHash() { }
	// RVA: 0x6807dc4 VA: 0x7598e1fdc4
	public Void .ctor() { }
	// RVA: 0x6807e40 VA: 0x7598e1fe40
	private ParameterOverride <OnEnable>b__3_2(FieldInfo t) { }
}
```