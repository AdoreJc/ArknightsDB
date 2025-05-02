# ClipperRegistry

**Namespace:** `UnityEngine.UI`


## Methods

- `Void Cull()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class ClipperRegistry
{
	private static ClipperRegistry s_Instance; // 0x0
	private readonly IndexedSet`1 m_Clippers; // 0x10

	public static ClipperRegistry instance { get; }

	// RVA: 0x6915058 VA: 0x7598f2d058
	protected Void .ctor() { }
	// RVA: 0x6913cb8 VA: 0x7598f2bcb8
	public static ClipperRegistry get_instance() { }
	// RVA: 0x6913d44 VA: 0x7598f2bd44
	public Void Cull() { }
	// RVA: 0x69150e0 VA: 0x7598f2d0e0
	public static Void Register(IClipper c) { }
	// RVA: 0x6915150 VA: 0x7598f2d150
	public static Void Unregister(IClipper c) { }
	// RVA: 0x69151ac VA: 0x7598f2d1ac
	public static Void Disable(IClipper c) { }
}
```