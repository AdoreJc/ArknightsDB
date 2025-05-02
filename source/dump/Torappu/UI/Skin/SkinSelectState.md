# SkinSelectState

**Namespace:** `Torappu.UI.Skin`


## Fields

- `SkinSelectStateBean _stateBean`

- `SkinSelectScrollView _view`

- `SkinPreviewPanel _previewPanelPrefab`

- `RectTransform _previewPanelRoot`

- `Boolean m_refreshDataFlag`

- `Boolean m_isThisStateEntered`

- `SkinPreviewPanel m_previewPanel`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _ChangeSkinSelectState(SkinSelectViewModel)`

- `Void _TryRefreshData()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _HandleSkinPreviewHide()`

- `Void _HandleSkinPreviewShow()`

- `Void _UpdateSkinIllustVisible()`

- `Void _HandleSkinStateChanged()`

- `Void EventOnBtnPreview()`

- `Void ChangeSelectState(SkinSelectViewModel)`

- `Void EventOnSkinBuyState(SkinSelectViewModel)`

- `Void <_ChangeSkinSelectState>b__12_0(ChangeCharSkinResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectState : State, IValueMsgReceiver
{
	private SkinSelectStateBean _stateBean; // 0x50
	private SkinSelectScrollView _view; // 0x58
	private SkinPreviewPanel _previewPanelPrefab; // 0x60
	private RectTransform _previewPanelRoot; // 0x68
	public const Int32 MSG_SKIN_STATE_CHANGED; // 0x0
	public const Int32 MSG_SKIN_PREVIEW_SHOW; // 0x0
	public const Int32 MSG_SKIN_PREVIEW_HIDE; // 0x0
	private Boolean m_refreshDataFlag; // 0x70
	private Boolean m_isThisStateEntered; // 0x71
	private SkinPreviewPanel m_previewPanel; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__ChangeSkinSelectState; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0__TryRefreshData; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge __Hotfix0_OnMessage; // 0x40
	private static DelegateBridge __Hotfix0__HandleSkinPreviewHide; // 0x48
	private static DelegateBridge __Hotfix0__HandleSkinPreviewShow; // 0x50
	private static DelegateBridge __Hotfix0__UpdateSkinIllustVisible; // 0x58
	private static DelegateBridge __Hotfix0__HandleSkinStateChanged; // 0x60
	private static DelegateBridge __Hotfix0_EventOnBtnPreview; // 0x68
	private static DelegateBridge __Hotfix0_ChangeSelectState; // 0x70
	private static DelegateBridge __Hotfix0_EventOnSkinBuyState; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x23d0e70 VA: 0x75949e8e70
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23d0ed8 VA: 0x75949e8ed8
	private Void _ChangeSkinSelectState(SkinSelectViewModel viewModel) { }
	// RVA: 0x23d1180 VA: 0x75949e9180
	protected override Void OnEnter() { }
	// RVA: 0x23d129c VA: 0x75949e929c
	protected override Void OnExit() { }
	// RVA: 0x23d1310 VA: 0x75949e9310
	protected override Void OnResume() { }
	// RVA: 0x23d1384 VA: 0x75949e9384
	private Void _TryRefreshData() { }
	// RVA: 0x23d148c VA: 0x75949e948c
	private Void OnEnable() { }
	// RVA: 0x23d14f4 VA: 0x75949e94f4
	private Void OnDisable() { }
	// RVA: 0x23d155c VA: 0x75949e955c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x23d17ec VA: 0x75949e97ec
	private Void _HandleSkinPreviewHide() { }
	// RVA: 0x23d1784 VA: 0x75949e9784
	private Void _HandleSkinPreviewShow() { }
	// RVA: 0x23d1854 VA: 0x75949e9854
	private Void _UpdateSkinIllustVisible() { }
	// RVA: 0x23d1640 VA: 0x75949e9640
	private Void _HandleSkinStateChanged() { }
	// RVA: 0x23d1abc VA: 0x75949e9abc
	public Void EventOnBtnPreview() { }
	// RVA: 0x23d20e0 VA: 0x75949ea0e0
	public Void ChangeSelectState(SkinSelectViewModel viewModel) { }
	// RVA: 0x23d2160 VA: 0x75949ea160
	public Void EventOnSkinBuyState(SkinSelectViewModel viewModel) { }
	// RVA: 0x23d2294 VA: 0x75949ea294
	public Void .ctor() { }
	// RVA: 0x23d2304 VA: 0x75949ea304
	private Void <_ChangeSkinSelectState>b__12_0(ChangeCharSkinResponse response) { }
	// RVA: 0x23d2334 VA: 0x75949ea334
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23d233c VA: 0x75949ea33c
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x23d2344 VA: 0x75949ea344
	private Void <>xLuaBaseProxy_OnResume() { }
}
```