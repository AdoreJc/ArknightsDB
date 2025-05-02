# YogaConfig

**Namespace:** `UnityEngine.Yoga`


## Fields

- `IntPtr _ygConfig`

- `Logger _logger`


## Properties

- `Boolean UseWebDefaults`

- `Single PointScaleFactor`


## Methods

- `Boolean get_UseWebDefaults()`

- `Void set_UseWebDefaults(Boolean)`

- `Void set_PointScaleFactor(Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsNativeModule.dll
// Namespace : UnityEngine.Yoga
internal class YogaConfig
{
	internal static readonly YogaConfig Default; // 0x0
	private IntPtr _ygConfig; // 0x10
	private Logger _logger; // 0x18

	internal IntPtr Handle { get; }
	public Boolean UseWebDefaults { get; set; }
	public Single PointScaleFactor { set; }

	// RVA: 0x6a3f184 VA: 0x7599057184
	private Void .ctor(IntPtr ygConfig) { }
	// RVA: 0x6a3f248 VA: 0x7599057248
	public Void .ctor() { }
	// RVA: 0x6a3f2b4 VA: 0x75990572b4
	protected override Void Finalize() { }
	// RVA: 0x6a3f3bc VA: 0x75990573bc
	internal IntPtr get_Handle() { }
	// RVA: 0x6a3f450 VA: 0x7599057450
	public Boolean get_UseWebDefaults() { }
	// RVA: 0x6a3f4c8 VA: 0x75990574c8
	public Void set_UseWebDefaults(Boolean value) { }
	// RVA: 0x6a3f550 VA: 0x7599057550
	public Void set_PointScaleFactor(Single value) { }
	// RVA: 0x6a3f5e8 VA: 0x75990575e8
	private static Void .cctor() { }
}
```