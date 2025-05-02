# RecordNotePageBtnGlowTweenWrapper

**Namespace:** ` `


## Fields

- `CanvasGroup m_glowCanvasGroup`

- `Sequence m_tween`


## Methods

- `Void SetCanvasGroup(CanvasGroup)`

- `Void SetTween()`

- `Void KillTween()`

- `Void <SetTween>b__5_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RecordNotePageBtnGlowTweenWrapper : IHotfixable
{
	private CanvasGroup m_glowCanvasGroup; // 0x10
	private Sequence m_tween; // 0x18
	private const Single SELECT_GLOW_TWEEN_DUR; // 0x0
	private const Single SELECT_GLOW_END_ALPHA; // 0x0
	private static DelegateBridge __Hotfix0_SetCanvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_SetTween; // 0x8
	private static DelegateBridge __Hotfix0_KillTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fd1710 VA: 0x75955e9710
	public Void SetCanvasGroup(CanvasGroup canvas) { }
	// RVA: 0x2fd1c84 VA: 0x75955e9c84
	public Void SetTween() { }
	// RVA: 0x2fd1bf8 VA: 0x75955e9bf8
	public Void KillTween() { }
	// RVA: 0x2fd16a0 VA: 0x75955e96a0
	public Void .ctor() { }
	// RVA: 0x2fd2644 VA: 0x75955ea644
	private Void <SetTween>b__5_1(Single val) { }
}
```