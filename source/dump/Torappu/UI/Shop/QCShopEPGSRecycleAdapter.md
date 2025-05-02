# QCShopEPGSRecycleAdapter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _itemObj`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopEPGSRecycleAdapter : RecycleLoopScrollAdapter
{
	public List`1 viewModelList; // 0x58
	private GameObject _itemObj; // 0x60
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x2452918 VA: 0x7594a6a918
	public override Int32 get_totalCount() { }
	// RVA: 0x2452998 VA: 0x7594a6a998
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x2452ad0 VA: 0x7594a6aad0
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2452bc0 VA: 0x7594a6abc0
	public Void .ctor() { }
}
```