# Act1VAutoChessHUDCampView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessHUDCampSelfView _selfCamp`

- `Act1VAutoChessHUDCampEnemyView _enemyCamp`

- `Act1VAutoChessHUDCampTipView _tipCamp`

- `UIAnimationLocation _rotateAnim`

- `CanvasGroup _back`

- `Boolean m_isInited`

- `FadeSwitchTween m_backFade`

- `AnimationSwitchTween m_rotateTween`

- `HUDSeqNumChecker m_stateChecker`

- `HUDSeqNumChecker m_campChecker`

- `HUDSeqNumChecker m_campUpdateChecker`

- `HUDSeqNumChecker m_campUpgradeChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampView : MonoBehaviour, IHotfixable
{
	private Act1VAutoChessHUDCampSelfView _selfCamp; // 0x18
	private Act1VAutoChessHUDCampEnemyView _enemyCamp; // 0x20
	private Act1VAutoChessHUDCampTipView _tipCamp; // 0x28
	private UIAnimationLocation _rotateAnim; // 0x30
	private CanvasGroup _back; // 0x40
	private Boolean m_isInited; // 0x48
	private FadeSwitchTween m_backFade; // 0x50
	private AnimationSwitchTween m_rotateTween; // 0x58
	private HUDSeqNumChecker m_stateChecker; // 0x60
	private HUDSeqNumChecker m_campChecker; // 0x68
	private HUDSeqNumChecker m_campUpdateChecker; // 0x70
	private HUDSeqNumChecker m_campUpgradeChecker; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x337218c VA: 0x759598a18c
	private Void _InitIfNot() { }
	// RVA: 0x33722e0 VA: 0x759598a2e0
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x3372520 VA: 0x759598a520
	public Void .ctor() { }
}
```