# Act20sideRecycleCompAdapter

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `GameObject _itemPrefab`

- `UIStringEvent _onCompSelect`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideRecycleCompAdapter : RecycleLoopScrollAdapter
{
	private GameObject _itemPrefab; // 0x58
	private UIStringEvent _onCompSelect; // 0x60
	public List`1 viewModelList; // 0x68
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x32eeee4 VA: 0x7595906ee4
	public override Int32 get_totalCount() { }
	// RVA: 0x32eef64 VA: 0x7595906f64
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x32ef0b4 VA: 0x75959070b4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x32ef1b4 VA: 0x75959071b4
	public Void .ctor() { }
}
```