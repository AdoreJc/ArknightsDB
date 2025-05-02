# EnemyDuelPerformView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _textLeft`

- `Text _textRight`

- `Text _textSupport`

- `GameObject _panelSupport`

- `GameObject _panelSupportLeft`

- `GameObject _panelSupportRight`

- `GameObject _panelSupportNormal`

- `GameObject _panelSupportAllin`

- `CanvasGroup _waitForOthers`

- `SimpleLayoutContent _leftContent`

- `SimpleLayoutContent _rightContent`

- `PrefabInstHolder _topBarInstHolder`

- `UIAnimationLocation _waitLoopAnim`

- `Boolean m_isInited`

- `AvatarAdapter m_leftAdapter`

- `AvatarAdapter m_rightAdapter`

- `FadeSwitchTween m_waitFadeSwitch`

- `EnemyDuelPerformViewModel m_cachedViewModel`

- `EnemyDuelBetTopBarView m_topBar`

- `Tween m_waitLoopTween`


## Methods

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__21_0(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPerformView : DataBinder`1
{
	private Text _textLeft; // 0x20
	private Text _textRight; // 0x28
	private Text _textSupport; // 0x30
	private GameObject _panelSupport; // 0x38
	private GameObject _panelSupportLeft; // 0x40
	private GameObject _panelSupportRight; // 0x48
	private GameObject _panelSupportNormal; // 0x50
	private GameObject _panelSupportAllin; // 0x58
	private CanvasGroup _waitForOthers; // 0x60
	private SimpleLayoutContent _leftContent; // 0x68
	private SimpleLayoutContent _rightContent; // 0x70
	private PrefabInstHolder _topBarInstHolder; // 0x78
	private UIAnimationLocation _waitLoopAnim; // 0x80
	private Boolean m_isInited; // 0x90
	private AvatarAdapter m_leftAdapter; // 0x98
	private AvatarAdapter m_rightAdapter; // 0xa0
	private FadeSwitchTween m_waitFadeSwitch; // 0xa8
	private EnemyDuelPerformViewModel m_cachedViewModel; // 0xb0
	private EnemyDuelBetTopBarView m_topBar; // 0xb8
	private Tween m_waitLoopTween; // 0xc0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x298ae4c VA: 0x7594fa2e4c
	private Void _InitIfNot() { }
	// RVA: 0x298b1b4 VA: 0x7594fa31b4
	public override Void OnValueChanged(EnemyDuelBattleProperty property) { }
	// RVA: 0x298b534 VA: 0x7594fa3534
	public Void .ctor() { }
	// RVA: 0x298b5c4 VA: 0x7594fa35c4
	private Void <_InitIfNot>b__21_0(GameObject obj) { }
}
```