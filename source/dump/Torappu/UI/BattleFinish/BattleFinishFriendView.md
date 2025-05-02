# BattleFinishFriendView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Text _friendName`

- `Text _awayTime`

- `Text _friendLvl`

- `Text _serverName`

- `Text _friendid`

- `TwoStateToggle _onlineState`

- `Text _addFriendText`

- `Transform _avatarContainer`

- `Single _avatarScale`

- `Int32 index`

- `FriendData friendData`


## Methods

- `Void ApplyData(SquadFriendData)`

- `String _TimeText(DateTime)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishFriendView : MonoBehaviour, IHotfixable
{
	private Text _friendName; // 0x18
	private Text _awayTime; // 0x20
	private Text _friendLvl; // 0x28
	private Text _serverName; // 0x30
	private Text _friendid; // 0x38
	private TwoStateToggle _onlineState; // 0x40
	private Text _addFriendText; // 0x48
	private Transform _avatarContainer; // 0x50
	private Single _avatarScale; // 0x58
	public Int32 index; // 0x5c
	protected FriendData friendData; // 0x60
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__TimeText; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e8e6d4 VA: 0x75954a66d4
	public Void ApplyData(SquadFriendData data) { }
	// RVA: 0x2e8e9b4 VA: 0x75954a69b4
	private String _TimeText(DateTime lastOnlineTime) { }
	// RVA: 0x2e8ec04 VA: 0x75954a6c04
	public Void .ctor() { }
}
```