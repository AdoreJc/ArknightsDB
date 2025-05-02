# CampaignBriefRotateViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String stageId`

- `String stageName`

- `String zoneName`

- `String remainTimeStr`

- `Sprite spriteZoneIcon`


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignBriefRotateViewModel : IHotfixable
{
	public String stageId; // 0x10
	public String stageName; // 0x18
	public String zoneName; // 0x20
	public String remainTimeStr; // 0x28
	public Sprite spriteZoneIcon; // 0x30
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isValid { get; }

	// RVA: 0x2dc4a5c VA: 0x75953dca5c
	public Boolean get_isValid() { }
	// RVA: 0x2dc508c VA: 0x75953dd08c
	public Void LoadData() { }
	// RVA: 0x2dc5350 VA: 0x75953dd350
	public Void .ctor() { }
}
```