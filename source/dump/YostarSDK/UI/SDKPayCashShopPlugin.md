# SDKPayCashShopPlugin

**Namespace:** `YostarSDK.UI`


## Fields

- `GameObject _btnAgreementOne`

- `GameObject _btnAgreementTwo`

- `Text _textDesc`

- `Text _textBtnOne`

- `Text _textBtnTwo`

- `YostarSDK m_sdk`


## Methods

- `Void Init(YostarSDK)`

- `Void EventOnAgreement1()`

- `Void EventOnAgreement2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPayCashShopPlugin : MonoBehaviour, IHotfixable
{
	private GameObject _btnAgreementOne; // 0x18
	private GameObject _btnAgreementTwo; // 0x20
	private Text _textDesc; // 0x28
	private Text _textBtnOne; // 0x30
	private Text _textBtnTwo; // 0x38
	private YostarSDK m_sdk; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_EventOnAgreement1; // 0x8
	private static DelegateBridge __Hotfix0_EventOnAgreement2; // 0x10
	private static DelegateBridge __Hotfix0__GetShopType1; // 0x18
	private static DelegateBridge __Hotfix0__GetShopType2; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b40e60 VA: 0x7594158e60
	public Void Init(YostarSDK sdk) { }
	// RVA: 0x1b4aca4 VA: 0x7594162ca4
	public Void EventOnAgreement1() { }
	// RVA: 0x1b4adcc VA: 0x7594162dcc
	public Void EventOnAgreement2() { }
	// RVA: 0x1b4ad38 VA: 0x7594162d38
	private static ShopAgreementType _GetShopType1() { }
	// RVA: 0x1b4ae60 VA: 0x7594162e60
	private static ShopAgreementType _GetShopType2() { }
	// RVA: 0x1b4aef4 VA: 0x7594162ef4
	public Void .ctor() { }
}
```