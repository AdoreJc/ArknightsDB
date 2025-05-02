# ShopDetailProgressView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopDetailProgressItem _unactiveItem`

- `ShopDetailProgressItem _acativeItem`

- `Transform _itemContainer`

- `Text _itemDetailState`


## Methods

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailProgressView : ShopDetailCommonView, IHotfixable
{
	private ShopDetailProgressItem _unactiveItem; // 0xa8
	private ShopDetailProgressItem _acativeItem; // 0xb0
	private Transform _itemContainer; // 0xb8
	private Text _itemDetailState; // 0xc0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x243c098 VA: 0x7594a54098
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x243c4e0 VA: 0x7594a544e0
	public Void .ctor() { }
	// RVA: 0x243c550 VA: 0x7594a54550
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
}
```