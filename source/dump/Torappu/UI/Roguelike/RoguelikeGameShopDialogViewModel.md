# RoguelikeGameShopDialogViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String m_topicId`

- `RoguelikeTopicDetail m_detailData`

- `RoguelikeGameShopDialogType m_dialogType`

- `String m_dialogStr`

- `Int32 m_rewardHintCount`

- `Boolean m_npcExsit`


## Properties

- `String dialogStr`

- `Boolean npcExist`


## Methods

- `String get_dialogStr()`

- `Boolean get_npcExist()`

- `Void Init(String, Boolean)`

- `Void UpdateDialogType(RoguelikeGameShopDialogType, RoguelikeGameItemType)`

- `String _GetRandomDialog(RoguelikeGameShopDialogType, RoguelikeGameItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameShopDialogViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private RoguelikeTopicDetail m_detailData; // 0x18
	private RoguelikeGameShopDialogType m_dialogType; // 0x20
	private String m_dialogStr; // 0x28
	private const Int32 REWARD_HINT_MAX; // 0x0
	private Int32 m_rewardHintCount; // 0x30
	private Boolean m_npcExsit; // 0x34
	private static DelegateBridge __Hotfix0_get_dialogStr; // 0x0
	private static DelegateBridge __Hotfix0_get_npcExist; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_UpdateDialogType; // 0x18
	private static DelegateBridge __Hotfix0__GetRandomDialog; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String dialogStr { get; }
	public Boolean npcExist { get; }

	// RVA: 0x2ae165c VA: 0x75950f965c
	public String get_dialogStr() { }
	// RVA: 0x2ae16c4 VA: 0x75950f96c4
	public Boolean get_npcExist() { }
	// RVA: 0x2ae172c VA: 0x75950f972c
	public Void Init(String topicId, Boolean npcExist) { }
	// RVA: 0x2ad6fa4 VA: 0x75950eefa4
	public Void UpdateDialogType(RoguelikeGameShopDialogType dialogType, RoguelikeGameItemType itemType) { }
	// RVA: 0x2ae1874 VA: 0x75950f9874
	private String _GetRandomDialog(RoguelikeGameShopDialogType dialogType, RoguelikeGameItemType itemType) { }
	// RVA: 0x2ae19d8 VA: 0x75950f99d8
	public Void .ctor() { }
}
```