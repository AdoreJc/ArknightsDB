# CampaignWorldStageViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String id`

- `Boolean isUnlocked`

- `Boolean isClosed`

- `CampaignStageType stageType`

- `Boolean isComplete`

- `Boolean hasUnconfirmedReward`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldStageViewModel : IHotfixable
{
	public String id; // 0x10
	public Boolean isUnlocked; // 0x18
	public Boolean isClosed; // 0x19
	public CampaignStageType stageType; // 0x1c
	public Boolean isComplete; // 0x20
	public Boolean hasUnconfirmedReward; // 0x21
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dd8b84 VA: 0x75953f0b84
	public Void LoadData(String stageId) { }
	// RVA: 0x2dd8b14 VA: 0x75953f0b14
	public Void .ctor() { }
}
```