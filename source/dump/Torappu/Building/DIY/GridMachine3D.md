# GridMachine3D

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Boolean AddGridCube(IGridCube, Boolean)`

- `Boolean RemoveGridCube(IGridCube)`

- `Void ClearGridRect()`

- `Void ForEachGridCube(Action`1)`

- `Boolean CheckIntersection(IGridCube, Action`1)`

- `Boolean CheckIntersectionPairs(Action`2)`

- `Boolean CheckOutofRange(Int32, Int32, Int32, Int32, Int32, Int32, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class GridMachine3D
{
	private List`1 m_cubeList; // 0x10


	// RVA: 0x37da938 VA: 0x7595df2938
	private static Boolean _HitTest(IGridCube rect0, IGridCube rect1) { }
	// RVA: 0x37db0c4 VA: 0x7595df30c4
	public Boolean AddGridCube(IGridCube cube, Boolean force) { }
	// RVA: 0x37db2c0 VA: 0x7595df32c0
	public Boolean RemoveGridCube(IGridCube cube) { }
	// RVA: 0x37db354 VA: 0x7595df3354
	public Void ClearGridRect() { }
	// RVA: 0x37db3c4 VA: 0x7595df33c4
	public Void ForEachGridCube(Action`1 action) { }
	// RVA: 0x37db1d0 VA: 0x7595df31d0
	public Boolean CheckIntersection(IGridCube rect, Action`1 action) { }
	// RVA: 0x37db470 VA: 0x7595df3470
	public Boolean CheckIntersectionPairs(Action`2 action) { }
	// RVA: 0x37db5c4 VA: 0x7595df35c4
	public Boolean CheckOutofRange(Int32 x, Int32 y, Int32 z, Int32 w, Int32 h, Int32 d, Action`1 action) { }
	// RVA: 0x37dbb9c VA: 0x7595df3b9c
	public Void .ctor() { }
}
```