# Act1VAutoChessCharSelectShuffleView

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `Text _profLabel`

- `GameObject _norAllNode`

- `GameObject _norProfNode`

- `GameObject _expandNode`

- `CanvasGroup _listPanel`

- `FadeSwitchTween m_fadeSwitch`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnFilterChange(ProfessionCategory)`

- `Void EventOnShowListPanel()`

- `Void EventOnHideListPanel()`

- `Void _SetFilterPanelShow(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectShuffleView : TemplateCharSelectShuffleViewBase`1
{
	private Text _profLabel; // 0x30
	private GameObject _norAllNode; // 0x38
	private GameObject _norProfNode; // 0x40
	private GameObject _expandNode; // 0x48
	private CanvasGroup _listPanel; // 0x50
	private Act1VAutoChessCharSelectFilterItem[] _filters; // 0x58
	private FadeSwitchTween m_fadeSwitch; // 0x60
	private static DelegateBridge __Hotfix0_OnRenderViewModel; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EventOnFilterChange; // 0x10
	private static DelegateBridge __Hotfix0_EventOnShowListPanel; // 0x18
	private static DelegateBridge __Hotfix0_EventOnHideListPanel; // 0x20
	private static DelegateBridge __Hotfix0__SetFilterPanelShow; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x338cdcc VA: 0x75959a4dcc
	protected override Void OnRenderViewModel() { }
	// RVA: 0x338cfec VA: 0x75959a4fec
	private Void _InitIfNot() { }
	// RVA: 0x338d1f8 VA: 0x75959a51f8
	private Void _EventOnFilterChange(ProfessionCategory filter) { }
	// RVA: 0x338d458 VA: 0x75959a5458
	public Void EventOnShowListPanel() { }
	// RVA: 0x338d5fc VA: 0x75959a55fc
	public Void EventOnHideListPanel() { }
	// RVA: 0x338d4c4 VA: 0x75959a54c4
	private Void _SetFilterPanelShow(Boolean v) { }
	// RVA: 0x338d668 VA: 0x75959a5668
	public Void .ctor() { }
}
```