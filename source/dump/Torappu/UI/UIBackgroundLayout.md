# UIBackgroundLayout

**Namespace:** `Torappu.UI`


## Fields

- `Single _ratio`

- `RectTransform m_rectTrans`

- `Single m_curRatio`


## Properties

- `RectTransform rectTrans`


## Methods

- `RectTransform get_rectTrans()`

- `Void _UpdateRectTransform()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBackgroundLayout : UIBehaviour
{
	private Single _ratio; // 0x18
	private RectTransform m_rectTrans; // 0x20
	private Single m_curRatio; // 0x28

	public RectTransform rectTrans { get; }

	// RVA: 0x220de28 VA: 0x7594825e28
	public RectTransform get_rectTrans() { }
	// RVA: 0x220ded0 VA: 0x7594825ed0
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x220e058 VA: 0x7594826058
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x220e074 VA: 0x7594826074
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x220deec VA: 0x7594825eec
	private Void _UpdateRectTransform() { }
	// RVA: 0x220e090 VA: 0x7594826090
	public Void .ctor() { }
}
```