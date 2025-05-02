# ClimbTowerFriendAssistModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SquadFriendData m_assistData`

- `Boolean m_isFriend`

- `CharacterData m_charData`


## Properties

- `Boolean isEmpty`

- `CharacterData charData`

- `SquadFriendData assistData`

- `Boolean isFriend`


## Methods

- `Boolean get_isEmpty()`

- `CharacterData get_charData()`

- `SquadFriendData get_assistData()`

- `Boolean get_isFriend()`

- `Void LoadData(SquadFriendData, Boolean)`

- `Void SetEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerFriendAssistModel : IHotfixable
{
	private SquadFriendData m_assistData; // 0x10
	private Boolean m_isFriend; // 0x18
	private CharacterData m_charData; // 0x20
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge __Hotfix0_get_charData; // 0x8
	private static DelegateBridge __Hotfix0_get_assistData; // 0x10
	private static DelegateBridge __Hotfix0_get_isFriend; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_SetEmpty; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isEmpty { get; }
	public CharacterData charData { get; }
	public SquadFriendData assistData { get; }
	public Boolean isFriend { get; }

	// RVA: 0x2cb648c VA: 0x75952ce48c
	public Boolean get_isEmpty() { }
	// RVA: 0x2cb6a88 VA: 0x75952cea88
	public CharacterData get_charData() { }
	// RVA: 0x2cb4ed4 VA: 0x75952cced4
	public SquadFriendData get_assistData() { }
	// RVA: 0x2cb4f3c VA: 0x75952ccf3c
	public Boolean get_isFriend() { }
	// RVA: 0x2cb50e0 VA: 0x75952cd0e0
	public Void LoadData(SquadFriendData assistData, Boolean isFriend) { }
	// RVA: 0x2cb6fa4 VA: 0x75952cefa4
	public Void SetEmpty() { }
	// RVA: 0x2cb6f34 VA: 0x75952cef34
	public Void .ctor() { }
}
```