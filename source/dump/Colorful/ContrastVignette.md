# ContrastVignette

**Namespace:** `Colorful`


## Fields

- `Vector2 Center`

- `Single Sharpness`

- `Single Darkness`

- `Single Contrast`

- `Vector3 ContrastCoeff`

- `Single EdgeBlending`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ContrastVignette : BaseEffect
{
	public Vector2 Center; // 0x28
	public Single Sharpness; // 0x30
	public Single Darkness; // 0x34
	public Single Contrast; // 0x38
	public Vector3 ContrastCoeff; // 0x3c
	public Single EdgeBlending; // 0x48


	// RVA: 0x34e92a8 VA: 0x7595b012a8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e93f4 VA: 0x7595b013f4
	protected override String GetShaderName() { }
	// RVA: 0x34e9434 VA: 0x7595b01434
	public Void .ctor() { }
}
```