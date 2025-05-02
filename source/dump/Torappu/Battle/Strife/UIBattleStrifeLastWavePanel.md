# UIBattleStrifeLastWavePanel

**Namespace:** `Torappu.Battle.Strife`


## Fields

- `GameObject _objNextPart`

- `GameObject _objLastPart`

- `AnimationWrapper _waveAnim`

- `Boolean m_isShow`

- `Single m_showDuration`


## Methods

- `Void OnInit()`

- `Void OnCurWaveWillFinish(Single)`

- `Void UpdateGameInfo()`

- `Void _SwitchPanelShow(Single, Boolean)`

- `Void _PlayWaveTipsAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Strife
public class UIBattleStrifeLastWavePanel : MonoBehaviour, IHotfixable
{
	private GameObject _objNextPart; // 0x18
	private GameObject _objLastPart; // 0x20
	private AnimationWrapper _waveAnim; // 0x28
	private const String STRIFE_NEXT_WAVE_ANIM; // 0x0
	private const String STRIFE_LAST_WAVE_ANIM; // 0x0
	private Boolean m_isShow; // 0x30
	private Single m_showDuration; // 0x34
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnCurWaveWillFinish; // 0x8
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x10
	private static DelegateBridge __Hotfix0__SwitchPanelShow; // 0x18
	private static DelegateBridge __Hotfix0__PlayWaveTipsAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1c586a4 VA: 0x75942706a4
	public Void OnInit() { }
	// RVA: 0x1c58758 VA: 0x7594270758
	public Void OnCurWaveWillFinish(Single showTime) { }
	// RVA: 0x1c58900 VA: 0x7594270900
	public Void UpdateGameInfo() { }
	// RVA: 0x1c587f4 VA: 0x75942707f4
	private Void _SwitchPanelShow(Single showTime, Boolean isShow) { }
	// RVA: 0x1c589b8 VA: 0x75942709b8
	private Void _PlayWaveTipsAnim(Boolean isLast) { }
	// RVA: 0x1c58b50 VA: 0x7594270b50
	public Void .ctor() { }
}
```