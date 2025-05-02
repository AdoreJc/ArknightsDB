# TemplateShopCommonRightViewHolder

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopCommonRightComplexView _complexView`

- `TemplateShopCommonRightSingleView _singleView`

- `TemplateCommonShopGoodViewModel m_cacheViewModel`


## Methods

- `Int32 GetBuyCount()`

- `Void RenderFirstTime()`

- `Void Render(TemplateCommonShopGoodViewModel, Boolean, Int32, ItemBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopCommonRightViewHolder : MonoBehaviour, IHotfixable
{
	private TemplateShopCommonRightComplexView _complexView; // 0x18
	private TemplateShopCommonRightSingleView _singleView; // 0x20
	private TemplateCommonShopGoodViewModel m_cacheViewModel; // 0x28
	private static DelegateBridge __Hotfix0_GetBuyCount; // 0x0
	private static DelegateBridge __Hotfix0_RenderFirstTime; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23545c4 VA: 0x759496c5c4
	public Int32 GetBuyCount() { }
	// RVA: 0x2353fec VA: 0x759496bfec
	public Void RenderFirstTime() { }
	// RVA: 0x2354134 VA: 0x759496c134
	public Void Render(TemplateCommonShopGoodViewModel shopViewModel, Boolean isReplicate, Int32 availCount, ItemBundle item) { }
	// RVA: 0x235d0dc VA: 0x75949750dc
	public Void .ctor() { }
}
```