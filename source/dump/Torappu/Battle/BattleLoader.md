# BattleLoader

**Namespace:** `Torappu.Battle`


## Fields

- `Single _minLoadingTime`

- `ResourceCollector _collector`

- `UIBattleLoading _loadingUI`

- `Single m_startLoadingTime`


## Methods

- `Void Start()`

- `Void _BeforeDoLoad()`

- `IEnumerator _DoLoad()`

- `Void _DoContinuousBattlePrepare(ref)`

- `Void _DoRestartGamePrepare()`

- `Void _DoMultiplayerLoad(ref)`

- `Void _OnFailed(String)`

- `Void _LoadDummyLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleLoader : AbstractBattleLoader
{
	private Single _minLoadingTime; // 0x18
	private ResourceCollector _collector; // 0x20
	private UIBattleLoading _loadingUI; // 0x28
	private Single m_startLoadingTime; // 0x30
	private List`1 m_configs; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0__BeforeDoLoad; // 0x8
	private static DelegateBridge __Hotfix0__DoLoad; // 0x10
	private static DelegateBridge __Hotfix0__DoContinuousBattlePrepare; // 0x18
	private static DelegateBridge __Hotfix0__DoRestartGamePrepare; // 0x20
	private static DelegateBridge __Hotfix0__DoMultiplayerLoad; // 0x28
	private static DelegateBridge __Hotfix0__OnFailed; // 0x30
	private static DelegateBridge __Hotfix0__LoadDummyLevel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3f71594 VA: 0x7596589594
	private Void Start() { }
	// RVA: 0x3f716c0 VA: 0x75965896c0
	private Void _BeforeDoLoad() { }
	// RVA: 0x3f71614 VA: 0x7596589614
	private IEnumerator _DoLoad() { }
	// RVA: 0x3f717dc VA: 0x75965897dc
	private Void _DoContinuousBattlePrepare(ref InParams input) { }
	// RVA: 0x3f718d0 VA: 0x75965898d0
	private Void _DoRestartGamePrepare() { }
	// RVA: 0x3f71994 VA: 0x7596589994
	private Void _DoMultiplayerLoad(ref InParams input) { }
	// RVA: 0x3f71d60 VA: 0x7596589d60
	private Void _OnFailed(String error) { }
	// RVA: 0x3f71ec0 VA: 0x7596589ec0
	private Void _LoadDummyLevel() { }
	// RVA: 0x3f72130 VA: 0x759658a130
	public Void .ctor() { }
}
```