# FifthAnnivExploreLogModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Int32 seqNum`

- `String eventTitle`

- `String eventTypeDesc`

- `String eventDesc`

- `String choiceTitle`

- `String choiceDesc`

- `Boolean isSuccess`

- `String resDesc`

- `String eventIconId`


## Methods

- `Void LoadData(FifthAnnivExploreEventPlanModel, ExploreSelectEventOptionResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreLogModel : IHotfixable
{
	public Int32 seqNum; // 0x10
	public String eventTitle; // 0x18
	public String eventTypeDesc; // 0x20
	public String eventDesc; // 0x28
	public String choiceTitle; // 0x30
	public String choiceDesc; // 0x38
	public Boolean isSuccess; // 0x40
	public String resDesc; // 0x48
	public Dictionary`2 deltaValues; // 0x50
	public String eventIconId; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x290cab8 VA: 0x7594f24ab8
	public Void LoadData(FifthAnnivExploreEventPlanModel currPlanModel, ExploreSelectEventOptionResponse response) { }
	// RVA: 0x290d0d0 VA: 0x7594f250d0
	public Void .ctor() { }
}
```