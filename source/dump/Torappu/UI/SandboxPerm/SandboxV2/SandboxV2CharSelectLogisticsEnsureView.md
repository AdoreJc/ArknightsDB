# SandboxV2CharSelectLogisticsEnsureView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _txtDuration`

- `Text _txtDrink`

- `Text _txtDrinkCapacity`

- `Text _txtPopulation`

- `Text _txtTotalPopulation`

- `Image _imgDrinkIcon`

- `CanvasGroup _canvasGroupNoDrink`

- `Boolean m_isInited`

- `FadeSwitchTween m_noDrinkSwitchTween`

- `UIStateFinder m_stateFinder`

- `SandboxV2CharListViewModel m_cachedViewModel`


## Methods

- `Void OnClick()`

- `Void OnClear()`

- `Void OnProduceDrink()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectLogisticsEnsureView : SandboxV2AdminCharAbstractEnsureView
{
	private const String FORMAT_TOTAL_POPULATION; // 0x0
	private Text _txtDuration; // 0x18
	private Text _txtDrink; // 0x20
	private Text _txtDrinkCapacity; // 0x28
	private Text _txtPopulation; // 0x30
	private Text _txtTotalPopulation; // 0x38
	private Image _imgDrinkIcon; // 0x40
	private CanvasGroup _canvasGroupNoDrink; // 0x48
	private Boolean m_isInited; // 0x50
	private FadeSwitchTween m_noDrinkSwitchTween; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private SandboxV2CharListViewModel m_cachedViewModel; // 0x70
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_OnClear; // 0x8
	private static DelegateBridge __Hotfix0_OnProduceDrink; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdateData; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2482c5c VA: 0x7594a9ac5c
	public Void OnClick() { }
	// RVA: 0x2482d2c VA: 0x7594a9ad2c
	public Void OnClear() { }
	// RVA: 0x2482de0 VA: 0x7594a9ade0
	public Void OnProduceDrink() { }
	// RVA: 0x2482e94 VA: 0x7594a9ae94
	public override Void OnUpdateData(SandboxV2CharListViewModel viewModel) { }
	// RVA: 0x2483140 VA: 0x7594a9b140
	private Void _InitIfNot() { }
	// RVA: 0x2483224 VA: 0x7594a9b224
	public Void .ctor() { }
}
```