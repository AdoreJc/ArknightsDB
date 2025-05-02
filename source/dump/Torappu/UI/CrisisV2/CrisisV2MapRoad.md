# CrisisV2MapRoad

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Single _segmentPerUnit`

- `Texture2D _texture`

- `Single m_lineWidth`


## Methods

- `Void ClearRoadData()`

- `Void SetRoadData(Vector2, Vector2, List`1, Single)`

- `Single _GetRadianOfVec(Vector2)`

- `Int32 _DrawLine(VertexHelper, Vector2, Vector2, Int32)`

- `Int32 _DrawArc(VertexHelper, ArcData, Int32)`

- `Texture <>xLuaBaseProxy_get_mainTexture()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoad : MaskableGraphic, IHotfixable
{
	private Single _segmentPerUnit; // 0xe0
	private Texture2D _texture; // 0xe8
	private static readonly Vector2 s_innerUV; // 0x0
	private static readonly Vector2 s_outerUV; // 0x8
	private List`1 m_linePosList; // 0xf0
	private List`1 m_arcList; // 0xf8
	private Single m_lineWidth; // 0x100
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x10
	private static DelegateBridge __Hotfix0_ClearRoadData; // 0x18
	private static DelegateBridge __Hotfix0_SetRoadData; // 0x20
	private static DelegateBridge __Hotfix0__GetRadianOfVec; // 0x28
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x30
	private static DelegateBridge __Hotfix0__DrawLine; // 0x38
	private static DelegateBridge __Hotfix0__DrawArc; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Texture mainTexture { get; }

	// RVA: 0x2c07d00 VA: 0x759521fd00
	public override Texture get_mainTexture() { }
	// RVA: 0x2c07de8 VA: 0x759521fde8
	public Void ClearRoadData() { }
	// RVA: 0x2c07eb0 VA: 0x759521feb0
	public Void SetRoadData(Vector2 srcPos, Vector2 dstPos, List`1 cornerPosList, Single width) { }
	// RVA: 0x2c08490 VA: 0x7595220490
	public Single _GetRadianOfVec(Vector2 vec) { }
	// RVA: 0x2c08700 VA: 0x7595220700
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2c08900 VA: 0x7595220900
	private Int32 _DrawLine(VertexHelper vh, Vector2 p1, Vector2 p2, Int32 vertIndex) { }
	// RVA: 0x2c095e0 VA: 0x75952215e0
	private Int32 _DrawArc(VertexHelper vh, ArcData arcData, Int32 vertIndex) { }
	// RVA: 0x2c09df8 VA: 0x7595221df8
	public Void .ctor() { }
	// RVA: 0x2c09f24 VA: 0x7595221f24
	private static Void .cctor() { }
	// RVA: 0x2c09f88 VA: 0x7595221f88
	private Texture <>xLuaBaseProxy_get_mainTexture() { }
	// RVA: 0x2c09fd8 VA: 0x7595221fd8
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```