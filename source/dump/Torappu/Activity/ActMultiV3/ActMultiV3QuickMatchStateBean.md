# ActMultiV3QuickMatchStateBean

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `TeamInst <cacheTeamInst>k__BackingField`

- `ActMultiV3QuickMatchProp m_prop`


## Properties

- `TeamInst cacheTeamInst`

- `ActMultiV3QuickMatchProp prop`


## Methods

- `TeamInst get_cacheTeamInst()`

- `Void set_cacheTeamInst(TeamInst)`

- `ActMultiV3QuickMatchProp get_prop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchStateBean : IStateBean, IHotfixable
{
	private TeamInst <cacheTeamInst>k__BackingField; // 0x10
	private ActMultiV3QuickMatchProp m_prop; // 0x18
	private static DelegateBridge __Hotfix0_get_cacheTeamInst; // 0x0
	private static DelegateBridge __Hotfix0_set_cacheTeamInst; // 0x8
	private static DelegateBridge __Hotfix0_get_prop; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public TeamInst cacheTeamInst { get; set; }
	public ActMultiV3QuickMatchProp prop { get; }

	// RVA: 0x312d6a4 VA: 0x75957456a4
	public TeamInst get_cacheTeamInst() { }
	// RVA: 0x312d70c VA: 0x759574570c
	public Void set_cacheTeamInst(TeamInst value) { }
	// RVA: 0x312d790 VA: 0x7595745790
	public ActMultiV3QuickMatchProp get_prop() { }
	// RVA: 0x312d7f8 VA: 0x75957457f8
	public Void .ctor() { }
}
```