# AdvancedSelectorWithOffsetFromTileBind

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _tagExcluded`

- `String _filterTag`

- `Boolean _excludeRootTile`

- `Boolean _ignoreMapLayer`


## Methods

- `Boolean <>xLuaBaseProxy_get_ignoreMapLayer()`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithOffsetFromTileBind : AdvancedSelector
{
	private Boolean _tagExcluded; // 0xe8
	private String _filterTag; // 0xf0
	private Boolean _excludeRootTile; // 0xf8
	private Boolean _ignoreMapLayer; // 0xf9
	private static DelegateBridge __Hotfix0_get_ignoreMapLayer; // 0x0
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override Boolean ignoreMapLayer { get; }

	// RVA: 0x1b9d888 VA: 0x75941b5888
	protected override Boolean get_ignoreMapLayer() { }
	// RVA: 0x1b9d8f0 VA: 0x75941b58f0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1b9df34 VA: 0x75941b5f34
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9e084 VA: 0x75941b6084
	public Void .ctor() { }
	// RVA: 0x1b9e0fc VA: 0x75941b60fc
	private Boolean <>xLuaBaseProxy_get_ignoreMapLayer() { }
	// RVA: 0x1b9e104 VA: 0x75941b6104
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1b9e10c VA: 0x75941b610c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```