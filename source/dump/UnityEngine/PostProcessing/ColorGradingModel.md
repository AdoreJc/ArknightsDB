# ColorGradingModel

**Namespace:** `UnityEngine.PostProcessing`


## Fields

- `Settings m_Settings`

- `Boolean <isDirty>k__BackingField`

- `RenderTexture <bakedLut>k__BackingField`


## Properties

- `Settings settings`

- `Boolean isDirty`

- `RenderTexture bakedLut`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`

- `Boolean get_isDirty()`

- `RenderTexture get_bakedLut()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityEngine.PostProcessing
public class ColorGradingModel : PostProcessingModel
{
	private Settings m_Settings; // 0x18
	private Boolean <isDirty>k__BackingField; // 0x120
	private RenderTexture <bakedLut>k__BackingField; // 0x128

	public Settings settings { get; set; }
	public Boolean isDirty { get; set; }
	public RenderTexture bakedLut { get; set; }

	// RVA: 0x66725a0 VA: 0x7598c8a5a0
	public Settings get_settings() { }
	// RVA: 0x66725b0 VA: 0x7598c8a5b0
	public Void set_settings(Settings value) { }
	// RVA: 0x66725e4 VA: 0x7598c8a5e4
	public Boolean get_isDirty() { }
	// RVA: 0x66725ec VA: 0x7598c8a5ec
	internal Void set_isDirty(Boolean value) { }
	// RVA: 0x66725f8 VA: 0x7598c8a5f8
	public RenderTexture get_bakedLut() { }
	// RVA: 0x6672600 VA: 0x7598c8a600
	internal Void set_bakedLut(RenderTexture value) { }
	// RVA: 0x6672610 VA: 0x7598c8a610
	public override Void Reset() { }
	// RVA: 0x6672734 VA: 0x7598c8a734
	public override Void OnValidate() { }
	// RVA: 0x6672740 VA: 0x7598c8a740
	public Void .ctor() { }
}
```