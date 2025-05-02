# ActPlayer

**Namespace:** ` `


## Fields

- `RoguelikeScrollReportController m_closure`

- `Single m_scrollSpeed`

- `Boolean m_isFastMode`

- `Boolean m_isSkipMode`

- `UISleepBlocker m_sleepBlocker`


## Methods

- `Void _UpdateScrollSpeed()`

- `Void DoSkip()`

- `Void SetFastMode(Boolean)`

- `Void Dispose()`

- `IEnumerator PlayCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActPlayer : IHotfixable, IDisposable
{
	private const Single BASE_SCROLL_PER_FRAME; // 0x0
	private const Single FAST_SCROLL_PER_FRAME; // 0x0
	private RoguelikeScrollReportController m_closure; // 0x10
	private Single m_scrollSpeed; // 0x18
	private Boolean m_isFastMode; // 0x1c
	private Boolean m_isSkipMode; // 0x1d
	private UISleepBlocker m_sleepBlocker; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__UpdateScrollSpeed; // 0x8
	private static DelegateBridge __Hotfix0_DoSkip; // 0x10
	private static DelegateBridge __Hotfix0_SetFastMode; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20
	private static DelegateBridge __Hotfix0_PlayCoroutine; // 0x28


	// RVA: 0x2a86348 VA: 0x759509e348
	public Void .ctor(RoguelikeScrollReportController closure) { }
	// RVA: 0x2a86418 VA: 0x759509e418
	private Void _UpdateScrollSpeed() { }
	// RVA: 0x2a85f78 VA: 0x759509df78
	public Void DoSkip() { }
	// RVA: 0x2a86060 VA: 0x759509e060
	public Void SetFastMode(Boolean isFastMode) { }
	// RVA: 0x2a85d68 VA: 0x759509dd68
	public Void Dispose() { }
	// RVA: 0x2a86494 VA: 0x759509e494
	public IEnumerator PlayCoroutine() { }
}
```