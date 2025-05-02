# BuiltinDebugViewsModel

**Namespace:** `UnityEngine.PostProcessing`


## Fields

- `Settings m_Settings`


## Properties

- `Settings settings`

- `Boolean willInterrupt`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`

- `Boolean get_willInterrupt()`

- `Boolean IsModeActive(Mode)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityEngine.PostProcessing
public class BuiltinDebugViewsModel : PostProcessingModel
{
	private Settings m_Settings; // 0x14

	public Settings settings { get; set; }
	public Boolean willInterrupt { get; }

	// RVA: 0x66723c8 VA: 0x7598c8a3c8
	public Settings get_settings() { }
	// RVA: 0x66723d8 VA: 0x7598c8a3d8
	public Void set_settings(Settings value) { }
	// RVA: 0x66723e8 VA: 0x7598c8a3e8
	public Boolean get_willInterrupt() { }
	// RVA: 0x667240c VA: 0x7598c8a40c
	public override Void Reset() { }
	// RVA: 0x6665fc4 VA: 0x7598c7dfc4
	public Boolean IsModeActive(Mode mode) { }
	// RVA: 0x667245c VA: 0x7598c8a45c
	public Void .ctor() { }
}
```