# AdvancedSelectorWithTagFilteredWithCreatedTime

**Namespace:** `Torappu.Battle`


## Fields

- `CompareType _compareWithOwnerCreatedTime`

- `Boolean _tagExcluded`

- `String _filterTag`

- `FP m_ownerCreatedTime`

- `UInt32 m_instanceUid`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithTagFilteredWithCreatedTime : AdvancedSelector
{
	private CompareType _compareWithOwnerCreatedTime; // 0xe8
	private Boolean _tagExcluded; // 0xec
	private String _filterTag; // 0xf0
	private FP m_ownerCreatedTime; // 0xf8
	private UInt32 m_instanceUid; // 0x100
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b9fca8 VA: 0x75941b7ca8
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1b9fd7c VA: 0x75941b7d7c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba0024 VA: 0x75941b8024
	public Void .ctor() { }
	// RVA: 0x1ba0094 VA: 0x75941b8094
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba009c VA: 0x75941b809c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```