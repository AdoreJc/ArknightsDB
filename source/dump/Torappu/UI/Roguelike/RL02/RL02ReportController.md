# RL02ReportController

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RectTransform _viewContainer`

- `Boolean m_hasInited`

- `Boolean m_isTransiting`

- `ReportViewController m_viewController`


## Methods

- `Void _InitIfNot()`

- `Void _BindAction(RL02CommonReportViewBase)`

- `Void _TurnToPrevView()`

- `Void _TurnToNextView()`

- `Void _SkipToFinView()`

- `Void _CloseReport()`

- `Void _OnBackPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportController : RoguelikeReportController`1
{
	private static List`1 VIEW_ORDER; // 0x0
	private RL02CommonReportViewBase[] _reportViews; // 0x30
	private RectTransform _viewContainer; // 0x38
	private Boolean m_hasInited; // 0x40
	private Boolean m_isTransiting; // 0x41
	private ReportViewController m_viewController; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__BindAction; // 0x18
	private static DelegateBridge __Hotfix0__TurnToPrevView; // 0x20
	private static DelegateBridge __Hotfix0__TurnToNextView; // 0x28
	private static DelegateBridge __Hotfix0__SkipToFinView; // 0x30
	private static DelegateBridge __Hotfix0__CloseReport; // 0x38
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2b61194 VA: 0x7595179194
	protected override Void OnInit() { }
	// RVA: 0x2b612fc VA: 0x75951792fc
	private Void _InitIfNot() { }
	// RVA: 0x2b61974 VA: 0x7595179974
	private Void _BindAction(RL02CommonReportViewBase reportView) { }
	// RVA: 0x2b61d6c VA: 0x7595179d6c
	private Void _TurnToPrevView() { }
	// RVA: 0x2b61fe0 VA: 0x7595179fe0
	private Void _TurnToNextView() { }
	// RVA: 0x2b620d8 VA: 0x759517a0d8
	private Void _SkipToFinView() { }
	// RVA: 0x2b621b4 VA: 0x759517a1b4
	private Void _CloseReport() { }
	// RVA: 0x2b62254 VA: 0x759517a254
	private Void _OnBackPressed() { }
	// RVA: 0x2b622c8 VA: 0x759517a2c8
	public Void .ctor() { }
	// RVA: 0x2b62368 VA: 0x759517a368
	private static Void .cctor() { }
}
```