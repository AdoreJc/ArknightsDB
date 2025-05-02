# RoguelikeTopicBPGrandPrize

**Namespace:** `Torappu`


## Fields

- `String grandPrizeDisplayId`

- `Int32 sortId`

- `Int32 displayUnlockYear`

- `Int32 displayUnlockMonth`

- `String acquireTitle`

- `String purchaseTitle`

- `String displayName`

- `String displayDiscription`

- `String bpLevelId`

- `ItemBundle itemBundle`

- `String detailAnnounceTime`

- `String picIdAftrerUnlock`


## Methods

- `Boolean ShouldSerializeitemBundle()`

- `Boolean ShouldSerializedetailAnnounceTime()`

- `Boolean ShouldSerializepicIdAftrerUnlock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicBPGrandPrize
{
	public String grandPrizeDisplayId; // 0x10
	public Int32 sortId; // 0x18
	public Int32 displayUnlockYear; // 0x1c
	public Int32 displayUnlockMonth; // 0x20
	public String acquireTitle; // 0x28
	public String purchaseTitle; // 0x30
	public String displayName; // 0x38
	public String displayDiscription; // 0x40
	public String bpLevelId; // 0x48
	public ItemBundle itemBundle; // 0x50
	public String detailAnnounceTime; // 0x58
	public String picIdAftrerUnlock; // 0x60


	// RVA: 0x34ab224 VA: 0x7595ac3224
	public Boolean ShouldSerializeitemBundle() { }
	// RVA: 0x34ab234 VA: 0x7595ac3234
	public Boolean ShouldSerializedetailAnnounceTime() { }
	// RVA: 0x34ab254 VA: 0x7595ac3254
	public Boolean ShouldSerializepicIdAftrerUnlock() { }
	// RVA: 0x34ab274 VA: 0x7595ac3274
	public Void .ctor() { }
}
```