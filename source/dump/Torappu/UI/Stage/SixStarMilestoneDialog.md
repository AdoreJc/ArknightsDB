# SixStarMilestoneDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIRenderTextureImage _imgBlur`

- `RectTransform _backRect`

- `SixStarMilestoneView _view`

- `SixStarMilestoneProperty m_property`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBackClicked()`

- `Void _EventOnClaimAllClicked()`

- `Void _HandleClaimAllResponse(ConfirmSixStarRewardResponse)`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarMilestoneDialog : UICompDialog`1, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_BACK_BTN_CLICKED; // 0x0
	public const Int32 ON_CLAIM_ALL_BTN_CLICKED; // 0x0
	private UIRenderTextureImage _imgBlur; // 0x48
	private RectTransform _backRect; // 0x50
	private SixStarMilestoneView _view; // 0x58
	private SixStarMilestoneProperty m_property; // 0x60
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnClaimAllClicked; // 0x28
	private static DelegateBridge __Hotfix0__HandleClaimAllResponse; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2f49d6c VA: 0x7595561d6c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2f49dd4 VA: 0x7595561dd4
	protected override Void OnInit() { }
	// RVA: 0x2f49f04 VA: 0x7595561f04
	protected override Void OnRender(Input input) { }
	// RVA: 0x2f4a2c4 VA: 0x75955622c4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f4a384 VA: 0x7595562384
	private Void _EventOnBackClicked() { }
	// RVA: 0x2f4a458 VA: 0x7595562458
	private Void _EventOnClaimAllClicked() { }
	// RVA: 0x2f4a7a4 VA: 0x75955627a4
	private Void _HandleClaimAllResponse(ConfirmSixStarRewardResponse response) { }
	// RVA: 0x2f4aacc VA: 0x7595562acc
	public Void .ctor() { }
	// RVA: 0x2f4ac04 VA: 0x7595562c04
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2f4ac0c VA: 0x7595562c0c
	private Void <>xLuaBaseProxy_OnInit() { }
}
```