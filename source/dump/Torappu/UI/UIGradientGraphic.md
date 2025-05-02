# UIGradientGraphic

**Namespace:** `Torappu.UI`


## Fields

- `DrawDirection _tapeDirection`

- `Vector2 m_rectSize`


## Methods

- `Vector2 _GetPost(Single, Single, Single, Single)`

- `Void DrawVerticalColoredTape(VertexHelper)`

- `Void DrawHorizontalColoredTape(VertexHelper)`

- `UIVertex GetUIVertex(Vector2, Color)`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGradientGraphic : MaskableGraphic, IHotfixable
{
	private DrawDirection _tapeDirection; // 0xe0
	private List`1 _colorPoints; // 0xe8
	private Vector2 m_rectSize; // 0xf0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x8
	private static DelegateBridge __Hotfix0__GetPost; // 0x10
	private static DelegateBridge __Hotfix0_DrawVerticalColoredTape; // 0x18
	private static DelegateBridge __Hotfix0_DrawHorizontalColoredTape; // 0x20
	private static DelegateBridge __Hotfix0_GetUIVertex; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21ec068 VA: 0x7594804068
	protected override Void OnEnable() { }
	// RVA: 0x21ec0d4 VA: 0x75948040d4
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x21eca10 VA: 0x7594804a10
	private Vector2 _GetPost(Single x, Single y, Single xP, Single yP) { }
	// RVA: 0x21ec1ac VA: 0x75948041ac
	private Void DrawVerticalColoredTape(VertexHelper vh) { }
	// RVA: 0x21ec5e0 VA: 0x75948045e0
	private Void DrawHorizontalColoredTape(VertexHelper vh) { }
	// RVA: 0x21ecabc VA: 0x7594804abc
	public UIVertex GetUIVertex(Vector2 point, Color color0) { }
	// RVA: 0x21ece98 VA: 0x7594804e98
	public Void .ctor() { }
	// RVA: 0x21ed0a8 VA: 0x75948050a8
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x21ed0b0 VA: 0x75948050b0
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```