# TemplateShopLeftProgressView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopLeftProgressItem _activeItem`

- `TemplateShopLeftProgressItem _unactiveItem`

- `Transform _container`


## Methods

- `Void Render(PlayerGoodProgressData, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopLeftProgressView : MonoBehaviour, IHotfixable
{
	private TemplateShopLeftProgressItem _activeItem; // 0x18
	private TemplateShopLeftProgressItem _unactiveItem; // 0x20
	private Transform _container; // 0x28
	private List`1 m_viewList; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x235bafc VA: 0x7594973afc
	public Void Render(PlayerGoodProgressData progressInfo, List`1 progressViewModelList) { }
	// RVA: 0x235e270 VA: 0x7594976270
	public Void .ctor() { }
}
```