# CampaignViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String id`

- `Int32 curMaxKillCnt`


## Methods

- `Void SetPlayerData(Stage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class CampaignViewModel
{
	public String id; // 0x10
	public Int32 curMaxKillCnt; // 0x18
	public List`1 breakLadders; // 0x20
	public List`1 displayRewards; // 0x28


	// RVA: 0x2f75f48 VA: 0x759558df48
	public Void .ctor(CampaignData campData) { }
	// RVA: 0x2f76678 VA: 0x759558e678
	public Void SetPlayerData(Stage instance) { }
}
```