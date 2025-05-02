# CertainSideSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _selectSideType`

- `Boolean _buffKeyExcluded`

- `Boolean _filterBuffSource`


## Methods

- `Void _CheckBuff(List`1, String)`

- `Boolean <>xLuaBaseProxy_VerifyTarget(List`1)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CertainSideSelector : AdvancedSelector
{
	private SideType _selectSideType; // 0xe8
	private Boolean _buffKeyExcluded; // 0xec
	private List`1 _buffs; // 0xf0
	private Boolean _filterBuffSource; // 0xf8
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x0
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x10
	private static DelegateBridge __Hotfix0__CheckBuff; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1bbe840 VA: 0x75941d6840
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bbeb28 VA: 0x75941d6b28
	public override Boolean VerifyTarget(List`1 candidates) { }
	// RVA: 0x1bbec60 VA: 0x75941d6c60
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbed6c VA: 0x75941d6d6c
	private Void _CheckBuff(List`1 candidates, String buffKey) { }
	// RVA: 0x1bbeef0 VA: 0x75941d6ef0
	public Void .ctor() { }
	// RVA: 0x1bbef68 VA: 0x75941d6f68
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1bbef6c VA: 0x75941d6f6c
	private Boolean <>xLuaBaseProxy_VerifyTarget(List`1 P0) { }
	// RVA: 0x1bbef70 VA: 0x75941d6f70
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```