# BattleLauncher

**Namespace:** `Torappu.Battle`


## Fields

- `String _levelId`

- `TextAsset _levelJson`

- `TextAsset _squadJson`

- `TextAsset _runeJson`

- `OperaConfig _operaConfig`

- `TextAsset _relicJson`

- `Difficulty _difficulty`

- `Boolean _forceReimportOnStart`

- `Boolean _includeDefaultGraphic`

- `Boolean _forceUseSquadFile`

- `Boolean _autoReplay`

- `String _autoReplayPlugin`

- `TextAsset _logJson`

- `Boolean _roguelikeDevLocal`

- `Boolean _multiplayerDevLocal`

- `PlayerSide _playerSide`

- `Boolean _enableAnother`

- `PlayerSide _playerSideAnother`

- `TextAsset _squadAnotherJson`


## Properties

- `Boolean isRoguelikeDevLocal`

- `Boolean isMultiplayerDevLocal`

- `Boolean IsMultiplayerDevLocalAndEnableAnother`


## Methods

- `Boolean get_isRoguelikeDevLocal()`

- `Boolean get_isMultiplayerDevLocal()`

- `Boolean get_IsMultiplayerDevLocalAndEnableAnother()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleLauncher : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private String _levelId; // 0x18
	private TextAsset _levelJson; // 0x20
	private TextAsset _squadJson; // 0x28
	private TextAsset _runeJson; // 0x30
	private OperaConfig _operaConfig; // 0x38
	private TextAsset _relicJson; // 0x40
	private Difficulty _difficulty; // 0x48
	private List`1 _slots; // 0x50
	private Boolean _forceReimportOnStart; // 0x58
	private Boolean _includeDefaultGraphic; // 0x59
	private Boolean _forceUseSquadFile; // 0x5a
	private Boolean _autoReplay; // 0x5b
	private String _autoReplayPlugin; // 0x60
	private TextAsset _logJson; // 0x68
	private Boolean _roguelikeDevLocal; // 0x70
	private Boolean _multiplayerDevLocal; // 0x71
	private PlayerSide _playerSide; // 0x74
	private Boolean _enableAnother; // 0x78
	private PlayerSide _playerSideAnother; // 0x7c
	private TextAsset _squadAnotherJson; // 0x80
	private List`1 _slotsAnother; // 0x88
	private static DelegateBridge __Hotfix0_get_isRoguelikeDevLocal; // 0x0
	private static DelegateBridge __Hotfix0_get_isMultiplayerDevLocal; // 0x8
	private static DelegateBridge __Hotfix0_get_IsMultiplayerDevLocalAndEnableAnother; // 0x10
	private static DelegateBridge __Hotfix0_LoadLevelData; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_AIRL_StartGameManually; // 0x28
	private static DelegateBridge __Hotfix0_AIRL_InitModuleAndMap; // 0x30
	private static DelegateBridge __Hotfix0__CreateBattlePlayerData; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_CETest_InitModuleAndMap; // 0x48
	private static DelegateBridge __Hotfix0__ChangeUI_EditorOnly; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isRoguelikeDevLocal { get; }
	public Boolean isMultiplayerDevLocal { get; }
	public Boolean IsMultiplayerDevLocalAndEnableAnother { get; }

	// RVA: 0x3f704a0 VA: 0x75965884a0
	public Boolean get_isRoguelikeDevLocal() { }
	// RVA: 0x3f70508 VA: 0x7596588508
	public Boolean get_isMultiplayerDevLocal() { }
	// RVA: 0x3f70570 VA: 0x7596588570
	public Boolean get_IsMultiplayerDevLocalAndEnableAnother() { }
	// RVA: 0x3f705f0 VA: 0x75965885f0
	protected virtual LevelData LoadLevelData() { }
	// RVA: 0x3f707cc VA: 0x75965887cc
	private Void Start() { }
	// RVA: 0x3f70f08 VA: 0x7596588f08
	private static Void AIRL_StartGameManually() { }
	// RVA: 0x3f70f8c VA: 0x7596588f8c
	private static Void AIRL_InitModuleAndMap(LevelData levelData) { }
	// RVA: 0x3f70c94 VA: 0x7596588c94
	private List`1 _CreateBattlePlayerData() { }
	// RVA: 0x3f710b4 VA: 0x75965890b4
	protected override Void OnDestroy() { }
	// RVA: 0x3f711a4 VA: 0x75965891a4
	private static Void CETest_InitModuleAndMap(LevelData levelData) { }
	// RVA: 0x3f71208 VA: 0x7596589208
	private static Void _ChangeUI_EditorOnly() { }
	// RVA: 0x3f71264 VA: 0x7596589264
	public Void .ctor() { }
}
```