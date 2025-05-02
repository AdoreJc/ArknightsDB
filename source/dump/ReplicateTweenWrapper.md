# ReplicateTweenWrapper

**Namespace:** ` `


## Fields

- `CanvasGroup m_itemCanvasGroup`

- `CanvasGroup m_replicateCanvasGroup`

- `Sequence m_tween`


## Methods

- `Void SetCanvasGroup(CanvasGroup, CanvasGroup)`

- `Void SetTween()`

- `Void KillTween()`

- `Void <SetTween>b__4_1(Single)`

- `Void <SetTween>b__4_3(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ReplicateTweenWrapper : IHotfixable
{
	private CanvasGroup m_itemCanvasGroup; // 0x10
	private CanvasGroup m_replicateCanvasGroup; // 0x18
	private Sequence m_tween; // 0x20
	private static DelegateBridge __Hotfix0_SetCanvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_SetTween; // 0x8
	private static DelegateBridge __Hotfix0_KillTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2188de0 VA: 0x75947a0de0
	public Void SetCanvasGroup(CanvasGroup item, CanvasGroup replicate) { }
	// RVA: 0x2189608 VA: 0x75947a1608
	public Void SetTween() { }
	// RVA: 0x2188cd0 VA: 0x75947a0cd0
	public Void KillTween() { }
	// RVA: 0x2188d70 VA: 0x75947a0d70
	public Void .ctor() { }
	// RVA: 0x218a070 VA: 0x75947a2070
	private Void <SetTween>b__4_1(Single val) { }
	// RVA: 0x218a0b4 VA: 0x75947a20b4
	private Void <SetTween>b__4_3(Single val) { }
}
```