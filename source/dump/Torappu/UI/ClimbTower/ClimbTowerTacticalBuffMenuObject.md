# ClimbTowerTacticalBuffMenuObject

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _panelFloat`

- `SimpleLayoutContent _buffList`

- `CanvasGroup _canvasNormal`

- `CanvasGroup _canvasSelected`

- `RectTransform _backBtn`

- `ShowSwitchTween m_switchTween`

- `ClimbTowerInnerBuffListModel m_cachedModel`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void SetShow(Boolean)`

- `Void Toggle()`

- `Void <_InitIfNot>b__11_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTacticalBuffMenuObject : ClimbTowerMenuObject
{
	private GameObject _panelFloat; // 0x20
	private SimpleLayoutContent _buffList; // 0x28
	private CanvasGroup _canvasNormal; // 0x30
	private CanvasGroup _canvasSelected; // 0x38
	private RectTransform _backBtn; // 0x40
	private ShowSwitchTween m_switchTween; // 0x48
	private ClimbTowerInnerBuffListModel m_cachedModel; // 0x50
	private Adapter m_adapter; // 0x58
	private Boolean m_hasInited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_SetShow; // 0x10
	private static DelegateBridge __Hotfix0_Toggle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c86624 VA: 0x759529e624
	private Void _InitIfNot() { }
	// RVA: 0x2c86960 VA: 0x759529e960
	public override Void Render(ClimbTowerMenuViewModel viewModel) { }
	// RVA: 0x2c86a18 VA: 0x759529ea18
	public Void SetShow(Boolean show) { }
	// RVA: 0x2c86b9c VA: 0x759529eb9c
	public Void Toggle() { }
	// RVA: 0x2c86d1c VA: 0x759529ed1c
	public Void .ctor() { }
	// RVA: 0x2c86d8c VA: 0x759529ed8c
	private Void <_InitIfNot>b__11_0() { }
}
```