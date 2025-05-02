# UIRadarMap

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _vertexCount`

- `Int32 _startDegree`

- `Boolean _isClockwise`

- `RectTransform m_rect`


## Properties

- `RectTransform rect`


## Methods

- `RectTransform get_rect()`

- `Void Render(Int32, IList`1, Boolean)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIRadarMap : MaskableGraphic, IHotfixable
{
	private Int32 _vertexCount; // 0xe0
	private Single[] _edgeLength; // 0xe8
	private Int32 _startDegree; // 0xf0
	private Boolean _isClockwise; // 0xf4
	private RectTransform m_rect; // 0xf8
	private static DelegateBridge __Hotfix0_get_rect; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private RectTransform rect { get; }

	// RVA: 0x21ef7a0 VA: 0x75948077a0
	private RectTransform get_rect() { }
	// RVA: 0x21ef878 VA: 0x7594807878
	public Void Render(Int32 vertexCount, IList`1 length, Boolean isClockwise) { }
	// RVA: 0x21ef994 VA: 0x7594807994
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x21f0278 VA: 0x7594808278
	public Void .ctor() { }
	// RVA: 0x21f02f0 VA: 0x75948082f0
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```