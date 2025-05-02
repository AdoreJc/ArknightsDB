# DIYPresetRenameState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `InputField _nameText`

- `UIRenderTextureImage _background`

- `DIYPresetRenameStateBean m_stateBean`


## Methods

- `Void _TryRenamePreset()`

- `Void OnCancelButtonPressed()`

- `Void OnOKButtonPressed()`

- `Void <_TryRenamePreset>b__4_0(ExaminResponse)`

- `Void <_TryRenamePreset>b__4_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYPresetRenameState : PopupFadeState
{
	private InputField _nameText; // 0x70
	private UIRenderTextureImage _background; // 0x78
	private DIYPresetRenameStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__TryRenamePreset; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_SetRootViewActive; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelButtonPressed; // 0x20
	private static DelegateBridge __Hotfix0_OnOKButtonPressed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3838138 VA: 0x7595e50138
	public override IStateBean GetCacheBean() { }
	// RVA: 0x38381a0 VA: 0x7595e501a0
	private Void _TryRenamePreset() { }
	// RVA: 0x3838374 VA: 0x7595e50374
	protected override Void OnEnter() { }
	// RVA: 0x383847c VA: 0x7595e5047c
	protected override Void SetRootViewActive(CanvasGroup rootView, Boolean active) { }
	// RVA: 0x38385cc VA: 0x7595e505cc
	public Void OnCancelButtonPressed() { }
	// RVA: 0x3838640 VA: 0x7595e50640
	public Void OnOKButtonPressed() { }
	// RVA: 0x38386a8 VA: 0x7595e506a8
	public Void .ctor() { }
	// RVA: 0x3838754 VA: 0x7595e50754
	private Void <_TryRenamePreset>b__4_0(ExaminResponse resp) { }
	// RVA: 0x38387e4 VA: 0x7595e507e4
	private Void <_TryRenamePreset>b__4_1() { }
	// RVA: 0x38387f4 VA: 0x7595e507f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x38387fc VA: 0x7595e507fc
	private Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup P0, Boolean P1) { }
}
```