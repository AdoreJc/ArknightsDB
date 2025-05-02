# GridMachine

**Namespace:** `Torappu.Building.DIY`


## Methods

- `Boolean AddGridRect(IGridRect, Boolean)`

- `Boolean RemoveGridRect(IGridRect)`

- `Void ClearGridRect()`

- `Void ForEachGridRect(Action`1)`

- `Boolean CheckIntersection(IGridRect, Action`1)`

- `Boolean CheckIntersectionPairs(Action`2)`

- `Boolean CheckOutofRange(Int32, Int32, Int32, Int32, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class GridMachine
{
	private List`1 m_rectList; // 0x10


	// RVA: 0x37d9620 VA: 0x7595df1620
	private static Boolean _HitTest(IGridRect rect0, IGridRect rect1) { }
	// RVA: 0x37d9b3c VA: 0x7595df1b3c
	public Boolean AddGridRect(IGridRect rect, Boolean force) { }
	// RVA: 0x37d9d38 VA: 0x7595df1d38
	public Boolean RemoveGridRect(IGridRect rect) { }
	// RVA: 0x37d9dcc VA: 0x7595df1dcc
	public Void ClearGridRect() { }
	// RVA: 0x37d9e3c VA: 0x7595df1e3c
	public Void ForEachGridRect(Action`1 action) { }
	// RVA: 0x37d9c48 VA: 0x7595df1c48
	public Boolean CheckIntersection(IGridRect rect, Action`1 action) { }
	// RVA: 0x37d9ee8 VA: 0x7595df1ee8
	public Boolean CheckIntersectionPairs(Action`2 action) { }
	// RVA: 0x37da03c VA: 0x7595df203c
	public Boolean CheckOutofRange(Int32 x, Int32 y, Int32 w, Int32 h, Action`1 action) { }
	// RVA: 0x37da46c VA: 0x7595df246c
	public Int32[,] GetOccupationMatrix(Int32 x, Int32 y, Int32 w, Int32 h) { }
	// RVA: 0x37da8b0 VA: 0x7595df28b0
	public Void .ctor() { }
}
```