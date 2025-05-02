# Halftone

**Namespace:** `Colorful`


## Fields

- `Single Scale`

- `Single DotSize`

- `Single Angle`

- `Single Smoothness`

- `Vector2 Center`

- `Boolean Desaturate`


## Methods

- `Vector4 CMYKRot(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Halftone : BaseEffect
{
	public Single Scale; // 0x28
	public Single DotSize; // 0x2c
	public Single Angle; // 0x30
	public Single Smoothness; // 0x34
	public Vector2 Center; // 0x38
	public Boolean Desaturate; // 0x40


	// RVA: 0x34ebd08 VA: 0x7595b03d08
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ebfac VA: 0x7595b03fac
	private Vector4 CMYKRot(Single angle) { }
	// RVA: 0x34ebfd0 VA: 0x7595b03fd0
	protected override String GetShaderName() { }
	// RVA: 0x34ec010 VA: 0x7595b04010
	public Void .ctor() { }
}
```