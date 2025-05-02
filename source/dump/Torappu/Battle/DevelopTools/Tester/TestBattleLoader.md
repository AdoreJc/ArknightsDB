# TestBattleLoader

**Namespace:** `Torappu.Battle.DevelopTools.Tester`


## Fields

- `Boolean _useSpecificScene`

- `String _nextScene`

- `String _levelId`

- `String _externalSquadConfig`

- `ResourceCollector _collector`

- `Boolean _isHard`

- `Boolean m_loading`

- `Single m_startLoadingTime`

- `String m_oldLevel`

- `TextAsset _packedLevelsAndSquadsJson`

- `String _actId`

- `GameModeType _gameModeType`

- `String _weatherId`

- `SandboxV2SeasonType _seasonType`

- `SubGameModeType _subGameModeType`

- `LevelAndJsonPack m_packedLevelsAndSquads`

- `Vector2 m_levelScrollPosition`

- `Vector2 m_squadScrollPosition`

- `String m_selectedSquadPath`


## Properties

- `Boolean useSpecificScene`


## Methods

- `Boolean get_useSpecificScene()`

- `IEnumerator _DoLoad()`

- `Void OnGUI()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools.Tester
public class TestBattleLoader : AbstractBattleLoader
{
	private const String TEST_BATTLE_LOADER_SCENE_PATH; // 0x0
	private Boolean _useSpecificScene; // 0x18
	private String _nextScene; // 0x20
	private String _levelId; // 0x28
	private String _externalSquadConfig; // 0x30
	private ResourceCollector _collector; // 0x38
	private AdvancedCharacterInst[] _slots; // 0x40
	private Boolean _isHard; // 0x48
	private Boolean m_loading; // 0x49
	private Single m_startLoadingTime; // 0x4c
	private List`1 m_configs; // 0x50
	private HashSet`1 m_resourceSet; // 0x58
	private String m_oldLevel; // 0x60
	private List`1 m_displayedLevel; // 0x68
	private String[] _levelJsonsPaths; // 0x70
	private String[] _squadJsonsPaths; // 0x78
	private TextAsset _packedLevelsAndSquadsJson; // 0x80
	private String _actId; // 0x88
	private GameModeType _gameModeType; // 0x90
	private String _weatherId; // 0x98
	private SandboxV2SeasonType _seasonType; // 0xa0
	private SubGameModeType _subGameModeType; // 0xa4
	private LevelAndJsonPack m_packedLevelsAndSquads; // 0xa8
	private Vector2 m_levelScrollPosition; // 0xb0
	private Vector2 m_squadScrollPosition; // 0xb8
	private String m_selectedSquadPath; // 0xc0
	private static DelegateBridge __Hotfix0_get_useSpecificScene; // 0x0
	private static DelegateBridge __Hotfix0__DoLoad; // 0x8
	private static DelegateBridge __Hotfix0_OnGUI; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean useSpecificScene { get; }

	// RVA: 0x1d2db58 VA: 0x7594345b58
	public Boolean get_useSpecificScene() { }
	// RVA: 0x1d2dbc0 VA: 0x7594345bc0
	private IEnumerator _DoLoad() { }
	// RVA: 0x1d2dc94 VA: 0x7594345c94
	private Void OnGUI() { }
	// RVA: 0x1d2e50c VA: 0x759434650c
	private Void Start() { }
	// RVA: 0x1d2e5dc VA: 0x75943465dc
	public Void .ctor() { }
}
```