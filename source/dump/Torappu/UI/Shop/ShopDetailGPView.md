# ShopDetailGPView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopDetailItemView _itemDetailView`

- `ScrollRect _itemScrollRect`

- `Transform _itemContainer`

- `Image _spriteImage`

- `GameObject _panelRemain`

- `Text _remainCount`

- `UIStringEvent _onPreviewClick`


## Methods

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailGPView : ShopDetailCommonView, IHotfixable
{
	private ShopDetailItemView _itemDetailView; // 0xa8
	private ScrollRect _itemScrollRect; // 0xb0
	private Transform _itemContainer; // 0xb8
	private Image _spriteImage; // 0xc0
	private GameObject _panelRemain; // 0xc8
	private Text _remainCount; // 0xd0
	private UIStringEvent _onPreviewClick; // 0xd8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2437e30 VA: 0x7594a4fe30
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x24387e4 VA: 0x7594a507e4
	public Void .ctor() { }
	// RVA: 0x2438850 VA: 0x7594a50850
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
}
```