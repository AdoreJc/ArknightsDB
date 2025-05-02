# RecruitSpecialGachaIntroDialog

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIRenderTextureImage _blurBkg`

- `Text _textTitle`

- `Text _textInfo`

- `RectTransform _backRt`


## Methods

- `Void EventOnBackBtnClicked()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaIntroDialog : UICompDialog`1, IHotfixable
{
	private UIRenderTextureImage _blurBkg; // 0x48
	private Text _textTitle; // 0x50
	private Text _textInfo; // 0x58
	private RectTransform _backRt; // 0x60
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2700cc8 VA: 0x7594d18cc8
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2700d30 VA: 0x7594d18d30
	protected override Void OnInit() { }
	// RVA: 0x2700e38 VA: 0x7594d18e38
	protected override Void OnRender(Options input) { }
	// RVA: 0x2700efc VA: 0x7594d18efc
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x2700fd0 VA: 0x7594d18fd0
	public Void .ctor() { }
	// RVA: 0x2701060 VA: 0x7594d19060
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2701068 VA: 0x7594d19068
	private Void <>xLuaBaseProxy_OnInit() { }
}
```