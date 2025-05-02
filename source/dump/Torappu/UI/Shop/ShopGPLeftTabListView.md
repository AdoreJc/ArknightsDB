# ShopGPLeftTabListView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopGPAllTagItem _allTabItem`

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_cachedSelectedId`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPLeftTabListView : DataBinder`1, IHotfixable
{
	private ShopGPAllTagItem _allTabItem; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private Boolean m_hasInited; // 0x30
	private Adapter m_adapter; // 0x38
	private List`1 m_cachedModels; // 0x40
	private String m_cachedSelectedId; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x244ab54 VA: 0x7594a62b54
	public override Void OnValueChanged(ShopGPProperty property) { }
	// RVA: 0x244ac9c VA: 0x7594a62c9c
	private Void _InitIfNot() { }
	// RVA: 0x244ae00 VA: 0x7594a62e00
	public Void .ctor() { }
}
```