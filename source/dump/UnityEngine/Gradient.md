# Gradient

**Namespace:** `UnityEngine`


## Methods

- `Void Cleanup()`

- `Boolean Internal_Equals(IntPtr)`

- `Color Evaluate(Single)`

- `Void set_colorKeys(GradientColorKey[])`

- `Void set_alphaKeys(GradientAlphaKey[])`

- `Boolean Equals(Gradient)`

- `Void Evaluate_Injected(Single, out)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Gradient : IEquatable`1
{
	internal IntPtr m_Ptr; // 0x10

	public GradientColorKey[] colorKeys { get; set; }
	public GradientAlphaKey[] alphaKeys { get; set; }

	// RVA: 0x6876d00 VA: 0x7598e8ed00
	private static IntPtr Init() { }
	// RVA: 0x6876d28 VA: 0x7598e8ed28
	private Void Cleanup() { }
	// RVA: 0x6876d64 VA: 0x7598e8ed64
	private Boolean Internal_Equals(IntPtr other) { }
	// RVA: 0x6876da8 VA: 0x7598e8eda8
	public Void .ctor() { }
	// RVA: 0x6876df0 VA: 0x7598e8edf0
	protected override Void Finalize() { }
	// RVA: 0x6876ea8 VA: 0x7598e8eea8
	public Color Evaluate(Single time) { }
	// RVA: 0x6876f64 VA: 0x7598e8ef64
	public GradientColorKey[] get_colorKeys() { }
	// RVA: 0x6876fa0 VA: 0x7598e8efa0
	public Void set_colorKeys(GradientColorKey[] value) { }
	// RVA: 0x6876fe4 VA: 0x7598e8efe4
	public GradientAlphaKey[] get_alphaKeys() { }
	// RVA: 0x6877020 VA: 0x7598e8f020
	public Void set_alphaKeys(GradientAlphaKey[] value) { }
	// RVA: 0x6877064 VA: 0x7598e8f064
	public override Boolean Equals(Object o) { }
	// RVA: 0x687712c VA: 0x7598e8f12c
	public Boolean Equals(Gradient other) { }
	// RVA: 0x68771f4 VA: 0x7598e8f1f4
	public override Int32 GetHashCode() { }
	// RVA: 0x6876f10 VA: 0x7598e8ef10
	private Void Evaluate_Injected(Single time, out Color ret) { }
}
```