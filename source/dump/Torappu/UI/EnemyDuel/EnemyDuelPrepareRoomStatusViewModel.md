# EnemyDuelPrepareRoomStatusViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `String modeId`

- `ReadyState readyState`

- `Int64 roomEndTs`

- `EnemyDuelServiceTeamInfo teamInfo`

- `ActivityEnemyDuelModeData modeData`

- `EnemyDuelPrepareRoomPlayerCardViewModel selfCardViewModel`

- `Boolean allowNpc`

- `ActivityEnemyDuelData actData`

- `ActivityEnemyDuelConstData constData`


## Methods

- `Void LoadModeData(String)`

- `Void LoadStableData(String)`

- `Void UpdateFriendData(GetFriendAndRequestSendListResponse)`

- `Void AddSentFriendRequestId(String)`

- `Void UpdateTeamSvrData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareRoomStatusViewModel : IHotfixable
{
	public String actId; // 0x10
	public String modeId; // 0x18
	public ReadyState readyState; // 0x20
	public Int64 roomEndTs; // 0x28
	public EnemyDuelServiceTeamInfo teamInfo; // 0x30
	public ActivityEnemyDuelModeData modeData; // 0x38
	public List`1 playerCardViewModels; // 0x40
	public EnemyDuelPrepareRoomPlayerCardViewModel selfCardViewModel; // 0x48
	public Boolean allowNpc; // 0x50
	private ActivityEnemyDuelData actData; // 0x58
	private ActivityEnemyDuelConstData constData; // 0x60
	public HashSet`1 friendIds; // 0x68
	public HashSet`1 friendRequestSentIds; // 0x70
	private static DelegateBridge __Hotfix0_LoadModeData; // 0x0
	private static DelegateBridge __Hotfix0_LoadStableData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateFriendData; // 0x10
	private static DelegateBridge __Hotfix0_AddSentFriendRequestId; // 0x18
	private static DelegateBridge __Hotfix0_UpdateTeamSvrData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x299b0cc VA: 0x7594fb30cc
	private Void LoadModeData(String modeId) { }
	// RVA: 0x299a7b0 VA: 0x7594fb27b0
	public Void LoadStableData(String actId) { }
	// RVA: 0x299b2b4 VA: 0x7594fb32b4
	public Void UpdateFriendData(GetFriendAndRequestSendListResponse resp) { }
	// RVA: 0x299b480 VA: 0x7594fb3480
	public Void AddSentFriendRequestId(String id) { }
	// RVA: 0x299a918 VA: 0x7594fb2918
	public Void UpdateTeamSvrData() { }
	// RVA: 0x299ae78 VA: 0x7594fb2e78
	public Void .ctor() { }
}
```