# Act25sideMapDecorMissionPlugin

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `CanvasGroup _canvasBtnNormal`

- `CanvasGroup _canvasBtnSelected`

- `Text _textBtn`

- `Color _colorBtnNormal`

- `Color _colorBtnSelected`

- `Single _tweenDuration`

- `GameObject _fullscreenRaycast`

- `SimpleLayoutContent _missionGroupView`

- `CanvasGroup _canvasMissionGroup`

- `RectTransform _posHandler`

- `Single _posHide`

- `Single _posShow`

- `GameObject _pnlButton`

- `SwitchTween m_showSwitchTween`

- `Boolean m_inited`

- `Adapter m_adapter`

- `Boolean m_cachedValid`


## Methods

- `Void _InitIfNot()`

- `Void OnButtonClicked()`

- `Void OnCloseButtonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideMapDecorMissionPlugin : TemplateActivityCommonPlugin
{
	private CanvasGroup _canvasBtnNormal; // 0x28
	private CanvasGroup _canvasBtnSelected; // 0x30
	private Text _textBtn; // 0x38
	private Color _colorBtnNormal; // 0x40
	private Color _colorBtnSelected; // 0x50
	private Single _tweenDuration; // 0x60
	private GameObject _fullscreenRaycast; // 0x68
	private SimpleLayoutContent _missionGroupView; // 0x70
	private CanvasGroup _canvasMissionGroup; // 0x78
	private RectTransform _posHandler; // 0x80
	private Single _posHide; // 0x88
	private Single _posShow; // 0x8c
	private GameObject _pnlButton; // 0x90
	private SwitchTween m_showSwitchTween; // 0x98
	private Boolean m_inited; // 0xa0
	private List`1 m_cachedMissionGroup; // 0xa8
	private Adapter m_adapter; // 0xb0
	private Boolean m_cachedValid; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_OnButtonClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnCloseButtonClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32710f0 VA: 0x75958890f0
	private Void _InitIfNot() { }
	// RVA: 0x3271350 VA: 0x7595889350
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3271530 VA: 0x7595889530
	public Void OnButtonClicked() { }
	// RVA: 0x32715d0 VA: 0x75958895d0
	public Void OnCloseButtonClicked() { }
	// RVA: 0x327165c VA: 0x759588965c
	public Void .ctor() { }
}
```