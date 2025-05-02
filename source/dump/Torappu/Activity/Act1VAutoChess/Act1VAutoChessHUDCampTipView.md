# Act1VAutoChessHUDCampTipView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _def`

- `Text _defTip`

- `Text _charDamage`

- `Text _charDamageTip`

- `UIAnimationLocation _showAnimation`

- `CanvasGroup _rootCG`

- `SimpleLayoutContent _professionContent`

- `SimpleLayoutContent _factionContent`

- `Boolean m_isInited`

- `FactionAdapter m_factionAdapter`

- `ProfessionAdapter m_professionAdapter`

- `AnimationSwitchTween m_showTween`

- `Act1VAutoChessHUDViewModel m_cachedModel`

- `HUDSeqNumChecker m_stateChecker`

- `HUDSeqNumChecker m_campUpdateChecker`

- `HUDSeqNumChecker m_selfShieldChecker`

- `HUDSeqNumChecker m_charChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(HUDCampShowState, Act1VAutoChessHUDViewModel, Int32[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampTipView : MonoBehaviour, IHotfixable
{
	private Text _def; // 0x18
	private Text _defTip; // 0x20
	private Text _charDamage; // 0x28
	private Text _charDamageTip; // 0x30
	private UIAnimationLocation _showAnimation; // 0x38
	private CanvasGroup _rootCG; // 0x48
	private SimpleLayoutContent _professionContent; // 0x50
	private SimpleLayoutContent _factionContent; // 0x58
	private Boolean m_isInited; // 0x60
	private FactionAdapter m_factionAdapter; // 0x68
	private ProfessionAdapter m_professionAdapter; // 0x70
	private AnimationSwitchTween m_showTween; // 0x78
	private Act1VAutoChessHUDViewModel m_cachedModel; // 0x80
	private HUDSeqNumChecker m_stateChecker; // 0x88
	private HUDSeqNumChecker m_campUpdateChecker; // 0x90
	private HUDSeqNumChecker m_selfShieldChecker; // 0x98
	private HUDSeqNumChecker m_charChecker; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x336a234 VA: 0x7595982234
	private Void _InitIfNot() { }
	// RVA: 0x336a4dc VA: 0x75959824dc
	public Void Render(HUDCampShowState campState, Act1VAutoChessHUDViewModel model, Int32[] seqNums) { }
	// RVA: 0x336a750 VA: 0x7595982750
	public Void .ctor() { }
}
```