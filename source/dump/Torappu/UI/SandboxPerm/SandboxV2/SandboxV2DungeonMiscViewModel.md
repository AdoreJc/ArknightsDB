# SandboxV2DungeonMiscViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String topicName`

- `Single daySeasonAngle`

- `Int64 lastLoadArchiveCoolDownTime`

- `Boolean haveArchive`

- `String textSurviveDay`

- `Int32 tempRacerTipLimit`

- `String tempRacerBagName`

- `Boolean showTempRacerTip`

- `SandboxV2DungeonMiscExpeditionViewModel expeditionViewModel`

- `SandboxV2DungeonMiscLogisticsEffectViewModel logisticsEffectViewModel`

- `SandboxV2DungeonMiscEventEffectViewModel eventEffectViewModel`

- `SandboxV2DungeonMaterialViewModel materialViewModel`

- `SandboxV2DungeonMiscRiftViewModel riftViewModel`

- `SandboxV2DungeonMiscChallengeViewModel challengeViewModel`


## Methods

- `Void UpdateData(UpdateParam)`

- `Void _LoadRacingData(UpdateParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMiscViewModel : IHotfixable
{
	public String topicName; // 0x10
	public Single daySeasonAngle; // 0x18
	public Int64 lastLoadArchiveCoolDownTime; // 0x20
	public Boolean haveArchive; // 0x28
	public String textSurviveDay; // 0x30
	public Int32 tempRacerTipLimit; // 0x38
	public String tempRacerBagName; // 0x40
	public Boolean showTempRacerTip; // 0x48
	public SandboxV2DungeonMiscExpeditionViewModel expeditionViewModel; // 0x50
	public SandboxV2DungeonMiscLogisticsEffectViewModel logisticsEffectViewModel; // 0x58
	public SandboxV2DungeonMiscEventEffectViewModel eventEffectViewModel; // 0x60
	public SandboxV2DungeonMaterialViewModel materialViewModel; // 0x68
	public SandboxV2DungeonMiscRiftViewModel riftViewModel; // 0x70
	public SandboxV2DungeonMiscChallengeViewModel challengeViewModel; // 0x78
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0__LoadRacingData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25b4998 VA: 0x7594bcc998
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25b4c34 VA: 0x7594bccc34
	private Void _LoadRacingData(UpdateParam updateParam) { }
	// RVA: 0x25b4e80 VA: 0x7594bcce80
	public Void .ctor() { }
}
```