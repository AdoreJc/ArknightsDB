# UIBuildingSpineAdapter

**Namespace:** `Torappu.UI`


## Fields

- `BuildingSpineInput m_cachedInput`


## Methods

- `Void UpdateParam(BuildingSpineInput)`

- `TRS <>xLuaBaseProxy_GetTransformParam()`

- `Boolean <>xLuaBaseProxy_EnableReverseMode(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBuildingSpineAdapter : Adapter, IHotfixable
{
	private BuildingSpineInput m_cachedInput; // 0x48
	private static DelegateBridge __Hotfix0_UpdateParam; // 0x0
	private static DelegateBridge __Hotfix0_GetSpineID; // 0x8
	private static DelegateBridge __Hotfix0_GetTransformParam; // 0x10
	private static DelegateBridge __Hotfix0_GetAnimParam; // 0x18
	private static DelegateBridge __Hotfix0_EnableReverseMode; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x21f09f0 VA: 0x75948089f0
	public Void UpdateParam(BuildingSpineInput input) { }
	// RVA: 0x21f0aa8 VA: 0x7594808aa8
	public override SpineID GetSpineID() { }
	// RVA: 0x21f0b30 VA: 0x7594808b30
	public override TRS GetTransformParam() { }
	// RVA: 0x21f0be4 VA: 0x7594808be4
	public override SpineAnimParam GetAnimParam() { }
	// RVA: 0x21f0cf4 VA: 0x7594808cf4
	public override Boolean EnableReverseMode(String animName) { }
	// RVA: 0x21f0da4 VA: 0x7594808da4
	public Void .ctor() { }
	// RVA: 0x21f0e20 VA: 0x7594808e20
	private TRS <>xLuaBaseProxy_GetTransformParam() { }
	// RVA: 0x21f0e34 VA: 0x7594808e34
	private Boolean <>xLuaBaseProxy_EnableReverseMode(String P0) { }
}
```