# Act9D0MissionReplicateTweenWrapper

**Namespace:** ` `


## Fields

- `CanvasGroup m_itemCanvasGroup`

- `CanvasGroup m_replicateCanvasGroup`

- `Sequence m_tween`


## Methods

- `Void SetCanvasGroup(CanvasGroup, CanvasGroup)`

- `Void SetTween()`

- `Void KillTween()`

- `Void Dispose()`

- `Void <SetTween>b__5_1(Single)`

- `Void <SetTween>b__5_3(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Act9D0MissionReplicateTweenWrapper : IHotfixable, IDisposable
{
	private const Single ANIMATION_ANIM_SPEED; // 0x0
	private CanvasGroup m_itemCanvasGroup; // 0x10
	private CanvasGroup m_replicateCanvasGroup; // 0x18
	private Sequence m_tween; // 0x20
	private static DelegateBridge __Hotfix0_SetCanvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_SetTween; // 0x8
	private static DelegateBridge __Hotfix0_KillTween; // 0x10
	private static DelegateBridge __Hotfix0_Dispose; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31a7fbc VA: 0x75957bffbc
	public Void SetCanvasGroup(CanvasGroup item, CanvasGroup replicate) { }
	// RVA: 0x31a795c VA: 0x75957bf95c
	public Void SetTween() { }
	// RVA: 0x31a78a8 VA: 0x75957bf8a8
	public Void KillTween() { }
	// RVA: 0x31a6a30 VA: 0x75957bea30
	public Void Dispose() { }
	// RVA: 0x31a7f4c VA: 0x75957bff4c
	public Void .ctor() { }
	// RVA: 0x31a81a0 VA: 0x75957c01a0
	private Void <SetTween>b__5_1(Single val) { }
	// RVA: 0x31a81e4 VA: 0x75957c01e4
	private Void <SetTween>b__5_3(Single val) { }
}
```