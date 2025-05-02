# HandBookV2MapAlphaDotView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Single backgroudAlpha`

- `Color pointColor`

- `Color pointColor2`

- `Single length`

- `Vector3 initPoint`

- `Single maxLength`

- `HexagonDirection m_direction`


## Methods

- `Void Render(HexagonDirection)`

- `Color _GetColor(Int32, Color, Color, Color)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapAlphaDotView : MaskableGraphic, IHotfixable
{
	public Single backgroudAlpha; // 0xe0
	public Color pointColor; // 0xe4
	public Color pointColor2; // 0xf4
	public Single length; // 0x104
	public Vector3 initPoint; // 0x108
	public Single maxLength; // 0x114
	private HexagonDirection m_direction; // 0x118
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetColor; // 0x8
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ece990 VA: 0x75954e6990
	public Void Render(HexagonDirection direction) { }
	// RVA: 0x2ecea0c VA: 0x75954e6a0c
	private Color _GetColor(Int32 i, Color color1, Color color2, Color color3) { }
	// RVA: 0x2eceb84 VA: 0x75954e6b84
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2ed05e4 VA: 0x75954e85e4
	public Void .ctor() { }
	// RVA: 0x2ed0668 VA: 0x75954e8668
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```