# HostImpl

**Namespace:** ` `


## Fields

- `UINotification m_closure`

- `UINotificationSlideLayouter m_slideLayouter`

- `NotificationFloatLayouter m_floatLayouter`

- `AutoUnloadAssets m_notifyViewPrefabLoader`


## Methods

- `Void CollectUsedAssets(ICollection`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HostImpl : NotifyViewHost, IHost
{
	private UINotification m_closure; // 0x28
	private UINotificationSlideLayouter m_slideLayouter; // 0x30
	private NotificationFloatLayouter m_floatLayouter; // 0x38
	private AutoUnloadAssets m_notifyViewPrefabLoader; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CurrentTicks; // 0x8
	private static DelegateBridge __Hotfix0_SelectLayouter; // 0x10
	private static DelegateBridge __Hotfix0_StartCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_LoadPrefabFromResource; // 0x20
	private static DelegateBridge __Hotfix0_UnloadUnusedPrefabs; // 0x28
	private static DelegateBridge __Hotfix0_CollectUsedAssets; // 0x30


	// RVA: 0x227427c VA: 0x759488c27c
	public Void .ctor(UINotification closure) { }
	// RVA: 0x2275098 VA: 0x759488d098
	protected override Int64 CurrentTicks() { }
	// RVA: 0x VA: 0x0
	protected override NotifyViewLayouter SelectLayouter(NotifyViewOptions`2 options) { }
	// RVA: 0x2275168 VA: 0x759488d168
	public override Coroutine StartCoroutine(IEnumerator routine) { }
	// RVA: 0x22751f4 VA: 0x759488d1f4
	public override GameObject LoadPrefabFromResource(String resPath) { }
	// RVA: 0x22752d8 VA: 0x759488d2d8
	protected override Void UnloadUnusedPrefabs() { }
	// RVA: 0x227534c VA: 0x759488d34c
	public Void CollectUsedAssets(ICollection`1 usedAssets) { }
}
```