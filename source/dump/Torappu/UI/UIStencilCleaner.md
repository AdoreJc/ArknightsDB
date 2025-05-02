# UIStencilCleaner

**Namespace:** `Torappu.UI`


## Fields

- `Material m_clearMat`


## Methods

- `Void _AddClearMaterial()`

- `Void _RemoveClearMaterial()`

- `Void RegisterNeedClean(INeedClean)`

- `Void UnregisterNeedClean(INeedClean)`

- `Material <>xLuaBaseProxy_get_materialForRendering()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Boolean <>xLuaBaseProxy_get_raycastTarget()`

- `Void <>xLuaBaseProxy_set_raycastTarget(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIStencilCleaner : UIStencilMaskable
{
	private HashSet`1 m_needCleans; // 0xc0
	private Material m_clearMat; // 0xc8
	private static DelegateBridge __Hotfix0_get_materialForRendering; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnDisable; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_get_raycastTarget; // 0x20
	private static DelegateBridge __Hotfix0_set_raycastTarget; // 0x28
	private static DelegateBridge __Hotfix0__AddClearMaterial; // 0x30
	private static DelegateBridge __Hotfix0__RemoveClearMaterial; // 0x38
	private static DelegateBridge __Hotfix0_RegisterNeedClean; // 0x40
	private static DelegateBridge __Hotfix0_UnregisterNeedClean; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override Material materialForRendering { get; }
	public override Boolean raycastTarget { get; set; }

	// RVA: 0x2198a70 VA: 0x75947b0a70
	public override Material get_materialForRendering() { }
	// RVA: 0x2198cf4 VA: 0x75947b0cf4
	protected override Void OnEnable() { }
	// RVA: 0x2198d68 VA: 0x75947b0d68
	protected override Void OnDisable() { }
	// RVA: 0x2198f3c VA: 0x75947b0f3c
	protected override Void OnDestroy() { }
	// RVA: 0x2198fb0 VA: 0x75947b0fb0
	public override Boolean get_raycastTarget() { }
	// RVA: 0x2199014 VA: 0x75947b1014
	public override Void set_raycastTarget(Boolean value) { }
	// RVA: 0x2198ae0 VA: 0x75947b0ae0
	private Void _AddClearMaterial() { }
	// RVA: 0x2198ddc VA: 0x75947b0ddc
	private Void _RemoveClearMaterial() { }
	// RVA: 0x219908c VA: 0x75947b108c
	public Void RegisterNeedClean(INeedClean needClean) { }
	// RVA: 0x2199180 VA: 0x75947b1180
	public Void UnregisterNeedClean(INeedClean needClean) { }
	// RVA: 0x2199274 VA: 0x75947b1274
	public Void .ctor() { }
	// RVA: 0x2199338 VA: 0x75947b1338
	private Material <>xLuaBaseProxy_get_materialForRendering() { }
	// RVA: 0x2199340 VA: 0x75947b1340
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x2199348 VA: 0x75947b1348
	private Void <>xLuaBaseProxy_OnDisable() { }
	// RVA: 0x2199350 VA: 0x75947b1350
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x2199358 VA: 0x75947b1358
	private Boolean <>xLuaBaseProxy_get_raycastTarget() { }
	// RVA: 0x2199360 VA: 0x75947b1360
	private Void <>xLuaBaseProxy_set_raycastTarget(Boolean P0) { }
}
```