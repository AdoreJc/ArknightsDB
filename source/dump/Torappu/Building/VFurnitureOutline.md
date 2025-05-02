# VFurnitureOutline

**Namespace:** `Torappu.Building`


## Fields

- `GameObject m_gameObject`

- `Boolean m_inited`

- `Boolean m_outlineOn`


## Properties

- `Boolean isOutlineOn`


## Methods

- `Boolean get_isOutlineOn()`

- `Void EnableOutline(Boolean)`

- `Void ResetOutline()`

- `Void _EnsureFurnitureOutlines()`

- `Void _InitFurnitureOutlines()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class VFurnitureOutline : IHotfixable
{
	private GameObject m_gameObject; // 0x10
	private List`1 m_outlineHolders; // 0x18
	private Boolean m_inited; // 0x20
	private Boolean m_outlineOn; // 0x21
	private static DelegateBridge __Hotfix0_get_isOutlineOn; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_EnableOutline; // 0x10
	private static DelegateBridge __Hotfix0_ResetOutline; // 0x18
	private static DelegateBridge __Hotfix0__EnsureFurnitureOutlines; // 0x20
	private static DelegateBridge __Hotfix0__InitFurnitureOutlines; // 0x28

	public Boolean isOutlineOn { get; }

	// RVA: 0x3785150 VA: 0x7595d9d150
	public Boolean get_isOutlineOn() { }
	// RVA: 0x37851b8 VA: 0x7595d9d1b8
	public Void .ctor(GameObject gameObject) { }
	// RVA: 0x37852a0 VA: 0x7595d9d2a0
	public Void EnableOutline(Boolean value) { }
	// RVA: 0x3785518 VA: 0x7595d9d518
	public Void ResetOutline() { }
	// RVA: 0x3785440 VA: 0x7595d9d440
	private Void _EnsureFurnitureOutlines() { }
	// RVA: 0x37856cc VA: 0x7595d9d6cc
	private Void _InitFurnitureOutlines() { }
}
```