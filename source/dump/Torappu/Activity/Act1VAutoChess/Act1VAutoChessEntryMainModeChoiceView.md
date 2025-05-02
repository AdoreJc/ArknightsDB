# Act1VAutoChessEntryMainModeChoiceView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _rootContainer`

- `TwoStateToggle _clickToggle`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryMainModeChoiceView : Act1VAutoChessEntryMainSubFrontViewComponent
{
	private GameObject _rootContainer; // 0x38
	private ModePanel[] _modePanels; // 0x40
	private TwoStateToggle _clickToggle; // 0x48
	private Boolean m_isInited; // 0x50
	private Dictionary`2 m_modePanelMap; // 0x58
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3340a30 VA: 0x7595958a30
	public override Void OnRender(Act1VAutoChessEntryMainViewModel viewModel) { }
	// RVA: 0x3340c68 VA: 0x7595958c68
	private Void _InitIfNot() { }
	// RVA: 0x3340dc8 VA: 0x7595958dc8
	public Void .ctor() { }
}
```