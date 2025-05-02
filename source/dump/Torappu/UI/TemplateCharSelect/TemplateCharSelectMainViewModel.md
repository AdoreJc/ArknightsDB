# TemplateCharSelectMainViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect`


## Fields

- `TemplateCharSelectMainViewModelSetupData <setupParam>k__BackingField`

- `TemplateCharSelectPoolViewModel <poolViewModel>k__BackingField`

- `TemplateCharSelectShuffleViewModel <shuffleViewModel>k__BackingField`

- `TemplateCharSelectDetailViewModel <detailViewModel>k__BackingField`

- `InputParam <cacheInput>k__BackingField`

- `Boolean ensured`


## Properties

- `TemplateCharSelectMainViewModelSetupData setupParam`

- `TemplateCharSelectPoolViewModel poolViewModel`

- `TemplateCharSelectShuffleViewModel shuffleViewModel`

- `TemplateCharSelectDetailViewModel detailViewModel`

- `InputParam cacheInput`

- `TemplateCharSelectMode mode`


## Methods

- `TemplateCharSelectMainViewModelSetupData get_setupParam()`

- `Void set_setupParam(TemplateCharSelectMainViewModelSetupData)`

- `TemplateCharSelectPoolViewModel get_poolViewModel()`

- `Void set_poolViewModel(TemplateCharSelectPoolViewModel)`

- `TemplateCharSelectShuffleViewModel get_shuffleViewModel()`

- `Void set_shuffleViewModel(TemplateCharSelectShuffleViewModel)`

- `TemplateCharSelectDetailViewModel get_detailViewModel()`

- `Void set_detailViewModel(TemplateCharSelectDetailViewModel)`

- `InputParam get_cacheInput()`

- `Void set_cacheInput(InputParam)`

- `TemplateCharSelectMode get_mode()`

- `Void Setup(TemplateCharSelectMainViewModelSetupData)`

- `Void TriggerResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect
public class TemplateCharSelectMainViewModel : IHotfixable
{
	private TemplateCharSelectMainViewModelSetupData <setupParam>k__BackingField; // 0x10
	private TemplateCharSelectPoolViewModel <poolViewModel>k__BackingField; // 0x38
	private TemplateCharSelectShuffleViewModel <shuffleViewModel>k__BackingField; // 0x40
	private TemplateCharSelectDetailViewModel <detailViewModel>k__BackingField; // 0x48
	private InputParam <cacheInput>k__BackingField; // 0x50
	public Boolean ensured; // 0x58
	private static DelegateBridge __Hotfix0_get_setupParam; // 0x0
	private static DelegateBridge __Hotfix0_set_setupParam; // 0x8
	private static DelegateBridge __Hotfix0_get_poolViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_poolViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_shuffleViewModel; // 0x20
	private static DelegateBridge __Hotfix0_set_shuffleViewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_detailViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_detailViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_cacheInput; // 0x40
	private static DelegateBridge __Hotfix0_set_cacheInput; // 0x48
	private static DelegateBridge __Hotfix0_get_selectedList; // 0x50
	private static DelegateBridge __Hotfix0_get_mode; // 0x58
	private static DelegateBridge __Hotfix0_Setup; // 0x60
	private static DelegateBridge __Hotfix0_ResetByInput; // 0x68
	private static DelegateBridge __Hotfix0_TriggerResume; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public TemplateCharSelectMainViewModelSetupData setupParam { get; set; }
	public TemplateCharSelectPoolViewModel poolViewModel { get; set; }
	public TemplateCharSelectShuffleViewModel shuffleViewModel { get; set; }
	public TemplateCharSelectDetailViewModel detailViewModel { get; set; }
	public InputParam cacheInput { get; set; }
	public List`1 selectedList { get; }
	public TemplateCharSelectMode mode { get; }

	// RVA: 0x2c4ef24 VA: 0x7595266f24
	public TemplateCharSelectMainViewModelSetupData get_setupParam() { }
	// RVA: 0x2c4efc0 VA: 0x7595266fc0
	private Void set_setupParam(TemplateCharSelectMainViewModelSetupData value) { }
	// RVA: 0x2c4e23c VA: 0x759526623c
	public TemplateCharSelectPoolViewModel get_poolViewModel() { }
	// RVA: 0x2c4f070 VA: 0x7595267070
	private Void set_poolViewModel(TemplateCharSelectPoolViewModel value) { }
	// RVA: 0x2c4e8a8 VA: 0x75952668a8
	public TemplateCharSelectShuffleViewModel get_shuffleViewModel() { }
	// RVA: 0x2c4f0f4 VA: 0x75952670f4
	private Void set_shuffleViewModel(TemplateCharSelectShuffleViewModel value) { }
	// RVA: 0x2c4c678 VA: 0x7595264678
	public TemplateCharSelectDetailViewModel get_detailViewModel() { }
	// RVA: 0x2c4f178 VA: 0x7595267178
	private Void set_detailViewModel(TemplateCharSelectDetailViewModel value) { }
	// RVA: 0x2c4f1fc VA: 0x75952671fc
	public InputParam get_cacheInput() { }
	// RVA: 0x2c4f264 VA: 0x7595267264
	private Void set_cacheInput(InputParam value) { }
	// RVA: 0x2c4f2e8 VA: 0x75952672e8
	public List`1 get_selectedList() { }
	// RVA: 0x2c4f364 VA: 0x7595267364
	public TemplateCharSelectMode get_mode() { }
	// RVA: 0x2c4f3dc VA: 0x75952673dc
	public Void Setup(TemplateCharSelectMainViewModelSetupData setup) { }
	// RVA: 0x2c4f520 VA: 0x7595267520
	public virtual Void ResetByInput(InputParam param) { }
	// RVA: 0x2c4d414 VA: 0x7595265414
	public Void TriggerResume() { }
	// RVA: 0x2c4f73c VA: 0x759526773c
	public Void .ctor() { }
}
```