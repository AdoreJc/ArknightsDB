# ItemRepoItemDetailStateBean

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIItemViewModel itemViewModel`

- `CharGachaVoucherData cacheCharData`

- `ItemVoucherData cacheItemData`

- `Output cacheGachaOutput`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemDetailStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public UIItemViewModel itemViewModel; // 0x18
	public CharGachaVoucherData cacheCharData; // 0x20
	public ItemVoucherData cacheItemData; // 0x28
	public GachaResult[] cacheGachaResult; // 0x30
	public Output cacheGachaOutput; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x2d2d2b0 VA: 0x75953452b0
	public Void .ctor() { }
}
```