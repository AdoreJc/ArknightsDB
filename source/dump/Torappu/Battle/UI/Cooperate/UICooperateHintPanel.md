# UICooperateHintPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `RectTransform _hintRect`

- `Text _hintText`

- `Text _infoText`

- `Single _targetPosOffset`

- `Single _infoPosOffset`

- `HintType m_curHint`

- `Single m_curDuration`

- `CooperateGameMode m_gameMode`

- `Vector2 m_originPos`

- `Vector2 m_fixPos`

- `Vector2 m_fixInfoPos`


## Methods

- `Void OnInit()`

- `Void Update()`

- `Void _ActiveHint(HintOptions)`

- `Void ShowHint(HintType)`

- `Void HideHint(HintType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateHintPanel : MonoBehaviour, IHotfixable
{
	private RectTransform _hintRect; // 0x18
	private Text _hintText; // 0x20
	private Text _infoText; // 0x28
	private Single _targetPosOffset; // 0x30
	private Single _infoPosOffset; // 0x34
	private List`1 _hints; // 0x38
	private List`1 _hintStyles; // 0x40
	private HintType m_curHint; // 0x48
	private Single m_curDuration; // 0x4c
	private CooperateGameMode m_gameMode; // 0x50
	private Vector2 m_originPos; // 0x58
	private Vector2 m_fixPos; // 0x60
	private Vector2 m_fixInfoPos; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__ActiveHint; // 0x10
	private static DelegateBridge __Hotfix0_ShowHint; // 0x18
	private static DelegateBridge __Hotfix0_HideHint; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x20cf7d0 VA: 0x75946e77d0
	public Void OnInit() { }
	// RVA: 0x20cfafc VA: 0x75946e7afc
	private Void Update() { }
	// RVA: 0x20cfda4 VA: 0x75946e7da4
	private Void _ActiveHint(HintOptions option) { }
	// RVA: 0x20d0018 VA: 0x75946e8018
	public Void ShowHint(HintType type) { }
	// RVA: 0x20cfbe4 VA: 0x75946e7be4
	public Void HideHint(HintType type) { }
	// RVA: 0x20d01f8 VA: 0x75946e81f8
	public Void .ctor() { }
}
```