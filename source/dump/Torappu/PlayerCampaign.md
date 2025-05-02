# PlayerCampaign

**Namespace:** `Torappu`


## Fields

- `Int32 campaignCurrentFee`

- `Int32 campaignTotalFee`

- `String activeGroupId`

- `StageOpenInfo open`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerCampaign
{
	public Int32 campaignCurrentFee; // 0x10
	public Int32 campaignTotalFee; // 0x14
	public String activeGroupId; // 0x18
	public StageOpenInfo open; // 0x20
	public Dictionary`2 missions; // 0x28
	public Dictionary`2 instances; // 0x30
	public Dictionary`2 sweepMaxKills; // 0x38


	// RVA: 0x32d4b2c VA: 0x75958ecb2c
	public Void .ctor() { }
}
```