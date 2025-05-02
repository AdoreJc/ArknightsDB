# RecruitSpecialGachaUpCharListDialog

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIRenderTextureImage _blurBkg`

- `RecruitSpecialGachaUpCharListButtonView _buttonView`

- `RectTransform _backRt`

- `RecruitSpecialGachaUpCharListProperty m_property`

- `Int32 m_dialogInstId`

- `Int32 m_introDialogInstId`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _OnCharCardClicked(RarityRank)`

- `Void _EventOnConfirmBtnClicked()`

- `Void _EventOnBackBtnClicked()`

- `Void _EventOnIntroBtnClicked()`

- `Void _SendChoosePoolUpRequest()`

- `Void <_SendChoosePoolUpRequest>b__24_0(ChoosePoolUpResponse)`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharListDialog : UICompDialog`1, IValueMsgReceiver, ICompDialogCallBack, IHotfixable
{
	private const Int32 STAR_6_CHAR_COUNT; // 0x0
	private const Int32 STAR_5_CHAR_COUNT; // 0x0
	public const Int32 ON_CHAR_CARD_CLICKED; // 0x0
	public const Int32 ON_CONFIRM_BTN_CLICKED; // 0x0
	public const Int32 ON_CANCEL_BTN_CLICKED; // 0x0
	public const Int32 ON_INTRO_BTN_CLICKED; // 0x0
	private UIRenderTextureImage _blurBkg; // 0x48
	private RecruitSpecialGachaUpCharListGroupView[] _groupViewList; // 0x50
	private RecruitSpecialGachaUpCharListButtonView _buttonView; // 0x58
	private RectTransform _backRt; // 0x60
	private RecruitSpecialGachaUpCharListProperty m_property; // 0x68
	private Int32 m_dialogInstId; // 0x70
	private Int32 m_introDialogInstId; // 0x74
	private UIPageFinder m_pageFinder; // 0x78
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnConfirmBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__EventOnIntroBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__SendChoosePoolUpRequest; // 0x48
	private static DelegateBridge __Hotfix0__FormatToastCharName; // 0x50
	private static DelegateBridge __Hotfix0__LoadCharModelList; // 0x58
	private static DelegateBridge __Hotfix0__CompareCharModel; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x27015fc VA: 0x7594d195fc
	protected override Void OnInit() { }
	// RVA: 0x27017bc VA: 0x7594d197bc
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2701824 VA: 0x7594d19824
	protected override Void OnRender(Options input) { }
	// RVA: 0x2701e20 VA: 0x7594d19e20
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27027a8 VA: 0x7594d1a7a8
	public Void HandleCallBack(Int32 instId, ValueBundle outputBundle) { }
	// RVA: 0x2701f2c VA: 0x7594d19f2c
	private Void _OnCharCardClicked(RarityRank rank) { }
	// RVA: 0x27021a0 VA: 0x7594d1a1a0
	private Void _EventOnConfirmBtnClicked() { }
	// RVA: 0x27024dc VA: 0x7594d1a4dc
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x27025b0 VA: 0x7594d1a5b0
	private Void _EventOnIntroBtnClicked() { }
	// RVA: 0x27037f8 VA: 0x7594d1b7f8
	private Void _SendChoosePoolUpRequest() { }
	// RVA: 0x2703604 VA: 0x7594d1b604
	private static Void _FormatToastCharName(StringBuilder builder, List`1 charIdList, Int32 rarity) { }
	// RVA: 0x2702b74 VA: 0x7594d1ab74
	private static Boolean _LoadCharModelList(RarityRank rank, Dictionary`2 selectCharIdDict, Dictionary`2 charModelDict, out List`1 chooseModelList, out Int32 selectCount, out String titleText, out List`1 selectCharIdList) { }
	// RVA: 0x2703ad4 VA: 0x7594d1bad4
	private static Int32 _CompareCharModel(UIPortraitChooseCharCardViewModel left, UIPortraitChooseCharCardViewModel right) { }
	// RVA: 0x2703bec VA: 0x7594d1bbec
	public Void .ctor() { }
	// RVA: 0x2703d24 VA: 0x7594d1bd24
	private Void <_SendChoosePoolUpRequest>b__24_0(ChoosePoolUpResponse response) { }
	// RVA: 0x2703e14 VA: 0x7594d1be14
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2703e1c VA: 0x7594d1be1c
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```