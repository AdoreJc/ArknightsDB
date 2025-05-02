# MgrHostWithPage

**Namespace:** ` `


## Fields

- `UIPageListener m_listener`

- `UIPage m_page`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MgrHostWithPage : MgrHost
{
	private UIPageListener m_listener; // 0x10
	private UIPage m_page; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CreateAssetGroupForDialog; // 0x8
	private static DelegateBridge __Hotfix0_CreateAssetGroupForContainer; // 0x10
	private static DelegateBridge __Hotfix0_DisposeAssetGroupOfDialog; // 0x18
	private static DelegateBridge __Hotfix0_SetOnHostClosedCallback; // 0x20
	private static DelegateBridge __Hotfix0_SetOnHostRoutedCallback; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfValidCallback; // 0x30
	private static DelegateBridge __Hotfix0_CoroutineWithHost; // 0x38


	// RVA: 0x22636ec VA: 0x759487b6ec
	public Void .ctor(UIPage page) { }
	// RVA: 0x22663cc VA: 0x759487e3cc
	public override ILoadAsset CreateAssetGroupForDialog(DialogBase dialog) { }
	// RVA: 0x2266458 VA: 0x759487e458
	public override ILoadAsset CreateAssetGroupForContainer(Transform container) { }
	// RVA: 0x22664e4 VA: 0x759487e4e4
	public override Void DisposeAssetGroupOfDialog(DialogBase dialog) { }
	// RVA: 0x22665cc VA: 0x759487e5cc
	public override Void SetOnHostClosedCallback(Action onHostClosed) { }
	// RVA: 0x226666c VA: 0x759487e66c
	public override Void SetOnHostRoutedCallback(Action onHostResumed) { }
	// RVA: 0x22666f8 VA: 0x759487e6f8
	public override Boolean CheckIfValidCallback(Transform callbackTransform) { }
	// RVA: 0x22667a4 VA: 0x759487e7a4
	public override Coroutine CoroutineWithHost(IEnumerator routine) { }
}
```