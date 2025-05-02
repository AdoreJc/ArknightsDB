# HomeMailRecycleAdapter

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _mailItem`

- `UIMailIndexEvent _mailClickEvent`

- `UIMailIndexEvent _mailDetailEvent`


## Methods

- `Void _OnMailClick(HomeMailIndex)`

- `Void _OnMailDetailClick(HomeMailIndex)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailRecycleAdapter : RecycleLoopScrollAdapter`2
{
	public Action`1 DealAction; // 0x68
	private GameObject _mailItem; // 0x70
	private UIMailIndexEvent _mailClickEvent; // 0x78
	private UIMailIndexEvent _mailDetailEvent; // 0x80
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnMailClick; // 0x10
	private static DelegateBridge __Hotfix0__OnMailDetailClick; // 0x18
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2844844 VA: 0x7594e5c844
	public override Void UpdateView(Int32 position, GameObject view, HomeMailItemViewHolder holder, MailItemViewModel data) { }
	// RVA: 0x28449d8 VA: 0x7594e5c9d8
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x2844a44 VA: 0x7594e5ca44
	private Void _OnMailClick(HomeMailIndex index) { }
	// RVA: 0x2844b0c VA: 0x7594e5cb0c
	private Void _OnMailDetailClick(HomeMailIndex index) { }
	// RVA: 0x2844bd4 VA: 0x7594e5cbd4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2844cc4 VA: 0x7594e5ccc4
	public Void .ctor() { }
}
```