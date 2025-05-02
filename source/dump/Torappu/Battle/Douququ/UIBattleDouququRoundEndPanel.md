# UIBattleDouququRoundEndPanel

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `GameObject _objResultPart`

- `GameObject _objDetailPart`

- `GameObject _leftWin`

- `GameObject _leftLost`

- `GameObject _rightWin`

- `GameObject _rightLost`

- `Text _curBalence`

- `GameObject _balanceMax`

- `GameObject _addPart`

- `GameObject _subPart`

- `Text _addBalence`

- `Text _subBalence`

- `GameObject _btnNext`

- `GameObject _btnFinish`

- `CanvasGroup _detailCanvasGroup`

- `AnimationWrapper _roundEndAnim`

- `DouququUIRoundEndState m_state`

- `DouququGameMode m_manager`

- `Boolean m_gameFinish`


## Methods

- `Void Init(DouququUIRoundEndState)`

- `Void Show(DouququGameMode)`

- `Void OnRoundEndOver()`

- `Void _ShowResult()`

- `Void _ShowDetails()`

- `Void <_ShowResult>b__24_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class UIBattleDouququRoundEndPanel : MonoBehaviour, IHotfixable
{
	private GameObject _objResultPart; // 0x18
	private GameObject _objDetailPart; // 0x20
	private GameObject _leftWin; // 0x28
	private GameObject _leftLost; // 0x30
	private GameObject _rightWin; // 0x38
	private GameObject _rightLost; // 0x40
	private Text _curBalence; // 0x48
	private GameObject _balanceMax; // 0x50
	private GameObject _addPart; // 0x58
	private GameObject _subPart; // 0x60
	private Text _addBalence; // 0x68
	private Text _subBalence; // 0x70
	private GameObject _btnNext; // 0x78
	private GameObject _btnFinish; // 0x80
	private CanvasGroup _detailCanvasGroup; // 0x88
	private AnimationWrapper _roundEndAnim; // 0x90
	private DouququUIRoundEndState m_state; // 0x98
	private DouququGameMode m_manager; // 0xa0
	private Boolean m_gameFinish; // 0xa8
	private const String DOUQUQU_ROUND_RESULT_ANIM; // 0x0
	private const String DOUQUQU_ROUND_DETAIL_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_OnRoundEndOver; // 0x10
	private static DelegateBridge __Hotfix0__ShowResult; // 0x18
	private static DelegateBridge __Hotfix0__ShowDetails; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1dd2f0c VA: 0x75943eaf0c
	public Void Init(DouququUIRoundEndState announceState) { }
	// RVA: 0x1dd2f98 VA: 0x75943eaf98
	public Void Show(DouququGameMode manager) { }
	// RVA: 0x1dd3278 VA: 0x75943eb278
	public Void OnRoundEndOver() { }
	// RVA: 0x1dd309c VA: 0x75943eb09c
	private Void _ShowResult() { }
	// RVA: 0x1dd32f0 VA: 0x75943eb2f0
	private Void _ShowDetails() { }
	// RVA: 0x1dd395c VA: 0x75943eb95c
	public Void .ctor() { }
	// RVA: 0x1dd39cc VA: 0x75943eb9cc
	private Void <_ShowResult>b__24_0(String key) { }
}
```