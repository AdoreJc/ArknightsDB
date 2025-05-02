# RoguelikeActivitySeedListModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `Int32 m_itemCnt`

- `String topicId`

- `String rlActId`

- `SeedItemType curTagType`

- `RoguelikeActivitySeedModeConstData constData`

- `Boolean isPlaying`

- `String copySeedFormat`

- `String copySucceededTextHint`

- `Int32 switchTagSequenceNum`


## Methods

- `Void LoadData(String, String)`

- `Void _LoadHistory()`

- `Void _LoadPredefine(RoguelikeActivitySeedModeData)`

- `Boolean CheckIsCurEnableSeed()`

- `Void SwitchTagType(SeedItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedListModel : IHotfixable
{
	private List`1 m_historySeedItemModelList; // 0x10
	private List`1 m_predefineSeedItemModelList; // 0x18
	private Int32 m_itemCnt; // 0x20
	public String topicId; // 0x28
	public String rlActId; // 0x30
	public SeedItemType curTagType; // 0x38
	public RoguelikeActivitySeedModeConstData constData; // 0x40
	public Boolean isPlaying; // 0x48
	public String copySeedFormat; // 0x50
	public String copySucceededTextHint; // 0x58
	public Int32 switchTagSequenceNum; // 0x60
	private static DelegateBridge __Hotfix0_get_curSeedItemModelList; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadHistory; // 0x10
	private static DelegateBridge __Hotfix0__LoadPredefine; // 0x18
	private static DelegateBridge __Hotfix0_CheckIsCurEnableSeed; // 0x20
	private static DelegateBridge __Hotfix0_SwitchTagType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 curSeedItemModelList { get; }

	// RVA: 0x26e2408 VA: 0x7594cfa408
	public List`1 get_curSeedItemModelList() { }
	// RVA: 0x26e0b8c VA: 0x7594cf8b8c
	public Void LoadData(String inputTopicId, String inputRlActId) { }
	// RVA: 0x26e2494 VA: 0x7594cfa494
	private Void _LoadHistory() { }
	// RVA: 0x26e27fc VA: 0x7594cfa7fc
	private Void _LoadPredefine(RoguelikeActivitySeedModeData seedModeData) { }
	// RVA: 0x26e150c VA: 0x7594cf950c
	public Boolean CheckIsCurEnableSeed() { }
	// RVA: 0x26e1264 VA: 0x7594cf9264
	public Void SwitchTagType(SeedItemType type) { }
	// RVA: 0x26e0a94 VA: 0x7594cf8a94
	public Void .ctor() { }
}
```