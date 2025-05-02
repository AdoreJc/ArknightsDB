# RoguelikeDungeonCostDefaultPanel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Action onCancel`

- `Action onAccept`

- `CanvasGroup _canvas`

- `Image _itemIcon`

- `Text _itemDesc`

- `Text _itemRemainContainer`

- `UIColorGraphic _uiColor`

- `FadeSwitchTween m_showTween`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void _OpenPanel()`

- `Void _ClosePanel()`

- `Void EventOnConfirm()`

- `Void OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonCostDefaultPanel : RoguelikeDungeonCostBasePanel
{
	public Action onCancel; // 0x18
	public Action onAccept; // 0x20
	private CanvasGroup _canvas; // 0x28
	private Image _itemIcon; // 0x30
	private Text _itemDesc; // 0x38
	private Text _itemRemainContainer; // 0x40
	private UIColorGraphic _uiColor; // 0x48
	private FadeSwitchTween m_showTween; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_HandleOnOpenCost; // 0x8
	private static DelegateBridge __Hotfix0__OpenPanel; // 0x10
	private static DelegateBridge __Hotfix0__ClosePanel; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2a0a934 VA: 0x7595022934
	private Void _InitIfNot() { }
	// RVA: 0x2a0aa18 VA: 0x7595022a18
	public override Void HandleOnOpenCost(UIPage page, Config config) { }
	// RVA: 0x2a0ac84 VA: 0x7595022c84
	private Void _OpenPanel() { }
	// RVA: 0x2a0acfc VA: 0x7595022cfc
	private Void _ClosePanel() { }
	// RVA: 0x2a0ad74 VA: 0x7595022d74
	public Void EventOnConfirm() { }
	// RVA: 0x2a0adf4 VA: 0x7595022df4
	public Void OnCancel() { }
	// RVA: 0x2a0ae74 VA: 0x7595022e74
	public Void .ctor() { }
}
```