# CampaignWorldZoneViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String id`

- `String name`

- `Boolean isActive`

- `Boolean isUnlocked`

- `Boolean hasStage`

- `Boolean hasUnconfirmedReward`

- `Boolean isRotate`

- `Int64 rotateEndTs`


## Methods

- `Void LoadData(String, CampaignWorldViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldZoneViewModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public Boolean isActive; // 0x20
	public Boolean isUnlocked; // 0x21
	public Boolean hasStage; // 0x22
	public Boolean hasUnconfirmedReward; // 0x23
	public Boolean isRotate; // 0x24
	public Int64 rotateEndTs; // 0x28
	public List`1 stageModels; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dd8e0c VA: 0x75953f0e0c
	public Void LoadData(String zoneId, CampaignWorldViewModel context) { }
	// RVA: 0x2dd8d48 VA: 0x75953f0d48
	public Void .ctor() { }
}
```