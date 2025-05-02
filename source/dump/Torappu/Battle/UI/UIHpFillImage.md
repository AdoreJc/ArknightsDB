# UIHpFillImage

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single m_splitValue`


## Properties

- `Single splitValue`


## Methods

- `Single get_splitValue()`

- `Void set_splitValue(Single)`

- `Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIHpFillImage : Image, IHotfixable
{
	private Single m_splitValue; // 0x188
	private static DelegateBridge __Hotfix0_get_splitValue; // 0x0
	private static DelegateBridge __Hotfix0_set_splitValue; // 0x8
	private static DelegateBridge __Hotfix0_get_packIntoRuntimeAtlas; // 0x10
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single splitValue { get; set; }
	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x207f9e8 VA: 0x75946979e8
	public Single get_splitValue() { }
	// RVA: 0x207e920 VA: 0x7594696920
	public Void set_splitValue(Single value) { }
	// RVA: 0x207fa50 VA: 0x7594697a50
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x207fab4 VA: 0x7594697ab4
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x207fbf0 VA: 0x7594697bf0
	public Void .ctor() { }
	// RVA: 0x207fc84 VA: 0x7594697c84
	private Boolean <>xLuaBaseProxy_get_packIntoRuntimeAtlas() { }
	// RVA: 0x207fc8c VA: 0x7594697c8c
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```