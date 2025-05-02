# CarvingSettleViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String challengeName`

- `Int32 score`

- `Int32 newRound`

- `Boolean hasNewRecord`

- `Boolean hasNewRecordReward`

- `Int32 newRecordReward`

- `Boolean isComplete`

- `Boolean hasFirstPassReward`

- `Int32 firstPassReward`

- `Int32 mileStonePointBefore`

- `Int32 mileStonePointAfter`

- `CarvingMileStoneInfo mileStoneInfoBefore`

- `CarvingMileStoneInfo mileStoneInfoAfter`


## Methods

- `Void LoadData(Option)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingSettleViewModel : IHotfixable
{
	public String challengeName; // 0x10
	public Int32 score; // 0x18
	public Int32 newRound; // 0x1c
	public Boolean hasNewRecord; // 0x20
	public Boolean hasNewRecordReward; // 0x21
	public Int32 newRecordReward; // 0x24
	public Boolean isComplete; // 0x28
	public Boolean hasFirstPassReward; // 0x29
	public Int32 firstPassReward; // 0x2c
	public Int32 mileStonePointBefore; // 0x30
	public Int32 mileStonePointAfter; // 0x34
	public CarvingMileStoneInfo mileStoneInfoBefore; // 0x38
	public CarvingMileStoneInfo mileStoneInfoAfter; // 0x50
	public List`1 mileStoneList; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dc116c VA: 0x75953d916c
	public Void LoadData(Option input) { }
	// RVA: 0x2dc10fc VA: 0x75953d90fc
	public Void .ctor() { }
}
```