# Act1VAutoChessHUDTopSelfHpView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `CanvasGroup _panelDanger`

- `Act1VAutoChessHUDHpView _hpView`

- `Boolean m_inited`

- `Single m_dangerPercent`

- `Single m_hpShowPercent`

- `Tweener m_hpTween`

- `FadeSwitchTween m_fadeTween`

- `HUDSeqNumChecker m_stateSeqChecker`

- `HUDSeqNumChecker m_ShieldSeqChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void _RenderPrepare(Act1VAutoChessHUDViewModel, Boolean)`

- `Void _ClearTweenIfNecessary()`

- `Void _RenderBattle(Act1VAutoChessHUDViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDTopSelfHpView : MonoBehaviour
{
	private CanvasGroup _panelDanger; // 0x18
	private Act1VAutoChessHUDHpView _hpView; // 0x20
	private Boolean m_inited; // 0x28
	private Single m_dangerPercent; // 0x2c
	private Single m_hpShowPercent; // 0x30
	private Tweener m_hpTween; // 0x38
	private FadeSwitchTween m_fadeTween; // 0x40
	private HUDSeqNumChecker m_stateSeqChecker; // 0x48
	private HUDSeqNumChecker m_ShieldSeqChecker; // 0x50


	// RVA: 0x337e4c4 VA: 0x75959964c4
	private Void _InitIfNot() { }
	// RVA: 0x337e568 VA: 0x7595996568
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337e5f4 VA: 0x75959965f4
	private Void _RenderPrepare(Act1VAutoChessHUDViewModel viewModel, Boolean fastMode) { }
	// RVA: 0x337ea14 VA: 0x7595996a14
	private Void _ClearTweenIfNecessary() { }
	// RVA: 0x337e8ec VA: 0x75959968ec
	private Void _RenderBattle(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337ea5c VA: 0x7595996a5c
	public Void .ctor() { }
}
```