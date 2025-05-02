# BounceEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `PhysicsMaterial2D m_physicsMaterial`


## Methods

- `Boolean <>xLuaBaseProxy_get_disableUIUnitHud()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Boolean <>xLuaBaseProxy_BeginPull(BObject, Vector2, Single)`

- `Void <>xLuaBaseProxy_EndPull(BObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BounceEnemy : Enemy
{
	protected PhysicsMaterial2D m_physicsMaterial; // 0x4b8
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x10
	private static DelegateBridge __Hotfix0_BeginPull; // 0x18
	private static DelegateBridge __Hotfix0_EndPull; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean disableUIUnitHud { get; }

	// RVA: 0x1bdfe38 VA: 0x75941f7e38
	public override Boolean get_disableUIUnitHud() { }
	// RVA: 0x1bdfea0 VA: 0x75941f7ea0
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1bdff50 VA: 0x75941f7f50
	public override Void OnRecycle() { }
	// RVA: 0x1be0034 VA: 0x75941f8034
	public override Boolean BeginPull(BObject source, Vector2 direction, Single force) { }
	// RVA: 0x1be0114 VA: 0x75941f8114
	public override Void EndPull(BObject source) { }
	// RVA: 0x1be01b8 VA: 0x75941f81b8
	public Void .ctor() { }
	// RVA: 0x1be024c VA: 0x75941f824c
	private Boolean <>xLuaBaseProxy_get_disableUIUnitHud() { }
	// RVA: 0x1be0254 VA: 0x75941f8254
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1be025c VA: 0x75941f825c
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x1be0264 VA: 0x75941f8264
	private Boolean <>xLuaBaseProxy_BeginPull(BObject P0, Vector2 P1, Single P2) { }
	// RVA: 0x1be026c VA: 0x75941f826c
	private Void <>xLuaBaseProxy_EndPull(BObject P0) { }
}
```