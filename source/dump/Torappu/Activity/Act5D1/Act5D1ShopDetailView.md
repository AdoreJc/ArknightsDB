# Act5D1ShopDetailView

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Text _currentPrice`

- `Text _itemDetail`

- `Text _itemDetail_2`

- `Text _itemName`

- `Act5D1ShopCommonViewModel m_data`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ShopDetailView : MonoBehaviour, IHotfixable
{
	protected Text _currentPrice; // 0x18
	protected Text _itemDetail; // 0x20
	protected Text _itemDetail_2; // 0x28
	protected Text _itemName; // 0x30
	private Act5D1ShopCommonViewModel m_data; // 0x38
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31d761c VA: 0x75957ef61c
	public virtual Void ApplyData(Act5D1ShopCommonViewModel data) { }
	// RVA: 0x31d7820 VA: 0x75957ef820
	public virtual Void OnClick() { }
	// RVA: 0x31d75a8 VA: 0x75957ef5a8
	public Void .ctor() { }
}
```