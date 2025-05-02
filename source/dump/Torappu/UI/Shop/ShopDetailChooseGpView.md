# ShopDetailChooseGpView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SimpleLayoutContent _gpItemList`

- `UIOptionEvent _findDetailAction`

- `Image _spriteImage`

- `Text _detailText`

- `Text _itemText`

- `Text _itemCount`

- `GameObject _panelRemain`

- `Text _remainCount`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `DetailChooseGPViewModel m_cacheChooseViewModel`


## Methods

- `Void _InitIfNot()`

- `Void OnGetDetail(Int32)`

- `Void RefreshIndexInfo(Int32)`

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailChooseGpView : ShopDetailCommonView, IHotfixable
{
	private const Int32 UNSELECT_INDEX; // 0x0
	private SimpleLayoutContent _gpItemList; // 0xa8
	private UIOptionEvent _findDetailAction; // 0xb0
	private Image _spriteImage; // 0xb8
	private Text _detailText; // 0xc0
	private Text _itemText; // 0xc8
	private Text _itemCount; // 0xd0
	private GameObject _panelRemain; // 0xd8
	private Text _remainCount; // 0xe0
	private Adapter m_adapter; // 0xe8
	private Boolean m_isInited; // 0xf0
	private DetailChooseGPViewModel m_cacheChooseViewModel; // 0xf8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0_OnGetDetail; // 0x10
	private static DelegateBridge __Hotfix0_RefreshIndexInfo; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2430878 VA: 0x7594a48878
	private Void _InitIfNot() { }
	// RVA: 0x24309bc VA: 0x7594a489bc
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x2430f94 VA: 0x7594a48f94
	public Void OnGetDetail(Int32 indexId) { }
	// RVA: 0x2430d18 VA: 0x7594a48d18
	public Void RefreshIndexInfo(Int32 indexId) { }
	// RVA: 0x2431078 VA: 0x7594a49078
	public override Void OnClick() { }
	// RVA: 0x24311f0 VA: 0x7594a491f0
	public Void .ctor() { }
	// RVA: 0x243125c VA: 0x7594a4925c
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
	// RVA: 0x2431260 VA: 0x7594a49260
	private Void <>xLuaBaseProxy_OnClick() { }
}
```