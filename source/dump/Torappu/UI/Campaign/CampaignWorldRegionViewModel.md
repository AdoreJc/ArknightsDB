# CampaignWorldRegionViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String id`

- `Boolean isUnknown`

- `Boolean isRotate`

- `Boolean isFirstTimeDetected`

- `Boolean isShowFog`


## Methods

- `Void LoadData(String, CampaignWorldViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldRegionViewModel : IHotfixable
{
	public String id; // 0x10
	public Boolean isUnknown; // 0x18
	public Boolean isRotate; // 0x19
	public Boolean isFirstTimeDetected; // 0x1a
	public Boolean isShowFog; // 0x1b
	public List`1 zoneModels; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dd9220 VA: 0x75953f1220
	public Void LoadData(String regionId, CampaignWorldViewModel context) { }
	// RVA: 0x2dd915c VA: 0x75953f115c
	public Void .ctor() { }
}
```