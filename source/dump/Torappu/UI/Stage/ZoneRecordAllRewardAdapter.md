# ZoneRecordAllRewardAdapter

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _itemObj`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordAllRewardAdapter : RecycleLoopScrollAdapter
{
	private GameObject _itemObj; // 0x58
	public List`1 recordList; // 0x60
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x2fc37b8 VA: 0x75955db7b8
	public override Int32 get_totalCount() { }
	// RVA: 0x2fc3838 VA: 0x75955db838
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x2fc3ae0 VA: 0x75955dbae0
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2fc3bd0 VA: 0x75955dbbd0
	public Void .ctor() { }
}
```