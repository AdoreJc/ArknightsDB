# QCShopLowViewGroup

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _lockedPart`

- `QCNormalGoodItem _item`

- `CanvasGroup _lockedCanvas`

- `Single _alphaLocked`

- `SimpleLayoutContent _container`

- `String cacheGroupId`

- `SpriteHub m_priceTypeHub`

- `QCShopLowGroup m_cachedShopGroup`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void InitGroupData(QCShopLowGroup)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopLowViewGroup : MonoBehaviour, IHotfixable
{
	private GameObject _lockedPart; // 0x18
	private QCNormalGoodItem _item; // 0x20
	private CanvasGroup _lockedCanvas; // 0x28
	private Single _alphaLocked; // 0x30
	private SimpleLayoutContent _container; // 0x38
	public String cacheGroupId; // 0x40
	private SpriteHub m_priceTypeHub; // 0x48
	private QCShopLowGroup m_cachedShopGroup; // 0x50
	private Adapter m_adapter; // 0x58
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0_InitGroupData; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2458080 VA: 0x7594a70080
	public Void InitGroupData(QCShopLowGroup shopGroup) { }
	// RVA: 0x2458678 VA: 0x7594a70678
	private Void _InitIfNot() { }
	// RVA: 0x24587dc VA: 0x7594a707dc
	public Void .ctor() { }
}
```