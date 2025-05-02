# SixStarRuneSelectDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIRenderTextureImage _imgBlur`

- `SixStarRuneSelectView _runeSelectView`

- `RectTransform _rectBack`

- `SixStarRuneSelectProperty m_property`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedDialogInstId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnConfirmBtnClicked()`

- `Void _EventOnRuneSelect(Int32, String)`

- `Void _EventOnMilestoneBtnClicked()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _HandleSelectRuneResponse(EditStageSixStarTagResponse)`

- `Void EventOnBackClicked()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnResumeFromStack()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectDialog : UICompDialog`1, IValueMsgReceiver, ICompDialogCallBack, IHotfixable
{
	public const Int32 ON_CONFIRM_BTN_CLICKED; // 0x0
	public const Int32 ON_RUNE_SELECT; // 0x0
	public const Int32 ON_MILESTONE_BTN_CLICKED; // 0x0
	public const Int32 SHOW_NEXT_REWARD_TIP_POINT; // 0x0
	private UIRenderTextureImage _imgBlur; // 0x48
	private SixStarRuneSelectView _runeSelectView; // 0x50
	private RectTransform _rectBack; // 0x58
	private SixStarRuneSelectProperty m_property; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private Int32 m_cachedDialogInstId; // 0x78
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnResumeFromStack; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__EventOnConfirmBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnRuneSelect; // 0x30
	private static DelegateBridge __Hotfix0__EventOnMilestoneBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x40
	private static DelegateBridge __Hotfix0__HandleSelectRuneResponse; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2f4d7bc VA: 0x75955657bc
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2f4d824 VA: 0x7595565824
	protected override Void OnInit() { }
	// RVA: 0x2f4d954 VA: 0x7595565954
	protected override Void OnRender(Input input) { }
	// RVA: 0x2f4e24c VA: 0x759556624c
	protected override Void OnResumeFromStack() { }
	// RVA: 0x2f4e5dc VA: 0x75955665dc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f4e6c4 VA: 0x75955666c4
	private Void _EventOnConfirmBtnClicked() { }
	// RVA: 0x2f4ea7c VA: 0x7595566a7c
	private Void _EventOnRuneSelect(Int32 level, String runeId) { }
	// RVA: 0x2f4ed14 VA: 0x7595566d14
	private Void _EventOnMilestoneBtnClicked() { }
	// RVA: 0x2f4f1f4 VA: 0x75955671f4
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2f4f2e0 VA: 0x75955672e0
	private Void _HandleSelectRuneResponse(EditStageSixStarTagResponse _) { }
	// RVA: 0x2f4f3c8 VA: 0x75955673c8
	public Void EventOnBackClicked() { }
	// RVA: 0x2f4f49c VA: 0x759556749c
	public Void .ctor() { }
	// RVA: 0x2f4f5d4 VA: 0x75955675d4
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2f4f5dc VA: 0x75955675dc
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2f4f5e4 VA: 0x75955675e4
	private Void <>xLuaBaseProxy_OnResumeFromStack() { }
}
```