# BuildingMeetingSession

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `SpriteHub m_clueSpriteHub`

- `Character m_cachedCharacter0`

- `Character m_cachedCharacter1`

- `CharacterProduct m_characterProduct`

- `TransferResult m_lastTransferResult`

- `Boolean m_usePushFlag`

- `Int32 <transferringVisitNumber>k__BackingField`


## Properties

- `ICharacterClueProduct characterMadeClue`

- `IRoomClueProduct roomMadeClue`

- `PlayerBuildingMeeting meetingRoom`

- `IMeetingStationaryCharacter stationaryCharacter0`

- `IMeetingStationaryCharacter stationaryCharacter1`

- `Boolean hasNewProduct`

- `Boolean hasNewRecv`

- `Boolean hasNewSend`

- `Int32 clueCountNeededForUnlockTransfer`

- `Boolean transferring`

- `Int32 transferringVisitNumber`

- `Int32 transferringSocialPoint`

- `Int32 localStorageCapacity`

- `TransferResult lastTransferResult`

- `DateTime transferExpireTime`

- `String slotId`

- `Boolean needReceiveTransferReward`


## Methods

- `Character _FetchCharacter(Int32, ref)`

- `Void _UpdateCharacterProduct()`

- `Void _UpdateSocialReward(Action`1)`

- `ICharacterClueProduct get_characterMadeClue()`

- `IRoomClueProduct get_roomMadeClue()`

- `ClueTypeData _GetTypeFromNumber(Int32)`

- `PlayerBuildingMeeting get_meetingRoom()`

- `PlayerBuildingMeetingClue _GetClueFromId(String, out)`

- `IMeetingClue GetSlotClue(Int32)`

- `IMeetingStationaryCharacter get_stationaryCharacter0()`

- `IMeetingStationaryCharacter get_stationaryCharacter1()`

- `Boolean get_hasNewProduct()`

- `Boolean get_hasNewRecv()`

- `Boolean get_hasNewSend()`

- `Int32 get_clueCountNeededForUnlockTransfer()`

- `Boolean get_transferring()`

- `Int32 get_transferringVisitNumber()`

- `Void set_transferringVisitNumber(Int32)`

- `Int32 get_transferringSocialPoint()`

- `Int32 get_localStorageCapacity()`

- `TransferResult get_lastTransferResult()`

- `DateTime get_transferExpireTime()`

- `String get_slotId()`

- `Boolean get_needReceiveTransferReward()`

- `Int32 ReceiveBonus(Int32)`

- `Void EquipClue(IMeetingClue, Action`1)`

- `Void UnequipClue(IMeetingClue, Action`1)`

- `Void RemoveClue(IMeetingClue, Action`1)`

- `Void TryUnlockTransfer(Action`1)`

- `Void TryFetchRoomProductClue(Action`1)`

- `Void TryFetchTransferReward(Action`1)`

- `Void ReceiveExternalClue(IMeetingClue, Action`1)`

- `Void ReceiveAllExternalClue(Action`1)`

- `Void GiveClue(IMeetingClue, IPeer, Action`1)`

- `Void UpdatePeers(Action`1)`

- `Void UpdateTransferVisitNum(Action`1)`

- `Void UpdateWaitingClue(Action`1)`

- `Void OnInit(Action`1)`

- `Void OnPlayerDataChanged(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMeetingSession : IMeetingSession, IHotfixable
{
	private SpriteHub m_clueSpriteHub; // 0x10
	private Character m_cachedCharacter0; // 0x18
	private Character m_cachedCharacter1; // 0x20
	private List`1 m_peerList; // 0x28
	private List`1 m_storedClueCache; // 0x30
	private List`1 m_waitingClue; // 0x38
	private CharacterProduct m_characterProduct; // 0x40
	private TransferResult m_lastTransferResult; // 0x48
	private Boolean m_usePushFlag; // 0x50
	private Int32 <transferringVisitNumber>k__BackingField; // 0x54
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__FetchCharacter; // 0x8
	private static DelegateBridge __Hotfix0__GetClueList; // 0x10
	private static DelegateBridge __Hotfix0_get_storedClues; // 0x18
	private static DelegateBridge __Hotfix0_get_waitingClues; // 0x20
	private static DelegateBridge __Hotfix0_get_peers; // 0x28
	private static DelegateBridge __Hotfix0__UpdateCharacterProduct; // 0x30
	private static DelegateBridge __Hotfix0__UpdateSocialReward; // 0x38
	private static DelegateBridge __Hotfix0_get_characterMadeClue; // 0x40
	private static DelegateBridge __Hotfix0_get_roomMadeClue; // 0x48
	private static DelegateBridge __Hotfix0__GetTypeFromNumber; // 0x50
	private static DelegateBridge __Hotfix0_get_meetingRoom; // 0x58
	private static DelegateBridge __Hotfix0__GetClueFromId; // 0x60
	private static DelegateBridge __Hotfix0_GetSlotClue; // 0x68
	private static DelegateBridge __Hotfix0_get_stationaryCharacter0; // 0x70
	private static DelegateBridge __Hotfix0_get_stationaryCharacter1; // 0x78
	private static DelegateBridge __Hotfix0_get_hasNewProduct; // 0x80
	private static DelegateBridge __Hotfix0_get_hasNewRecv; // 0x88
	private static DelegateBridge __Hotfix0_get_hasNewSend; // 0x90
	private static DelegateBridge __Hotfix0_get_clueCountNeededForUnlockTransfer; // 0x98
	private static DelegateBridge __Hotfix0_get_transferring; // 0xa0
	private static DelegateBridge __Hotfix0_get_transferringVisitNumber; // 0xa8
	private static DelegateBridge __Hotfix0_set_transferringVisitNumber; // 0xb0
	private static DelegateBridge __Hotfix0_get_transferringSocialPoint; // 0xb8
	private static DelegateBridge __Hotfix0_get_localStorageCapacity; // 0xc0
	private static DelegateBridge __Hotfix0_get_lastTransferResult; // 0xc8
	private static DelegateBridge __Hotfix0_get_transferExpireTime; // 0xd0
	private static DelegateBridge __Hotfix0_get_slotId; // 0xd8
	private static DelegateBridge __Hotfix0_get_needReceiveTransferReward; // 0xe0
	private static DelegateBridge __Hotfix0_ReceiveBonus; // 0xe8
	private static DelegateBridge __Hotfix0_EquipClue; // 0xf0
	private static DelegateBridge __Hotfix0_UnequipClue; // 0xf8
	private static DelegateBridge __Hotfix0_RemoveClue; // 0x100
	private static DelegateBridge __Hotfix0_TryUnlockTransfer; // 0x108
	private static DelegateBridge __Hotfix0_TryFetchRoomProductClue; // 0x110
	private static DelegateBridge __Hotfix0_TryFetchTransferReward; // 0x118
	private static DelegateBridge __Hotfix0_ReceiveExternalClue; // 0x120
	private static DelegateBridge __Hotfix0_ReceiveAllExternalClue; // 0x128
	private static DelegateBridge __Hotfix0_GiveClue; // 0x130
	private static DelegateBridge __Hotfix0_UpdatePeers; // 0x138
	private static DelegateBridge __Hotfix0_UpdateTransferVisitNum; // 0x140
	private static DelegateBridge __Hotfix0_UpdateWaitingClue; // 0x148
	private static DelegateBridge __Hotfix0_OnInit; // 0x150
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x158

	public IEnumerable`1 storedClues { get; }
	public IEnumerable`1 waitingClues { get; }
	public IEnumerable`1 peers { get; }
	public ICharacterClueProduct characterMadeClue { get; }
	public IRoomClueProduct roomMadeClue { get; }
	private PlayerBuildingMeeting meetingRoom { get; }
	public IMeetingStationaryCharacter stationaryCharacter0 { get; }
	public IMeetingStationaryCharacter stationaryCharacter1 { get; }
	public Boolean hasNewProduct { get; }
	public Boolean hasNewRecv { get; }
	public Boolean hasNewSend { get; }
	public Int32 clueCountNeededForUnlockTransfer { get; }
	public Boolean transferring { get; }
	public Int32 transferringVisitNumber { get; set; }
	public Int32 transferringSocialPoint { get; }
	public Int32 localStorageCapacity { get; }
	public TransferResult lastTransferResult { get; }
	public DateTime transferExpireTime { get; }
	public String slotId { get; }
	public Boolean needReceiveTransferReward { get; }

	// RVA: 0x3de0b28 VA: 0x75963f8b28
	public Void .ctor() { }
	// RVA: 0x3de0ea4 VA: 0x75963f8ea4
	private Character _FetchCharacter(Int32 index, ref Character cache) { }
	// RVA: 0x3de137c VA: 0x75963f937c
	private IEnumerable`1 _GetClueList(List`1 clueList, Boolean external) { }
	// RVA: 0x3de14a0 VA: 0x75963f94a0
	public IEnumerable`1 get_storedClues() { }
	// RVA: 0x3de1590 VA: 0x75963f9590
	public IEnumerable`1 get_waitingClues() { }
	// RVA: 0x3de1680 VA: 0x75963f9680
	public IEnumerable`1 get_peers() { }
	// RVA: 0x3de0c98 VA: 0x75963f8c98
	private Void _UpdateCharacterProduct() { }
	// RVA: 0x3de1898 VA: 0x75963f9898
	private Void _UpdateSocialReward(Action`1 rewardHandler) { }
	// RVA: 0x3de1cf4 VA: 0x75963f9cf4
	public ICharacterClueProduct get_characterMadeClue() { }
	// RVA: 0x3de1d6c VA: 0x75963f9d6c
	public IRoomClueProduct get_roomMadeClue() { }
	// RVA: 0x3de21c4 VA: 0x75963fa1c4
	private ClueTypeData _GetTypeFromNumber(Int32 typeNumber) { }
	// RVA: 0x3de1770 VA: 0x75963f9770
	private PlayerBuildingMeeting get_meetingRoom() { }
	// RVA: 0x3de2304 VA: 0x75963fa304
	private PlayerBuildingMeetingClue _GetClueFromId(String id, out Boolean external) { }
	// RVA: 0x3de24ac VA: 0x75963fa4ac
	public IMeetingClue GetSlotClue(Int32 index) { }
	// RVA: 0x3de2a2c VA: 0x75963faa2c
	public IMeetingStationaryCharacter get_stationaryCharacter0() { }
	// RVA: 0x3de2a9c VA: 0x75963faa9c
	public IMeetingStationaryCharacter get_stationaryCharacter1() { }
	// RVA: 0x3de2b0c VA: 0x75963fab0c
	public Boolean get_hasNewProduct() { }
	// RVA: 0x3de2c04 VA: 0x75963fac04
	public Boolean get_hasNewRecv() { }
	// RVA: 0x3de2cd8 VA: 0x75963facd8
	public Boolean get_hasNewSend() { }
	// RVA: 0x3de2d3c VA: 0x75963fad3c
	public Int32 get_clueCountNeededForUnlockTransfer() { }
	// RVA: 0x3de2ddc VA: 0x75963faddc
	public Boolean get_transferring() { }
	// RVA: 0x3de2e4c VA: 0x75963fae4c
	public Int32 get_transferringVisitNumber() { }
	// RVA: 0x3de2eb4 VA: 0x75963faeb4
	private Void set_transferringVisitNumber(Int32 value) { }
	// RVA: 0x3de2f30 VA: 0x75963faf30
	public Int32 get_transferringSocialPoint() { }
	// RVA: 0x3de2fbc VA: 0x75963fafbc
	public Int32 get_localStorageCapacity() { }
	// RVA: 0x3de3048 VA: 0x75963fb048
	public TransferResult get_lastTransferResult() { }
	// RVA: 0x3de30b0 VA: 0x75963fb0b0
	public DateTime get_transferExpireTime() { }
	// RVA: 0x3de315c VA: 0x75963fb15c
	public String get_slotId() { }
	// RVA: 0x3de31e8 VA: 0x75963fb1e8
	public Boolean get_needReceiveTransferReward() { }
	// RVA: 0x3de3270 VA: 0x75963fb270
	public Int32 ReceiveBonus(Int32 count) { }
	// RVA: 0x3de33d8 VA: 0x75963fb3d8
	public Void EquipClue(IMeetingClue clue, Action`1 resultHandler) { }
	// RVA: 0x3de3718 VA: 0x75963fb718
	public Void UnequipClue(IMeetingClue clue, Action`1 resultHandler) { }
	// RVA: 0x3de3aec VA: 0x75963fbaec
	public Void RemoveClue(IMeetingClue clue, Action`1 resultHandler) { }
	// RVA: 0x3de3fe8 VA: 0x75963fbfe8
	public Void TryUnlockTransfer(Action`1 resultHandler) { }
	// RVA: 0x3de42cc VA: 0x75963fc2cc
	public Void TryFetchRoomProductClue(Action`1 resultHandler) { }
	// RVA: 0x3de45a0 VA: 0x75963fc5a0
	public Void TryFetchTransferReward(Action`1 resultHandler) { }
	// RVA: 0x3de4884 VA: 0x75963fc884
	public Void ReceiveExternalClue(IMeetingClue clue, Action`1 resultHandler) { }
	// RVA: 0x3de4cbc VA: 0x75963fccbc
	public Void ReceiveAllExternalClue(Action`1 resultHandler) { }
	// RVA: 0x3de508c VA: 0x75963fd08c
	public Void GiveClue(IMeetingClue clue, IPeer peer, Action`1 resultHandler) { }
	// RVA: 0x3de54d4 VA: 0x75963fd4d4
	public Void UpdatePeers(Action`1 resultHandler) { }
	// RVA: 0x3de5738 VA: 0x75963fd738
	public Void UpdateTransferVisitNum(Action`1 resultHandler) { }
	// RVA: 0x3de5964 VA: 0x75963fd964
	public Void UpdateWaitingClue(Action`1 resultHandler) { }
	// RVA: 0x3de5b90 VA: 0x75963fdb90
	public Void OnInit(Action`1 rewardHandler) { }
	// RVA: 0x3de5c10 VA: 0x75963fdc10
	public Void OnPlayerDataChanged(Action`1 rewardHandler) { }
}
```