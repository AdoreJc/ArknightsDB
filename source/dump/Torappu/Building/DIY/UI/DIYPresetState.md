# DIYPresetState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYListViewStateBean _stateBean`

- `DIYPresetPanel _panelPreset`

- `Int32 m_cachedRenameIndex`

- `String m_cachedPresetName`


## Methods

- `Void _ShowJudgeDialog(String, Action)`

- `Void _LoadPreset(Int32, IDIYPreset)`

- `Void _SavePreset(Int32, IDIYPreset)`

- `Void _RenamePreset(Int32, String)`

- `Void _OnSavePreset()`

- `Void _DataToSaveState(IStateBean)`

- `Void _DataToRenameState(IStateBean)`

- `Void OnBackButtonPressed()`

- `Void OnSaveButtonPressed()`

- `Void OnLoadButtonPressed()`

- `Void <_SavePreset>b__6_0(DIYPreset)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYPresetState : DIYPopupState
{
	private DIYListViewStateBean _stateBean; // 0x68
	private DIYPresetPanel _panelPreset; // 0x70
	private Int32 m_cachedRenameIndex; // 0x78
	private String m_cachedPresetName; // 0x80
	private static DelegateBridge __Hotfix0__ShowJudgeDialog; // 0x0
	private static DelegateBridge __Hotfix0__LoadPreset; // 0x8
	private static DelegateBridge __Hotfix0__SavePreset; // 0x10
	private static DelegateBridge __Hotfix0__RenamePreset; // 0x18
	private static DelegateBridge __Hotfix0__OnSavePreset; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0__DataToSaveState; // 0x48
	private static DelegateBridge __Hotfix0__DataToRenameState; // 0x50
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x58
	private static DelegateBridge __Hotfix0_OnBackButtonPressed; // 0x60
	private static DelegateBridge __Hotfix0_OnSaveButtonPressed; // 0x68
	private static DelegateBridge __Hotfix0_OnLoadButtonPressed; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x3838f0c VA: 0x7595e50f0c
	private Void _ShowJudgeDialog(String content, Action positiveAction) { }
	// RVA: 0x3839068 VA: 0x7595e51068
	private Void _LoadPreset(Int32 index, IDIYPreset preset) { }
	// RVA: 0x38390fc VA: 0x7595e510fc
	private Void _SavePreset(Int32 index, IDIYPreset preset) { }
	// RVA: 0x38391f0 VA: 0x7595e511f0
	private Void _RenamePreset(Int32 index, String presetName) { }
	// RVA: 0x383932c VA: 0x7595e5132c
	private Void _OnSavePreset() { }
	// RVA: 0x3839438 VA: 0x7595e51438
	protected override Void OnEnter() { }
	// RVA: 0x38395fc VA: 0x7595e515fc
	protected override Void OnResume() { }
	// RVA: 0x38396d0 VA: 0x7595e516d0
	protected override Void OnExit() { }
	// RVA: 0x383973c VA: 0x7595e5173c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3839930 VA: 0x7595e51930
	private Void _DataToSaveState(IStateBean stateBean) { }
	// RVA: 0x3839a7c VA: 0x7595e51a7c
	private Void _DataToRenameState(IStateBean stateBean) { }
	// RVA: 0x3839b64 VA: 0x7595e51b64
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3839bcc VA: 0x7595e51bcc
	public Void OnBackButtonPressed() { }
	// RVA: 0x3839c50 VA: 0x7595e51c50
	public Void OnSaveButtonPressed() { }
	// RVA: 0x3839cb8 VA: 0x7595e51cb8
	public Void OnLoadButtonPressed() { }
	// RVA: 0x3839d54 VA: 0x7595e51d54
	public Void .ctor() { }
	// RVA: 0x3839dc0 VA: 0x7595e51dc0
	private Void <_SavePreset>b__6_0(DIYPreset newPreset) { }
	// RVA: 0x3839e34 VA: 0x7595e51e34
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3839e3c VA: 0x7595e51e3c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3839e44 VA: 0x7595e51e44
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x3839e4c VA: 0x7595e51e4c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```