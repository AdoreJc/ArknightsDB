# LineBuilderData

**Namespace:** `Torappu`


## Fields

- `Int32 numCornerVertices`

- `Int32 numCapVertices`

- `LineAlignment alignment`

- `Boolean loop`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class LineBuilderData
{
	public List`1 vertices; // 0x10
	public List`1 currentLineLengths; // 0x18
	public List`1 lineSmoothFactor; // 0x20
	public List`1 extrusionDirection; // 0x28
	public List`1 intersections; // 0x30
	public Int32 numCornerVertices; // 0x38
	public Int32 numCapVertices; // 0x3c
	public LineAlignment alignment; // 0x40
	public Boolean loop; // 0x44


	// RVA: 0x677162c VA: 0x7598d8962c
	public Void .ctor() { }
}
```