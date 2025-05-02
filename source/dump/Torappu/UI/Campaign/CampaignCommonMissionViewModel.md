# CampaignCommonMissionViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String missionId`

- `String description`

- `Int32 value`

- `Int32 target`

- `Int32 breakFeeAdd`

- `Boolean isUnlocked`

- `String unlockText`

- `Boolean isFullfilled`

- `Boolean isFinished`


## Methods

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignCommonMissionViewModel : IHotfixable
{
	private const Int32 NORMAL_CAMPAIGN_PARAM_INDEX; // 0x0
	private const Int32 SMALL_SCALE_CAMPAIGN_PARAM_INDEX; // 0x0
	public String missionId; // 0x10
	public String description; // 0x18
	public Int32 value; // 0x20
	public Int32 target; // 0x24
	public Int32 breakFeeAdd; // 0x28
	public Boolean isUnlocked; // 0x2c
	public String unlockText; // 0x30
	public Boolean isFullfilled; // 0x38
	public Boolean isFinished; // 0x39
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dcfa58 VA: 0x75953e7a58
	public Void LoadData(String missionId, String rotateStageId) { }
	// RVA: 0x2dcff98 VA: 0x75953e7f98
	public Void .ctor() { }
}
```