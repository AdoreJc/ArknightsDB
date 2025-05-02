# SandboxV2RiftEntryViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String riftId`

- `Boolean isRiftReservated`

- `Boolean isRandomRift`

- `Boolean isPreyRift`

- `Boolean useDifficulty`

- `String mainTargetTitle`

- `String mainTargetDesc`

- `Int32 mainTargetDayCount`

- `RiftParam climateParam`

- `RiftParam terrainParam`

- `RiftParam enemyParam`

- `String riftGlobalEffectDesc`

- `String subTargetDesc`

- `Int32 randomRiftDifficultyLevel`

- `String riftTeamId`

- `String riftTeamIconId`

- `String riftTeamName`

- `Int32 riftTeamLevel`

- `Int32 remainDayCount`

- `Boolean canStartRift`


## Methods

- `Void LoadData(String)`

- `Void RefreshData(String)`

- `Void _ProcessParamData(SandboxV2RiftParamData, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftEntryViewModel : IHotfixable
{
	private const Int32 DEFAULT_DISPLAY_ITEM_COUNT; // 0x0
	public String riftId; // 0x10
	public Boolean isRiftReservated; // 0x18
	public Boolean isRandomRift; // 0x19
	public Boolean isPreyRift; // 0x1a
	public Boolean useDifficulty; // 0x1b
	public String mainTargetTitle; // 0x20
	public String mainTargetDesc; // 0x28
	public Int32 mainTargetDayCount; // 0x30
	public RiftParam climateParam; // 0x38
	public RiftParam terrainParam; // 0x40
	public RiftParam enemyParam; // 0x48
	public String riftGlobalEffectDesc; // 0x50
	public String subTargetDesc; // 0x58
	public List`1 rewards; // 0x60
	public List`1 difficultyDescs; // 0x68
	public Int32 randomRiftDifficultyLevel; // 0x70
	public String riftTeamId; // 0x78
	public String riftTeamIconId; // 0x80
	public String riftTeamName; // 0x88
	public Int32 riftTeamLevel; // 0x90
	public Int32 remainDayCount; // 0x94
	public Boolean canStartRift; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0__ProcessParamData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25f86cc VA: 0x7594c106cc
	public Void LoadData(String topicId) { }
	// RVA: 0x25f8f84 VA: 0x7594c10f84
	public Void RefreshData(String topicId) { }
	// RVA: 0x26017bc VA: 0x7594c197bc
	private Void _ProcessParamData(SandboxV2RiftParamData gameData, ref RiftParam param) { }
	// RVA: 0x2601960 VA: 0x7594c19960
	public Void .ctor() { }
}
```