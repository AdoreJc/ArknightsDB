# HotUpdatePreMainView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `IContext m_context`

- `Assets m_assets`

- `PreMainState m_currentState`

- `FadeSwitchTween m_picSwitchTween`

- `Boolean m_isInited`


## Properties

- `PreMainState currentState`


## Methods

- `PreMainState get_currentState()`

- `Void SetContext(IContext)`

- `Void SetAssets(Assets)`

- `Void InitHide()`

- `Void OnClear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdatePreMainView : DataBinder`1
{
	private List`1 _preMainList; // 0x20
	private List`1 _backImgList; // 0x28
	private IContext m_context; // 0x30
	private Assets m_assets; // 0x38
	private PreMainState m_currentState; // 0x40
	private FadeSwitchTween m_picSwitchTween; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_get_currentState; // 0x0
	private static DelegateBridge __Hotfix0_SetContext; // 0x8
	private static DelegateBridge __Hotfix0_SetAssets; // 0x10
	private static DelegateBridge __Hotfix0_InitHide; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnClear; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public PreMainState currentState { get; }

	// RVA: 0x27cb87c VA: 0x7594de387c
	public PreMainState get_currentState() { }
	// RVA: 0x27cb3a0 VA: 0x7594de33a0
	public Void SetContext(IContext context) { }
	// RVA: 0x27cb48c VA: 0x7594de348c
	public Void SetAssets(Assets assets) { }
	// RVA: 0x27cb510 VA: 0x7594de3510
	public Void InitHide() { }
	// RVA: 0x27cb8e4 VA: 0x7594de38e4
	public override Void OnValueChanged(HotUpdatePreMainProperty property) { }
	// RVA: 0x27cba84 VA: 0x7594de3a84
	public Void OnClear() { }
	// RVA: 0x27cbb4c VA: 0x7594de3b4c
	public Void .ctor() { }
}
```