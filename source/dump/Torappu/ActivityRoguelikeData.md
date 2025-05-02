# ActivityRoguelikeData

**Namespace:** `Torappu`


## Fields

- `String outerBuffToken`

- `String shopToken`

- `Int64 relicUnlockTime`

- `Single milestoneTokenRatio`

- `Single outerBuffTokenRatio`

- `Single relicTokenRatio`

- `Single relicOuterBuffTokenRatio`

- `Int32 reOpenCoolDown`

- `ItemBundle tokenItem`

- `String charStoneId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityRoguelikeData
{
	public ListDict`2 outBuffInfos; // 0x10
	public Dictionary`2 apSupplyOutOfDateDict; // 0x18
	public String outerBuffToken; // 0x20
	public String shopToken; // 0x28
	public Int64 relicUnlockTime; // 0x30
	public Single milestoneTokenRatio; // 0x38
	public Single outerBuffTokenRatio; // 0x3c
	public Single relicTokenRatio; // 0x40
	public Single relicOuterBuffTokenRatio; // 0x44
	public Int32 reOpenCoolDown; // 0x48
	public ItemBundle tokenItem; // 0x50
	public String charStoneId; // 0x58
	public List`1 milestone; // 0x60
	public List`1 unlockConds; // 0x68


	// RVA: 0x33bb844 VA: 0x75959d3844
	public Void .ctor() { }
}
```