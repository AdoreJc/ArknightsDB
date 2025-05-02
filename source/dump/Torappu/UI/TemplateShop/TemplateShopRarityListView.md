# TemplateShopRarityListView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `SimpleLayoutContent _content`

- `ScrollRect _scrollRect`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1, TemplateShopResHolder)`

- `Void FocusOnRarityList(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopRarityListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private ScrollRect _scrollRect; // 0x20
	private Adapter m_adapter; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_FocusOnRarityList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x235ed20 VA: 0x7594976d20
	public Void _InitIfNot() { }
	// RVA: 0x2356820 VA: 0x759496e820
	public Void Render(List`1 viewModelList, TemplateShopResHolder resHolder) { }
	// RVA: 0x23576e0 VA: 0x759496f6e0
	public Void FocusOnRarityList(Int32 focusIdx) { }
	// RVA: 0x235efa0 VA: 0x7594976fa0
	public Void .ctor() { }
}
```