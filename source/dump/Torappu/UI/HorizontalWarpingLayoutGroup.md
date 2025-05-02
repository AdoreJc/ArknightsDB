# HorizontalWarpingLayoutGroup

**Namespace:** `Torappu.UI`


## Fields

- `Single _fixedWidth`

- `Vector2 _spacing`

- `Vector2 m_contentSizeMeta`


## Methods

- `Vector2 _GetTrueOffsetOfChild(ChildMeta)`

- `Vector2 _GetTrueOffsetOfRow(RowMeta)`

- `Void <>xLuaBaseProxy_CalculateLayoutInputHorizontal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class HorizontalWarpingLayoutGroup : LayoutGroup, IHotfixable
{
	private Single _fixedWidth; // 0x58
	private Vector2 _spacing; // 0x5c
	private Vector2 m_contentSizeMeta; // 0x64
	private readonly List`1 m_rowMetas; // 0x70
	private readonly Dictionary`2 m_childMetas; // 0x78
	private static DelegateBridge __Hotfix0_CalculateLayoutInputHorizontal; // 0x0
	private static DelegateBridge __Hotfix0_CalculateLayoutInputVertical; // 0x8
	private static DelegateBridge __Hotfix0_SetLayoutHorizontal; // 0x10
	private static DelegateBridge __Hotfix0_SetLayoutVertical; // 0x18
	private static DelegateBridge __Hotfix0__GetTrueOffsetOfChild; // 0x20
	private static DelegateBridge __Hotfix0__GetTrueOffsetOfRow; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x220b66c VA: 0x759482366c
	public override Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x220b864 VA: 0x7594823864
	public override Void CalculateLayoutInputVertical() { }
	// RVA: 0x220bc94 VA: 0x7594823c94
	public override Void SetLayoutHorizontal() { }
	// RVA: 0x220be24 VA: 0x7594823e24
	public override Void SetLayoutVertical() { }
	// RVA: 0x220bffc VA: 0x7594823ffc
	private Vector2 _GetTrueOffsetOfChild(ChildMeta meta) { }
	// RVA: 0x220c17c VA: 0x759482417c
	private Vector2 _GetTrueOffsetOfRow(RowMeta meta) { }
	// RVA: 0x220c640 VA: 0x7594824640
	public Void .ctor() { }
	// RVA: 0x220c754 VA: 0x7594824754
	private Void <>xLuaBaseProxy_CalculateLayoutInputHorizontal() { }
}
```