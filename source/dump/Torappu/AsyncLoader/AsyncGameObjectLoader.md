# AsyncGameObjectLoader

**Namespace:** `Torappu.AsyncLoader`


## Methods

- `Void StartTask(Int32, Handler)`

- `Void StartTask(Int32, Int32, Handler)`

- `Void ModifyLoadingOrders(IEnumerator`1)`

- `Void _StartTaskImpl(AsyncOrder, Handler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AsyncLoader
public class AsyncGameObjectLoader : AsyncLoaderBase
{
	private static DelegateBridge __Hotfix0_StartTask; // 0x0
	private static DelegateBridge __Hotfix1_StartTask; // 0x8
	private static DelegateBridge __Hotfix0_ModifyLoadingOrders; // 0x10
	private static DelegateBridge __Hotfix0__StartTaskImpl; // 0x18
	private static DelegateBridge __Hotfix0_OnTaskLoaded; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x372a66c VA: 0x7595d4266c
	public Void StartTask(Int32 index, Handler handler) { }
	// RVA: 0x372a7b4 VA: 0x7595d427b4
	public Void StartTask(Int32 group, Int32 index, Handler handler) { }
	// RVA: 0x372a858 VA: 0x7595d42858
	public Void ModifyLoadingOrders(IEnumerator`1 iter) { }
	// RVA: 0x372a6f8 VA: 0x7595d426f8
	private Void _StartTaskImpl(AsyncOrder order, Handler handler) { }
	// RVA: 0x372abe8 VA: 0x7595d42be8
	protected override Void OnTaskLoaded(AsyncTaskBase task) { }
	// RVA: 0x372ac60 VA: 0x7595d42c60
	public Void .ctor() { }
}
```