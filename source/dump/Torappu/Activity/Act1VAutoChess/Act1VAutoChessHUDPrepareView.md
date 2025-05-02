# Act1VAutoChessHUDPrepareView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _selfHp`

- `Text _enemyHp`

- `Text _round`

- `Text _def`

- `GameObject _panelNormalDef`

- `GameObject _panelSpecialDef`

- `UIAnimationLocation _specialAnim`

- `Single _specialAnimDelay`

- `CanvasGroup _defCanvasGroup`

- `CanvasGroup _defSpCanvasGroup`

- `CanvasGroup _tipSpCanvasGroup`

- `Boolean m_isInited`

- `Int32 m_showSelfHp`

- `Tween m_selfHpTween`

- `Tween m_specialRoundTween`

- `FadeSwitchTween m_defFadeSwitchTween`

- `FadeSwitchTween m_defSpFadeSwitchTween`

- `FadeSwitchTween m_tipSpFadeSwitchTween`

- `HUDSeqNumChecker m_campSeqChecker`

- `HUDSeqNumChecker m_stateSeqChecker`

- `HUDSeqNumChecker m_ShieldSeqChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void _PlaySpecialTween()`

- `Void _PlaySelfCurrHpTween(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDPrepareView : MonoBehaviour, IHotfixable
{
	private Text _selfHp; // 0x18
	private Text _enemyHp; // 0x20
	private Text _round; // 0x28
	private Text _def; // 0x30
	private GameObject _panelNormalDef; // 0x38
	private GameObject _panelSpecialDef; // 0x40
	private UIAnimationLocation _specialAnim; // 0x48
	private Single _specialAnimDelay; // 0x58
	private CanvasGroup _defCanvasGroup; // 0x60
	private CanvasGroup _defSpCanvasGroup; // 0x68
	private CanvasGroup _tipSpCanvasGroup; // 0x70
	private Boolean m_isInited; // 0x78
	private Int32 m_showSelfHp; // 0x7c
	private Tween m_selfHpTween; // 0x80
	private Tween m_specialRoundTween; // 0x88
	private FadeSwitchTween m_defFadeSwitchTween; // 0x90
	private FadeSwitchTween m_defSpFadeSwitchTween; // 0x98
	private FadeSwitchTween m_tipSpFadeSwitchTween; // 0xa0
	private HUDSeqNumChecker m_campSeqChecker; // 0xa8
	private HUDSeqNumChecker m_stateSeqChecker; // 0xb0
	private HUDSeqNumChecker m_ShieldSeqChecker; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__PlaySpecialTween; // 0x10
	private static DelegateBridge __Hotfix0__PlaySelfCurrHpTween; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x337d718 VA: 0x7595995718
	private Void _InitIfNot() { }
	// RVA: 0x337d8c0 VA: 0x75959958c0
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x337dc50 VA: 0x7595995c50
	private Void _PlaySpecialTween() { }
	// RVA: 0x337dda8 VA: 0x7595995da8
	private Void _PlaySelfCurrHpTween(Int32 targetHp) { }
	// RVA: 0x337dff8 VA: 0x7595995ff8
	public Void .ctor() { }
}
```