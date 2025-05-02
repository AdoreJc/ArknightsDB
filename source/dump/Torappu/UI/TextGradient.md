# TextGradient

**Namespace:** `Torappu.UI`


## Fields

- `Color32 rightColor`

- `Color32 leftColor`

- `Single delta`


## Methods

- `Void _ApplyGradient(List`1, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TextGradient : BaseMeshEffect
{
	private Color32 rightColor; // 0x20
	private Color32 leftColor; // 0x24
	private Single delta; // 0x28


	// RVA: 0x2104360 VA: 0x759471c360
	public override Void ModifyMesh(VertexHelper vh) { }
	// RVA: 0x2104440 VA: 0x759471c440
	private Void _ApplyGradient(List`1 vertexList, Int32 start, Int32 end) { }
	// RVA: 0x21046f4 VA: 0x759471c6f4
	public Void .ctor() { }
}
```