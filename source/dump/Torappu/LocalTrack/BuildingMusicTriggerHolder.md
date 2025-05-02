# BuildingMusicTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Boolean _CheckMusicUnlocked(String, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class BuildingMusicTriggerHolder : PlayerTrackTriggerHolder`1
{
	private static DelegateBridge __Hotfix0_CreatePlayerDataPathList; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfToTrigger; // 0x8
	private static DelegateBridge __Hotfix0__CheckMusicUnlocked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f16a88 VA: 0x759652ea88
	protected override IList`1 CreatePlayerDataPathList() { }
	// RVA: 0x3f16c98 VA: 0x759652ec98
	protected override Boolean CheckIfToTrigger(BuildingMusicTrigger trigger, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x3f16dac VA: 0x759652edac
	private Boolean _CheckMusicUnlocked(String bgmId, PlayerDataModel data) { }
	// RVA: 0x3f16e98 VA: 0x759652ee98
	public Void .ctor() { }
}
```