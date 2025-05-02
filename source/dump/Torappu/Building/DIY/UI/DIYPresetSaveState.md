# DIYPresetSaveState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Image _presetView`

- `InputField _inputText`

- `UIRenderTextureImage _background`

- `DIYPresetDataSaveStateBean m_stateBean`


## Methods

- `Void _TrySavePreset()`

- `Void OnBackButtonPressed()`

- `Void OnConfirmPressed()`

- `Void <_TrySavePreset>b__5_0(DIYPreset)`

- `Void <_TrySavePreset>b__5_1(DIYPreset)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYPresetSaveState : PopupFadeState
{
	private Image _presetView; // 0x70
	private InputField _inputText; // 0x78
	private UIRenderTextureImage _background; // 0x80
	private DIYPresetDataSaveStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__TrySavePreset; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnBackButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0_OnConfirmPressed; // 0x20
	private static DelegateBridge __Hotfix0_SetRootViewActive; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3838878 VA: 0x7595e50878
	public override IStateBean GetCacheBean() { }
	// RVA: 0x38388e0 VA: 0x7595e508e0
	private Void _TrySavePreset() { }
	// RVA: 0x3838a90 VA: 0x7595e50a90
	protected override Void OnEnter() { }
	// RVA: 0x3838c00 VA: 0x7595e50c00
	public Void OnBackButtonPressed() { }
	// RVA: 0x3838c74 VA: 0x7595e50c74
	public Void OnConfirmPressed() { }
	// RVA: 0x3838cdc VA: 0x7595e50cdc
	protected override Void SetRootViewActive(CanvasGroup rootView, Boolean active) { }
	// RVA: 0x3838e2c VA: 0x7595e50e2c
	public Void .ctor() { }
	// RVA: 0x3838ed8 VA: 0x7595e50ed8
	private Void <_TrySavePreset>b__5_0(DIYPreset newPreset) { }
	// RVA: 0x3838ee8 VA: 0x7595e50ee8
	private Void <_TrySavePreset>b__5_1(DIYPreset newPreset) { }
	// RVA: 0x3838ef8 VA: 0x7595e50ef8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3838f00 VA: 0x7595e50f00
	private Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup P0, Boolean P1) { }
}
```