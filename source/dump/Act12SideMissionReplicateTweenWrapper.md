# Act12SideMissionReplicateTweenWrapper

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
private class Act12SideMissionReplicateTweenWrapper : IHotfixable
{
	private CanvasGroup m_itemCanvasGroup; // 0x10
	private CanvasGroup m_replicateCanvasGroup; // 0x18
	private Sequence m_tween; // 0x20
	private static DelegateBridge __Hotfix0_SetCanvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_SetTween; // 0x8
	private static DelegateBridge __Hotfix0_KillTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x34656f4 VA: 0x7595a7d6f4
	public Void SetCanvasGroup(CanvasGroup item, CanvasGroup replicate) { }
	// RVA: 0x34650a0 VA: 0x7595a7d0a0
	public Void SetTween() { }
	// RVA: 0x3464d58 VA: 0x7595a7cd58
	public Void KillTween() { }
	// RVA: 0x3465684 VA: 0x7595a7d684
	public Void .ctor() { }
	// RVA: 0x346590c VA: 0x7595a7d90c
	private Void <SetTween>b__4_1(Single val) { }
	// RVA: 0x3465950 VA: 0x7595a7d950
	private Void <SetTween>b__4_3(Single val) { }
}
```