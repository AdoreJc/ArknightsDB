# RL02OuterBuffCurve

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `PolarPoint _startPos`

- `PolarPoint _endPos`

- `Int32 _width`


## Methods

- `Void SetPosition(PolarPoint, PolarPoint)`

- `Void _DrawArc(VertexHelper, PolarPoint, PolarPoint)`

- `Void _DrawLine(VertexHelper, PolarPoint, PolarPoint)`

- `Void Update()`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_SetClipRect(Rect, Boolean)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffCurve : Image, IHotfixable
{
	private PolarPoint _startPos; // 0x188
	private PolarPoint _endPos; // 0x190
	private Int32 _width; // 0x198
	private UIVertex[] m_vertexArray; // 0x1a0
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x0
	private static DelegateBridge __Hotfix0_SetPosition; // 0x8
	private static DelegateBridge __Hotfix0_SetClipRect; // 0x10
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x18
	private static DelegateBridge __Hotfix0__DrawArc; // 0x20
	private static DelegateBridge __Hotfix0__DrawLine; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x26be3e8 VA: 0x7594cd63e8
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x26be44c VA: 0x7594cd644c
	public Void SetPosition(PolarPoint startPos, PolarPoint endPos) { }
	// RVA: 0x26be550 VA: 0x7594cd6550
	public override Void SetClipRect(Rect clipRect, Boolean validRect) { }
	// RVA: 0x26be628 VA: 0x7594cd6628
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x26be788 VA: 0x7594cd6788
	private Void _DrawArc(VertexHelper vh, PolarPoint startPos, PolarPoint endPos) { }
	// RVA: 0x26bf05c VA: 0x7594cd705c
	private Void _DrawLine(VertexHelper vh, PolarPoint startPos, PolarPoint endPos) { }
	// RVA: 0x26c0168 VA: 0x7594cd8168
	public Void Update() { }
	// RVA: 0x26c01cc VA: 0x7594cd81cc
	public Void .ctor() { }
	// RVA: 0x26c029c VA: 0x7594cd829c
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x26c02a4 VA: 0x7594cd82a4
	private Void <>xLuaBaseProxy_SetClipRect(Rect P0, Boolean P1) { }
	// RVA: 0x26c02b0 VA: 0x7594cd82b0
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```