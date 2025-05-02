# CampaignPermanentMissionViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String stageId`

- `String code`

- `String name`

- `Int32 value`

- `Int32 target`

- `Int32 remainBreakFeeAdd`

- `Int32 totalBreakFeeAdd`

- `Boolean isUnlocked`

- `String unlockText`

- `Boolean isFinished`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignPermanentMissionViewModel : IHotfixable
{
	public String stageId; // 0x10
	public String code; // 0x18
	public String name; // 0x20
	public Int32 value; // 0x28
	public Int32 target; // 0x2c
	public Int32 remainBreakFeeAdd; // 0x30
	public Int32 totalBreakFeeAdd; // 0x34
	public Boolean isUnlocked; // 0x38
	public String unlockText; // 0x40
	public Boolean isFinished; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dcf584 VA: 0x75953e7584
	public Void LoadData(String stageId) { }
	// RVA: 0x2dcf9e8 VA: 0x75953e79e8
	public Void .ctor() { }
}
```