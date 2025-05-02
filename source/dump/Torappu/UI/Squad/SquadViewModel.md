# SquadViewModel

**Namespace:** `Torappu.UI.Squad`


## Fields

- `Int32 id`

- `String name`

- `Int32 <cachedMemberCount>k__BackingField`


## Properties

- `EvolvePhaseAndLevel maxEvolvePhaseAndLevel`

- `Int32 cachedMemberCount`


## Methods

- `EvolvePhaseAndLevel get_maxEvolvePhaseAndLevel()`

- `Int32 get_cachedMemberCount()`

- `Void set_cachedMemberCount(Int32)`

- `Int32 CountValidMembers()`

- `EvolvePhaseAndLevel _CalcEvolveMaxPhaseAndLevel()`

- `Void ApplySquadName(PlayerSquad)`

- `Void FillWithPlayerData(PlayerSquad)`

- `Void ShrinkMembers()`

- `Void UpdateMemberStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadViewModel : IHotfixable
{
	public Int32 id; // 0x10
	public String name; // 0x18
	public SquadItemStruct[] members; // 0x20
	private Int32 <cachedMemberCount>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_maxEvolvePhaseAndLevel; // 0x0
	private static DelegateBridge __Hotfix0_get_cachedMemberCount; // 0x8
	private static DelegateBridge __Hotfix0_set_cachedMemberCount; // 0x10
	private static DelegateBridge __Hotfix0_CountValidMembers; // 0x18
	private static DelegateBridge __Hotfix0__CalcEvolveMaxPhaseAndLevel; // 0x20
	private static DelegateBridge __Hotfix0_ApplySquadName; // 0x28
	private static DelegateBridge __Hotfix0_FillWithPlayerData; // 0x30
	private static DelegateBridge __Hotfix0_ShrinkMembers; // 0x38
	private static DelegateBridge __Hotfix0_UpdateMemberStatus; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public EvolvePhaseAndLevel maxEvolvePhaseAndLevel { get; }
	public Int32 cachedMemberCount { get; set; }

	// RVA: 0x23c2578 VA: 0x75949da578
	public EvolvePhaseAndLevel get_maxEvolvePhaseAndLevel() { }
	// RVA: 0x23c276c VA: 0x75949da76c
	public Int32 get_cachedMemberCount() { }
	// RVA: 0x23c27d4 VA: 0x75949da7d4
	private Void set_cachedMemberCount(Int32 value) { }
	// RVA: 0x23c2850 VA: 0x75949da850
	public Int32 CountValidMembers() { }
	// RVA: 0x23c25e0 VA: 0x75949da5e0
	private EvolvePhaseAndLevel _CalcEvolveMaxPhaseAndLevel() { }
	// RVA: 0x23c297c VA: 0x75949da97c
	public Void ApplySquadName(PlayerSquad playerSquad) { }
	// RVA: 0x23c2a08 VA: 0x75949daa08
	public Void FillWithPlayerData(PlayerSquad playerSquad) { }
	// RVA: 0x23c2cac VA: 0x75949dacac
	public Void ShrinkMembers() { }
	// RVA: 0x23c2e7c VA: 0x75949dae7c
	public Void UpdateMemberStatus() { }
	// RVA: 0x23c3190 VA: 0x75949db190
	public Void .ctor() { }
}
```