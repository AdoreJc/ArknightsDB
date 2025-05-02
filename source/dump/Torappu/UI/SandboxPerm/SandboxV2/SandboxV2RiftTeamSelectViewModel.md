# SandboxV2RiftTeamSelectViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 teamLevel`

- `String noTeamName`

- `String noTeamBgId`

- `String noTeamDesc`

- `String noTeamBigIconId`

- `String m_selectedTeamId`


## Properties

- `String selectedTeamId`


## Methods

- `String get_selectedTeamId()`

- `Void LoadData(String)`

- `Void UpdateSelectTeam(String)`

- `Boolean IsTeamSame(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftTeamSelectViewModel : IHotfixable
{
	public ListDict`2 teamItemDict; // 0x10
	public Int32 teamLevel; // 0x18
	public String noTeamName; // 0x20
	public String noTeamBgId; // 0x28
	public String noTeamDesc; // 0x30
	public String noTeamBigIconId; // 0x38
	private String m_selectedTeamId; // 0x40
	private static DelegateBridge __Hotfix0_get_selectedTeamId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelectTeam; // 0x10
	private static DelegateBridge __Hotfix0_IsTeamSame; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String selectedTeamId { get; }

	// RVA: 0x25fb128 VA: 0x7594c13128
	public String get_selectedTeamId() { }
	// RVA: 0x25faae4 VA: 0x7594c12ae4
	public Void LoadData(String topicId) { }
	// RVA: 0x25fbad0 VA: 0x7594c13ad0
	public Void UpdateSelectTeam(String teamId) { }
	// RVA: 0x25fba10 VA: 0x7594c13a10
	public Boolean IsTeamSame(String teamId) { }
	// RVA: 0x2601cd8 VA: 0x7594c19cd8
	public Void .ctor() { }
}
```