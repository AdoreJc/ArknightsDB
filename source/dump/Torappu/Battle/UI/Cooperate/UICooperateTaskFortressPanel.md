# UICooperateTaskFortressPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Text _maxWave`

- `Text _curWave`

- `Text _curEnemy`

- `Text _maxEnemy`

- `Text _fortressInfo`

- `String _fortressInfoKey`

- `Int32 m_maxWaveCnt`

- `Int32 m_waveFinished`

- `Scheduler m_scheduler`

- `CooperateGameMode m_gameMode`


## Methods

- `Void InitPanel()`

- `Void UpdatePanel()`

- `Void _UpdateWaveInfo()`

- `Void <InitPanel>b__10_0(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateTaskFortressPanel : MonoBehaviour, IHotfixable
{
	private Text _maxWave; // 0x18
	private Text _curWave; // 0x20
	private Text _curEnemy; // 0x28
	private Text _maxEnemy; // 0x30
	private Text _fortressInfo; // 0x38
	private String _fortressInfoKey; // 0x40
	private Int32 m_maxWaveCnt; // 0x48
	private Int32 m_waveFinished; // 0x4c
	private Scheduler m_scheduler; // 0x50
	private CooperateGameMode m_gameMode; // 0x58
	private static DelegateBridge __Hotfix0_InitPanel; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePanel; // 0x8
	private static DelegateBridge __Hotfix0__UpdateWaveInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x20d5ca4 VA: 0x75946edca4
	public Void InitPanel() { }
	// RVA: 0x20d61b8 VA: 0x75946ee1b8
	public Void UpdatePanel() { }
	// RVA: 0x20d5f2c VA: 0x75946edf2c
	private Void _UpdateWaveInfo() { }
	// RVA: 0x20d62dc VA: 0x75946ee2dc
	public Void .ctor() { }
	// RVA: 0x20d634c VA: 0x75946ee34c
	private Void <InitPanel>b__10_0(Object arg) { }
}
```