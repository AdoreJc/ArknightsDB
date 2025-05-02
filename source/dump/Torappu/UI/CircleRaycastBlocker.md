# CircleRaycastBlocker

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _enableDisplay`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CircleRaycastBlocker : Graphic
{
	private const Boolean IS_TEST_MODE; // 0x0
	private Boolean _enableDisplay; // 0xa9


	// RVA: 0x2214b64 VA: 0x759482cb64
	public override Void SetMaterialDirty() { }
	// RVA: 0x2214b68 VA: 0x759482cb68
	public override Void SetVerticesDirty() { }
	// RVA: 0x2214b6c VA: 0x759482cb6c
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2214b84 VA: 0x759482cb84
	public override Boolean Raycast(Vector2 sp, Camera eventCamera) { }
	// RVA: 0x2214d98 VA: 0x759482cd98
	public Void .ctor() { }
}
```