# FriendListStateBean

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String searchWord`

- `SpriteHub m_professionIconHub`

- `TrackPointViewProperty friendTrackProp`

- `FriendListProperty friendListProperty`


## Methods

- `Void InitSpriteHub()`

- `Void _InitSpriteHubsIfNeeded()`

- `Boolean _CheckIfAssistDiffFromPlayer()`

- `Void _ApplyAssist(AssistApplyOptions)`

- `Void LoadNecessarySprite(CharacterCardViewModel)`

- `Void ApplyListData(Int32, GetFriendListResponse, List`1)`

- `Void ApplySearchData(Int32, SearchPlayerResponse, List`1)`

- `Void ApplyRequestListData(Int32, GetFriendRequestResponse, List`1)`

- `Void ApplyFriendAssistFloatPanel(Int32, String, ItemType)`

- `Void ApplySkillId(Int32, String)`

- `Void ApplyEquipId(Int32, String)`

- `Void SaveAssistIfNeeded()`

- `Void ApplySelectState(CharSelectStateBean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public String searchWord; // 0x18
	public SharedCharData[] selectedAssist; // 0x20
	public const Int32 PER_PAGE_COUNT; // 0x0
	private SpriteHub m_professionIconHub; // 0x28
	public TrackPointViewProperty friendTrackProp; // 0x30
	public FriendListProperty friendListProperty; // 0x38
	private static DelegateBridge __Hotfix0_InitSpriteHub; // 0x0
	private static DelegateBridge __Hotfix0__InitSpriteHubsIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfAssistDiffFromPlayer; // 0x10
	private static DelegateBridge __Hotfix0__ApplyAssist; // 0x18
	private static DelegateBridge __Hotfix0_LoadNecessarySprite; // 0x20
	private static DelegateBridge __Hotfix0_ApplyListData; // 0x28
	private static DelegateBridge __Hotfix0_ApplySearchData; // 0x30
	private static DelegateBridge __Hotfix0_ApplyRequestListData; // 0x38
	private static DelegateBridge __Hotfix0_ApplyFriendAssistFloatPanel; // 0x40
	private static DelegateBridge __Hotfix0_ApplySkillId; // 0x48
	private static DelegateBridge __Hotfix0_ApplyEquipId; // 0x50
	private static DelegateBridge __Hotfix0_SaveAssistIfNeeded; // 0x58
	private static DelegateBridge __Hotfix0_ApplySelectState; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x28af344 VA: 0x7594ec7344
	public Void InitSpriteHub() { }
	// RVA: 0x28bbd68 VA: 0x7594ed3d68
	private Void _InitSpriteHubsIfNeeded() { }
	// RVA: 0x28bbe28 VA: 0x7594ed3e28
	private Boolean _CheckIfAssistDiffFromPlayer() { }
	// RVA: 0x28bc118 VA: 0x7594ed4118
	private Void _ApplyAssist(AssistApplyOptions options) { }
	// RVA: 0x28b54dc VA: 0x7594ecd4dc
	public Void LoadNecessarySprite(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x28b09f4 VA: 0x7594ec89f4
	public Void ApplyListData(Int32 index, GetFriendListResponse friendListData, List`1 idList) { }
	// RVA: 0x28b4d60 VA: 0x7594eccd60
	public Void ApplySearchData(Int32 index, SearchPlayerResponse friendListData, List`1 idList) { }
	// RVA: 0x28b3248 VA: 0x7594ecb248
	public Void ApplyRequestListData(Int32 index, GetFriendRequestResponse friendListData, List`1 idList) { }
	// RVA: 0x28bc760 VA: 0x7594ed4760
	public Void ApplyFriendAssistFloatPanel(Int32 index, String id, ItemType type) { }
	// RVA: 0x28bc864 VA: 0x7594ed4864
	public Void ApplySkillId(Int32 characterIndex, String skillId) { }
	// RVA: 0x28bc940 VA: 0x7594ed4940
	public Void ApplyEquipId(Int32 characterIndex, String equipId) { }
	// RVA: 0x28bca1c VA: 0x7594ed4a1c
	public Void SaveAssistIfNeeded() { }
	// RVA: 0x28bcaa0 VA: 0x7594ed4aa0
	public Void ApplySelectState(CharSelectStateBean selectStateBean) { }
	// RVA: 0x28bce10 VA: 0x7594ed4e10
	public Void .ctor() { }
}
```