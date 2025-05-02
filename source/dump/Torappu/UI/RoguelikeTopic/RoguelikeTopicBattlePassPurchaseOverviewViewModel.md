# RoguelikeTopicBattlePassPurchaseOverviewViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 srcLevel`

- `Int32 dstLevel`

- `Int32 maxLevel`

- `String srcBpId`

- `String dstBpId`

- `String topicId`

- `Int32 curBpPoint`

- `RoguelikeTopicBP curBpData`

- `Boolean isInit`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseOverviewViewModel : IHotfixable
{
	public Int32 srcLevel; // 0x10
	public Int32 dstLevel; // 0x14
	public Int32 maxLevel; // 0x18
	public String srcBpId; // 0x20
	public String dstBpId; // 0x28
	public String topicId; // 0x30
	public Int32 curBpPoint; // 0x38
	public RoguelikeTopicBP curBpData; // 0x40
	public ListDict`2 grandPrizeList; // 0x48
	public ListDict`2 normalPrizeList; // 0x50
	public Boolean isInit; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x2674a5c VA: 0x7594c8ca5c
	public Void .ctor() { }
}
```