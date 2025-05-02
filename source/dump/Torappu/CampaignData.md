# CampaignData

**Namespace:** `Torappu`


## Fields

- `String stageId`

- `Int32 isSmallScale`

- `Boolean isCustomized`


## Methods

- `GainLadder GetGainDataOrDefault(Int32)`

- `GainLadder GetGainDataOrDefault(CampaignStageType, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CampaignData : IHotfixable
{
	public String stageId; // 0x10
	public Int32 isSmallScale; // 0x18
	public List`1 breakLadders; // 0x20
	public Boolean isCustomized; // 0x28
	public Dictionary`2 dropGains; // 0x30
	private static DelegateBridge __Hotfix0_GetGainDataOrDefault; // 0x0
	private static DelegateBridge __Hotfix1_GetGainDataOrDefault; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33c7e28 VA: 0x75959dfe28
	public GainLadder GetGainDataOrDefault(Int32 killCnt) { }
	// RVA: 0x33c7eb8 VA: 0x75959dfeb8
	public GainLadder GetGainDataOrDefault(CampaignStageType stageType, Int32 killCnt) { }
	// RVA: 0x33c801c VA: 0x75959e001c
	public Void .ctor() { }
}
```