# HexRaycastBlocker

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _enableDisplay`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class HexRaycastBlocker : Graphic
{
	private const Boolean IS_TEST_MODE; // 0x0
	private Boolean _enableDisplay; // 0xa9


	// RVA: 0x224afe8 VA: 0x7594862fe8
	public override Void SetMaterialDirty() { }
	// RVA: 0x224afec VA: 0x7594862fec
	public override Void SetVerticesDirty() { }
	// RVA: 0x224aff0 VA: 0x7594862ff0
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x224b008 VA: 0x7594863008
	public override Boolean Raycast(Vector2 sp, Camera eventCamera) { }
	// RVA: 0x224b428 VA: 0x7594863428
	public Void .ctor() { }
}
```