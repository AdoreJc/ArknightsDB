# UILineRenderer

**Namespace:** `Torappu.UI`


## Fields

- `Single thickness`


## Methods

- `Void _CreateBottomAndTopPoints(Vector3, Single, Vector3, Single, VertexHelper)`

- `Single _LookRotationV2(Vector2)`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILineRenderer : Image, IHotfixable
{
	public Vector2[] points; // 0x188
	public Single thickness; // 0x190
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x0
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x8
	private static DelegateBridge __Hotfix0__CreateBottomAndTopPoints; // 0x10
	private static DelegateBridge __Hotfix0__LookRotationV2; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x224a414 VA: 0x7594862414
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x224a478 VA: 0x7594862478
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x224a90c VA: 0x759486290c
	private Void _CreateBottomAndTopPoints(Vector3 p, Single progress, Vector3 direction, Single thickness, VertexHelper vh) { }
	// RVA: 0x224aea4 VA: 0x7594862ea4
	private Single _LookRotationV2(Vector2 direction) { }
	// RVA: 0x224af3c VA: 0x7594862f3c
	public Void .ctor() { }
	// RVA: 0x224afd8 VA: 0x7594862fd8
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x224afe0 VA: 0x7594862fe0
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```