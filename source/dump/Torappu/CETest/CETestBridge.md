# CETestBridge

**Namespace:** `Torappu.CETest`


## Fields

- `Boolean m_inited`

- `String m_levelJson`

- `String m_squadJson`

- `String m_runeJson`


## Properties

- `String levelJson`

- `String squadJson`

- `String runeJson`


## Methods

- `String get_levelJson()`

- `String get_squadJson()`

- `String get_runeJson()`

- `Void Dispose()`

- `Object LoadData()`

- `Void LoadLevel(String, String)`

- `Void BackToLogin()`

- `Void OnGameReset(BattleController)`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameStart()`

- `Void OnGameOver(GameResult)`

- `Void BlockOceanCatHead(ref)`

- `Void BlockOceanCatHeadInEditor(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.CETest
public class CETestBridge : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IBattleModule
{
	private Boolean m_inited; // 0x18
	public const String TEST_SCENE_NAME; // 0x0
	public const String TEST_BATTLE_LOADER_NAME; // 0x0
	public const String TEST_BATTLE_SCENE_NAME; // 0x0
	public const String TEST_SCENE_PATH; // 0x0
	public const String TEST_BATTLE_LOADER_PATH; // 0x0
	public const String TEST_BATTLE_SCENE_PATH; // 0x0
	public const String PREF_KEY; // 0x0
	private String m_levelJson; // 0x20
	private String m_squadJson; // 0x28
	private String m_runeJson; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_levelJson; // 0x8
	private static DelegateBridge __Hotfix0_get_squadJson; // 0x10
	private static DelegateBridge __Hotfix0_get_runeJson; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_Dispose; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_LoadLevel; // 0x38
	private static DelegateBridge __Hotfix0_BackToLogin; // 0x40
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x48
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x50
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x58
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x60
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0_BlockOceanCatHead; // 0x78
	private static DelegateBridge __Hotfix0_BlockOceanCatHeadInEditor; // 0x80

	public String levelJson { get; }
	public String squadJson { get; }
	public String runeJson { get; }

	// RVA: 0x376d970 VA: 0x7595d85970
	private Void .ctor() { }
	// RVA: 0x376d7e8 VA: 0x7595d857e8
	public String get_levelJson() { }
	// RVA: 0x376d850 VA: 0x7595d85850
	public String get_squadJson() { }
	// RVA: 0x376d8b8 VA: 0x7595d858b8
	public String get_runeJson() { }
	// RVA: 0x376da00 VA: 0x7595d85a00
	protected override Void OnInit() { }
	// RVA: 0x376daa8 VA: 0x7595d85aa8
	public Void Dispose() { }
	// RVA: 0x376db10 VA: 0x7595d85b10
	public Object LoadData() { }
	// RVA: 0x376db7c VA: 0x7595d85b7c
	public Void LoadLevel(String levelId, String squadId) { }
	// RVA: 0x376dc84 VA: 0x7595d85c84
	public Void BackToLogin() { }
	// RVA: 0x376dd98 VA: 0x7595d85d98
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x376de10 VA: 0x7595d85e10
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x376de88 VA: 0x7595d85e88
	public Void OnGameReady() { }
	// RVA: 0x376deec VA: 0x7595d85eec
	public Void OnGameStart() { }
	// RVA: 0x376df50 VA: 0x7595d85f50
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x376dfc8 VA: 0x7595d85fc8
	protected override Void OnDestroy() { }
	// RVA: 0x376e0a8 VA: 0x7595d860a8
	private Void BlockOceanCatHead(ref Boolean checkMark) { }
	// RVA: 0x376e1b4 VA: 0x7595d861b4
	private Void BlockOceanCatHeadInEditor(ref Boolean checkMark) { }
}
```