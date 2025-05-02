# FriendListRepoGridAdapter

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _friendItem`

- `FriendListState _state`

- `FriendListView _view`

- `Int32 indexFlag`


## Methods

- `Void HideViewList(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListRepoGridAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _friendItem; // 0x68
	private FriendListState _state; // 0x70
	private FriendListView _view; // 0x78
	public Int32 indexFlag; // 0x80
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x0
	private static DelegateBridge __Hotfix0_HideViewList; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28ce22c VA: 0x7594ee622c
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x28ce298 VA: 0x7594ee6298
	public Void HideViewList(Int32 index) { }
	// RVA: 0x28ce314 VA: 0x7594ee6314
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x28ce404 VA: 0x7594ee6404
	public override Void UpdateView(Int32 position, GameObject view, FriendListItemHolder holder, KeyValuePair`2 data) { }
	// RVA: 0x28ce554 VA: 0x7594ee6554
	public Void .ctor() { }
}
```