# UISlicedCircleBar

**Namespace:** `Torappu.UI`


## Fields

- `Single _startAngle`

- `Single _angleSpan`

- `Single m_radius`

- `Boolean m_antiClockwise`

- `Single m_borderUV`


## Properties

- `Single startAngle`

- `Single angleSpan`


## Methods

- `Void set_startAngle(Single)`

- `Void set_angleSpan(Single)`

- `Void _AddVertex(VertexHelper, Vector2, Vector2, ref)`

- `Vector2 _GetVertexPos(Single, Single)`

- `Void _GetRadialVertexUV(Int32, Single, out, out)`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISlicedCircleBar : Image, IHotfixable
{
	private Single _startAngle; // 0x188
	private Single _angleSpan; // 0x18c
	private Single m_radius; // 0x190
	private Boolean m_antiClockwise; // 0x194
	private Single m_borderUV; // 0x198
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x0
	private static DelegateBridge __Hotfix0_set_startAngle; // 0x8
	private static DelegateBridge __Hotfix0_set_angleSpan; // 0x10
	private static DelegateBridge __Hotfix0__AddVertex; // 0x18
	private static DelegateBridge __Hotfix0__GetVertexPos; // 0x20
	private static DelegateBridge __Hotfix0__GetRadialVertexUV; // 0x28
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean packIntoRuntimeAtlas { get; }
	public Single startAngle { set; }
	public Single angleSpan { set; }

	// RVA: 0x2254d60 VA: 0x759486cd60
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x2254dc4 VA: 0x759486cdc4
	public Void set_startAngle(Single value) { }
	// RVA: 0x2254e50 VA: 0x759486ce50
	public Void set_angleSpan(Single value) { }
	// RVA: 0x2254edc VA: 0x759486cedc
	private Void _AddVertex(VertexHelper vh, Vector2 pos, Vector2 uv, ref Int32 vertexIndex) { }
	// RVA: 0x2255334 VA: 0x759486d334
	private Vector2 _GetVertexPos(Single angleOffset, Single radius) { }
	// RVA: 0x22553e8 VA: 0x759486d3e8
	private Void _GetRadialVertexUV(Int32 section, Single angle, out Single radius, out Vector2 uv) { }
	// RVA: 0x22555e8 VA: 0x759486d5e8
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x225701c VA: 0x759486f01c
	public Void .ctor() { }
	// RVA: 0x22570b0 VA: 0x759486f0b0
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x22570b8 VA: 0x759486f0b8
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```