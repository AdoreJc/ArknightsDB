# CampaignStateViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String id`

- `Int32 curMaxKillCnt`

- `StageViewModel stageCommonViewModel`


## Methods

- `Void SetPlayerData(Stage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignStateViewModel : IHotfixable
{
	public String id; // 0x10
	public Int32 curMaxKillCnt; // 0x18
	public StageViewModel stageCommonViewModel; // 0x20
	public List`1 breakLadders; // 0x28
	public List`1 displayRewards; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetPlayerData; // 0x8


	// RVA: 0x2dde844 VA: 0x75953f6844
	public Void .ctor(CampaignData campData, CampaignStageType stageType) { }
	// RVA: 0x2ddf038 VA: 0x75953f7038
	public Void SetPlayerData(Stage instance) { }
}
```