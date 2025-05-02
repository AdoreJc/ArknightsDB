# SDKPopupStateShopAgreement

**Namespace:** `YostarSDK.UI`


## Fields

- `SimpleLayoutContent _textContainer`

- `ContentAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnBlankClicked()`

- `Void _ShowAgreement()`

- `Void _GetShopAgreementCallback(GetShopAgreementRet)`

- `Void <_GetShopAgreementCallback>b__16_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPopupStateShopAgreement : UIState
{
	private const Int32 MAX_TEXT_STRLEN; // 0x0
	private const Int32 MIN_TEXT_STRLEN; // 0x0
	private SimpleLayoutContent _textContainer; // 0x50
	private List`1 m_content; // 0x58
	private ContentAdapter m_adapter; // 0x60
	private Boolean m_isInited; // 0x68
	private Nullable`1 m_shopAgreeType; // 0x6c
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_myState; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x18
	private static DelegateBridge __Hotfix0__DealWithTitleStyle; // 0x20
	private static DelegateBridge __Hotfix0__DealWithContentStyle; // 0x28
	private static DelegateBridge __Hotfix0__ShowAgreement; // 0x30
	private static DelegateBridge __Hotfix0__GetShopAgreementCallback; // 0x38
	private static DelegateBridge __Hotfix0__ExtractAgreementContent; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override PopupState myState { get; }

	// RVA: 0x257894c VA: 0x7594b9094c
	private Void _InitIfNot() { }
	// RVA: 0x2578ab0 VA: 0x7594b90ab0
	public override PopupState get_myState() { }
	// RVA: 0x2578b18 VA: 0x7594b90b18
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2578e00 VA: 0x7594b90e00
	public Void EventOnBlankClicked() { }
	// RVA: 0x2578e8c VA: 0x7594b90e8c
	private static Void _DealWithTitleStyle(Text text) { }
	// RVA: 0x2578f14 VA: 0x7594b90f14
	private static Void _DealWithContentStyle(Text text) { }
	// RVA: 0x2578c88 VA: 0x7594b90c88
	private Void _ShowAgreement() { }
	// RVA: 0x2578f9c VA: 0x7594b90f9c
	private Void _GetShopAgreementCallback(GetShopAgreementRet ret) { }
	// RVA: 0x257915c VA: 0x7594b9115c
	private static String _ExtractAgreementContent(GetShopAgreementRet ret) { }
	// RVA: 0x257972c VA: 0x7594b9172c
	public Void .ctor() { }
	// RVA: 0x2579798 VA: 0x7594b91798
	private Void <_GetShopAgreementCallback>b__16_0() { }
	// RVA: 0x25797b0 VA: 0x7594b917b0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```