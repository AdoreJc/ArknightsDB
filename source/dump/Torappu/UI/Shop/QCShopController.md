# QCShopController

**Namespace:** `Torappu.UI.Shop`


## Fields

- `UIQCShopEvent _clickEvent`

- `QCShopHighView _highView`

- `QCShopLowView _lowView`

- `QCShopClassicView _classicView`

- `QCShopExtraView _extraView`

- `QCShopREPView _repView`

- `QCShopLMTGSView m_sLMTGSView`

- `QCShopEPGSView m_sEPGSView`

- `Transform _sLMTGSContainer`

- `Transform _sEPGSContainer`

- `Transform _sLMTGSButtonContainer`

- `Transform _sEPGSButtonContainer`

- `GameObject _qcDetail`

- `GameObject _limitDetail`

- `GameObject _extraQCDetail`

- `GameObject _repQCDetail`

- `GameObject _classicDetail`

- `GameObject _classicLeftButton`

- `Transform _limitDetailButtonContainer`

- `Button m_limitDetailButton`

- `LMTGSControllerButton m_button`

- `QCShopDetailShopEnum m_currentState`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot(ShopPage)`

- `Void _DealWithQCResponse(IQCShopGetResponse)`

- `Void RefreshData(ShopPage)`

- `Void ApplyQCState(QCShopDetailShopEnum, ShopPage, UnityAction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopController : MonoBehaviour, IHotfixable
{
	private UIQCShopEvent _clickEvent; // 0x18
	private List`1 _objList; // 0x20
	private QCShopHighView _highView; // 0x28
	private QCShopLowView _lowView; // 0x30
	private QCShopClassicView _classicView; // 0x38
	private QCShopExtraView _extraView; // 0x40
	private QCShopREPView _repView; // 0x48
	private QCShopLMTGSView m_sLMTGSView; // 0x50
	private QCShopEPGSView m_sEPGSView; // 0x58
	private Transform _sLMTGSContainer; // 0x60
	private Transform _sEPGSContainer; // 0x68
	private Transform _sLMTGSButtonContainer; // 0x70
	private Transform _sEPGSButtonContainer; // 0x78
	private GameObject _qcDetail; // 0x80
	private GameObject _limitDetail; // 0x88
	private GameObject _extraQCDetail; // 0x90
	private GameObject _repQCDetail; // 0x98
	private GameObject _classicDetail; // 0xa0
	private GameObject _classicLeftButton; // 0xa8
	private Transform _limitDetailButtonContainer; // 0xb0
	private Button m_limitDetailButton; // 0xb8
	private LMTGSControllerButton m_button; // 0xc0
	private List`1 m_objList; // 0xc8
	private const QCShopDetailShopEnum DEFAULT_STATE; // 0x0
	private QCShopDetailShopEnum m_currentState; // 0xd0
	private Boolean m_isInited; // 0xd4
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__DealWithQCResponse; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyQCState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2450438 VA: 0x7594a68438
	private Void _InitIfNot(ShopPage page) { }
	// RVA: 0x2450c08 VA: 0x7594a68c08
	private Void _DealWithQCResponse(IQCShopGetResponse response) { }
	// RVA: 0x2450e58 VA: 0x7594a68e58
	public Void RefreshData(ShopPage page) { }
	// RVA: 0x24519c0 VA: 0x7594a699c0
	public Void ApplyQCState(QCShopDetailShopEnum detailState, ShopPage page, UnityAction detailCick) { }
	// RVA: 0x2452068 VA: 0x7594a6a068
	public Void .ctor() { }
}
```