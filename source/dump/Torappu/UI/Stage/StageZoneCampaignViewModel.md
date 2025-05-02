# StageZoneCampaignViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean isValid`

- `Int32 currentFee`

- `Int32 totalFee`

- `String feeCountDownStr`

- `String rotateGroupId`

- `String rotateStageId`

- `String rotateStageName`

- `String rotateZoneId`

- `String rotateZoneName`

- `Sprite spriteRotateZoneIcon`

- `String rotateRemainTimeStr`

- `Int64 rotateRemainTime`

- `Boolean isRotateUnlocked`

- `String rotateUnlockStr`

- `Boolean isTrainingAllOpen`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneCampaignViewModel : IHotfixable
{
	public Boolean isValid; // 0x10
	public Int32 currentFee; // 0x14
	public Int32 totalFee; // 0x18
	public String feeCountDownStr; // 0x20
	public String rotateGroupId; // 0x28
	public String rotateStageId; // 0x30
	public String rotateStageName; // 0x38
	public String rotateZoneId; // 0x40
	public String rotateZoneName; // 0x48
	public Sprite spriteRotateZoneIcon; // 0x50
	public String rotateRemainTimeStr; // 0x58
	public Int64 rotateRemainTime; // 0x60
	public Boolean isRotateUnlocked; // 0x68
	public String rotateUnlockStr; // 0x70
	public Boolean isTrainingAllOpen; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ef8de4 VA: 0x7595510de4
	public Void LoadData() { }
	// RVA: 0x2ef960c VA: 0x759551160c
	public Void .ctor() { }
}
```