# SandboxV2ExpeditionEnsureView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _duration`

- `Text _drink`

- `Text _drinkObtain`

- `Text _costAction`

- `CanvasGroup _noDrink`

- `GameObject _panelCostAction`

- `UIAtlasImage _startBtnBkg`

- `Color _colorDisable`

- `Color _colorEnable`

- `SimpleLayoutContent _content`

- `Image _drinkIcon`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `FadeSwitchTween m_noDrinkSwitchTween`

- `UIStateFinder m_stateFinder`

- `SandboxV2CharListViewModel m_cachedViewModel`


## Methods

- `Void OnClick()`

- `Void OnClear()`

- `Void OnProduceDrink()`

- `Void _InitIfNot()`

- `Void _LoadIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ExpeditionEnsureView : SandboxV2AdminCharAbstractEnsureView
{
	private Text _duration; // 0x18
	private Text _drink; // 0x20
	private Text _drinkObtain; // 0x28
	private Text _costAction; // 0x30
	private CanvasGroup _noDrink; // 0x38
	private GameObject _panelCostAction; // 0x40
	private UIAtlasImage _startBtnBkg; // 0x48
	private Color _colorDisable; // 0x50
	private Color _colorEnable; // 0x60
	private SimpleLayoutContent _content; // 0x70
	private Image _drinkIcon; // 0x78
	private Boolean m_isInited; // 0x80
	private Adapter m_adapter; // 0x88
	private FadeSwitchTween m_noDrinkSwitchTween; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private SandboxV2CharListViewModel m_cachedViewModel; // 0xa8
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_OnClear; // 0x8
	private static DelegateBridge __Hotfix0_OnProduceDrink; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdateData; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__LoadIcon; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2488414 VA: 0x7594aa0414
	public Void OnClick() { }
	// RVA: 0x248861c VA: 0x7594aa061c
	public Void OnClear() { }
	// RVA: 0x24886d0 VA: 0x7594aa06d0
	public Void OnProduceDrink() { }
	// RVA: 0x2488784 VA: 0x7594aa0784
	public override Void OnUpdateData(SandboxV2CharListViewModel viewModel) { }
	// RVA: 0x2488a5c VA: 0x7594aa0a5c
	private Void _InitIfNot() { }
	// RVA: 0x2488b94 VA: 0x7594aa0b94
	private Void _LoadIcon(String topicId) { }
	// RVA: 0x2488d34 VA: 0x7594aa0d34
	public Void .ctor() { }
}
```