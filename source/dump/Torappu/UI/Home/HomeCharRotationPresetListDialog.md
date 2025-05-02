# HomeCharRotationPresetListDialog

**Namespace:** `Torappu.UI.Home`


## Fields

- `UIRenderTextureImage _blurBkg`

- `HomeCharRotationPresetListView _view`

- `HomeCharRotationPresetListViewProperty m_property`

- `Boolean m_inited`

- `Boolean m_isHiding`

- `String m_appliedPreset`


## Methods

- `Void _InitIfNot()`

- `Void _OnBtnNameClick(String)`

- `Void _OnBtnDeleteClick(String)`

- `Void _OnBtnEditClick(String)`

- `Void _OnBtnApplyClick(String)`

- `Void _OnBtnCreatePresetClick()`

- `Void EventOnBackBtnClicked()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetListDialog : UICompDialog`1, IHotfixable
{
	private const Int32 PRESET_NAME_INPUT_MAX_COUNT; // 0x0
	private UIRenderTextureImage _blurBkg; // 0x48
	private HomeCharRotationPresetListView _view; // 0x50
	private HomeCharRotationPresetListViewProperty m_property; // 0x58
	private Boolean m_inited; // 0x60
	private Boolean m_isHiding; // 0x61
	private String m_appliedPreset; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0__OnBtnNameClick; // 0x20
	private static DelegateBridge __Hotfix0__OnBtnDeleteClick; // 0x28
	private static DelegateBridge __Hotfix0__OnBtnEditClick; // 0x30
	private static DelegateBridge __Hotfix0__OnBtnApplyClick; // 0x38
	private static DelegateBridge __Hotfix0__OnBtnCreatePresetClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x27dcc80 VA: 0x7594df4c80
	private Void _InitIfNot() { }
	// RVA: 0x27dd15c VA: 0x7594df515c
	protected override Void OnInit() { }
	// RVA: 0x27dd1d0 VA: 0x7594df51d0
	protected override Void OnRender(Options input) { }
	// RVA: 0x27dd6b0 VA: 0x7594df56b0
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x27dd718 VA: 0x7594df5718
	private Void _OnBtnNameClick(String presetInstId) { }
	// RVA: 0x27ddaa8 VA: 0x7594df5aa8
	private Void _OnBtnDeleteClick(String presetInstId) { }
	// RVA: 0x27ddd24 VA: 0x7594df5d24
	private Void _OnBtnEditClick(String presetInstId) { }
	// RVA: 0x27dde4c VA: 0x7594df5e4c
	private Void _OnBtnApplyClick(String presetInstId) { }
	// RVA: 0x27de12c VA: 0x7594df612c
	private Void _OnBtnCreatePresetClick() { }
	// RVA: 0x27de3bc VA: 0x7594df63bc
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x27de494 VA: 0x7594df6494
	public Void .ctor() { }
	// RVA: 0x27de5cc VA: 0x7594df65cc
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x27de5d4 VA: 0x7594df65d4
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```