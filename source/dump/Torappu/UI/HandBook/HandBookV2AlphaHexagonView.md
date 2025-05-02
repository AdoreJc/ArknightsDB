# HandBookV2AlphaHexagonView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Color pointColor`

- `Single backgroudAlpha`

- `Single _length`

- `Vector3 _initPoint`

- `Single _maxLength`


## Methods

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2AlphaHexagonView : MaskableGraphic, IHotfixable
{
	public Color pointColor; // 0xe0
	public Single backgroudAlpha; // 0xf0
	private Single _length; // 0xf4
	private Vector3 _initPoint; // 0xf8
	private Single _maxLength; // 0x104
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ecd294 VA: 0x75954e5294
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2ece8fc VA: 0x75954e68fc
	public Void .ctor() { }
	// RVA: 0x2ece988 VA: 0x75954e6988
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```