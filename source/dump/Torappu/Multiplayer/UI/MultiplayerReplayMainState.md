# MultiplayerReplayMainState

**Namespace:** `Torappu.Multiplayer.UI`


## Fields

- `Text _videoInfo`

- `Dropdown _playerList`

- `IMultiplayerBattleVideo m_video`


## Methods

- `Void EventOpenFile()`

- `Void EventPlay()`

- `Void EventNetPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.UI
internal class MultiplayerReplayMainState : State
{
	private Text _videoInfo; // 0x50
	private Dropdown _playerList; // 0x58
	private IMultiplayerBattleVideo m_video; // 0x60
	private List`1 m_players; // 0x68
	private static DelegateBridge __Hotfix0_EventOpenFile; // 0x0
	private static DelegateBridge __Hotfix0_EventPlay; // 0x8
	private static DelegateBridge __Hotfix0_EventNetPlay; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3594710 VA: 0x7595bac710
	public Void EventOpenFile() { }
	// RVA: 0x3594d30 VA: 0x7595bacd30
	public Void EventPlay() { }
	// RVA: 0x3594e00 VA: 0x7595bace00
	public Void EventNetPlay() { }
	// RVA: 0x3594f0c VA: 0x7595bacf0c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3594f70 VA: 0x7595bacf70
	public Void .ctor() { }
}
```