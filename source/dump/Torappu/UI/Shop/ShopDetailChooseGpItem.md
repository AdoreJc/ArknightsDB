# ShopDetailChooseGpItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `TwoStateToggle _twoStateToggle`

- `Text _itemName1`

- `Text _itemName2`

- `Int32 m_position`

- `ChooseGiftPackageShopOption m_cacheOption`


## Methods

- `Void InitData(Int32, ChooseGiftPackageShopOption)`

- `Void SetPos(Int32)`

- `Void OnClickDetail()`

- `Void OnSelectClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailChooseGpItem : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _twoStateToggle; // 0x18
	private Text _itemName1; // 0x20
	private Text _itemName2; // 0x28
	public Action`1 onDetailClick; // 0x30
	public Action`1 onSelectClick; // 0x38
	private Int32 m_position; // 0x40
	private ChooseGiftPackageShopOption m_cacheOption; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SetPos; // 0x8
	private static DelegateBridge __Hotfix0_OnClickDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x242ffc4 VA: 0x7594a47fc4
	public Void InitData(Int32 position, ChooseGiftPackageShopOption option) { }
	// RVA: 0x24300f4 VA: 0x7594a480f4
	public Void SetPos(Int32 selectPos) { }
	// RVA: 0x2430188 VA: 0x7594a48188
	public Void OnClickDetail() { }
	// RVA: 0x2430210 VA: 0x7594a48210
	public Void OnSelectClick() { }
	// RVA: 0x2430298 VA: 0x7594a48298
	public Void .ctor() { }
}
```