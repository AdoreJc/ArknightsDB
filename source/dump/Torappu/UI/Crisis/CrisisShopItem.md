# CrisisShopItem

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `Image _backImage`

- `Text _displayName`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `GameObject _tagPart`

- `GameObject _remasterPart`

- `Image _seasonPart`

- `Text _priceText`

- `GameObject _alreadyHavePart`

- `GameObject _soldOutPart`

- `Transform _itemContainer`

- `Single _itemScale`

- `CanvasGroup _soldOutCanvasGroup`

- `Sprite _normalBack`

- `Sprite _progressBack`

- `Image _allBack`

- `GameObject _inActPart`

- `Image _shopIcon`

- `Sprite _crisisV1Icon`

- `Sprite _crisisV2Icon`

- `CrisisShopEvent clickEvent`

- `UIItemCard m_itemCard`

- `CrisisShopWrapped m_cacheViewModel`


## Methods

- `UIItemCard _EnsureItemCard()`

- `Void InitData(CrisisSeasonShopWrapped)`

- `Void InitData(CrisisLongTermShopWrapped)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopItem : MonoBehaviour, IHotfixable
{
	private Image _backImage; // 0x18
	private Text _displayName; // 0x20
	private Text _remainCount; // 0x28
	private GameObject _remainCountPart; // 0x30
	private GameObject _tagPart; // 0x38
	private GameObject _remasterPart; // 0x40
	private Image _seasonPart; // 0x48
	private Text _priceText; // 0x50
	private GameObject _alreadyHavePart; // 0x58
	private GameObject _soldOutPart; // 0x60
	private Transform _itemContainer; // 0x68
	private Single _itemScale; // 0x70
	private CanvasGroup _soldOutCanvasGroup; // 0x78
	private Sprite _normalBack; // 0x80
	private Sprite _progressBack; // 0x88
	private Image _allBack; // 0x90
	private GameObject _inActPart; // 0x98
	private Image _shopIcon; // 0xa0
	private Sprite _crisisV1Icon; // 0xa8
	private Sprite _crisisV2Icon; // 0xb0
	public CrisisShopEvent clickEvent; // 0xb8
	private UIItemCard m_itemCard; // 0xc0
	private CrisisShopWrapped m_cacheViewModel; // 0xc8
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix1_InitData; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c39420 VA: 0x7595251420
	private UIItemCard _EnsureItemCard() { }
	// RVA: 0x2c38cfc VA: 0x7595250cfc
	public Void InitData(CrisisSeasonShopWrapped shopViewModel) { }
	// RVA: 0x2c3829c VA: 0x759525029c
	public Void InitData(CrisisLongTermShopWrapped shopViewModel) { }
	// RVA: 0x2c395d4 VA: 0x75952515d4
	public Void OnClick() { }
	// RVA: 0x2c3966c VA: 0x759525166c
	public Void .ctor() { }
}
```