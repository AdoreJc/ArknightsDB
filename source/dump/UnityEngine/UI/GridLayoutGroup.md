# GridLayoutGroup

**Namespace:** `UnityEngine.UI`


## Fields

- `Corner m_StartCorner`

- `Axis m_StartAxis`

- `Vector2 m_CellSize`

- `Vector2 m_Spacing`

- `Constraint m_Constraint`

- `Int32 m_ConstraintCount`


## Properties

- `Corner startCorner`

- `Axis startAxis`

- `Vector2 cellSize`

- `Vector2 spacing`

- `Constraint constraint`

- `Int32 constraintCount`


## Methods

- `Corner get_startCorner()`

- `Void set_startCorner(Corner)`

- `Axis get_startAxis()`

- `Void set_startAxis(Axis)`

- `Vector2 get_cellSize()`

- `Void set_cellSize(Vector2)`

- `Vector2 get_spacing()`

- `Void set_spacing(Vector2)`

- `Constraint get_constraint()`

- `Void set_constraint(Constraint)`

- `Int32 get_constraintCount()`

- `Void set_constraintCount(Int32)`

- `Void SetCellsAlongAxis(Int32)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class GridLayoutGroup : LayoutGroup
{
	protected Corner m_StartCorner; // 0x58
	protected Axis m_StartAxis; // 0x5c
	protected Vector2 m_CellSize; // 0x60
	protected Vector2 m_Spacing; // 0x68
	protected Constraint m_Constraint; // 0x70
	protected Int32 m_ConstraintCount; // 0x74

	public Corner startCorner { get; set; }
	public Axis startAxis { get; set; }
	public Vector2 cellSize { get; set; }
	public Vector2 spacing { get; set; }
	public Constraint constraint { get; set; }
	public Int32 constraintCount { get; set; }

	// RVA: 0x6a52f18 VA: 0x759906af18
	public Corner get_startCorner() { }
	// RVA: 0x6a52f20 VA: 0x759906af20
	public Void set_startCorner(Corner value) { }
	// RVA: 0x6a52f7c VA: 0x759906af7c
	public Axis get_startAxis() { }
	// RVA: 0x6a52f84 VA: 0x759906af84
	public Void set_startAxis(Axis value) { }
	// RVA: 0x6a52fe0 VA: 0x759906afe0
	public Vector2 get_cellSize() { }
	// RVA: 0x6a52fe8 VA: 0x759906afe8
	public Void set_cellSize(Vector2 value) { }
	// RVA: 0x6a5304c VA: 0x759906b04c
	public Vector2 get_spacing() { }
	// RVA: 0x6a53054 VA: 0x759906b054
	public Void set_spacing(Vector2 value) { }
	// RVA: 0x6a530b8 VA: 0x759906b0b8
	public Constraint get_constraint() { }
	// RVA: 0x6a530c0 VA: 0x759906b0c0
	public Void set_constraint(Constraint value) { }
	// RVA: 0x6a5311c VA: 0x759906b11c
	public Int32 get_constraintCount() { }
	// RVA: 0x6a53124 VA: 0x759906b124
	public Void set_constraintCount(Int32 value) { }
	// RVA: 0x6a53184 VA: 0x759906b184
	protected Void .ctor() { }
	// RVA: 0x6a5334c VA: 0x759906b34c
	public override Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x6a53964 VA: 0x759906b964
	public override Void CalculateLayoutInputVertical() { }
	// RVA: 0x6a53c34 VA: 0x759906bc34
	public override Void SetLayoutHorizontal() { }
	// RVA: 0x6a54214 VA: 0x759906c214
	public override Void SetLayoutVertical() { }
	// RVA: 0x6a53c3c VA: 0x759906bc3c
	private Void SetCellsAlongAxis(Int32 axis) { }
}
```