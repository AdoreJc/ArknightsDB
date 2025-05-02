# RecruitDialogController

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RectTransform _dialogContainer`

- `UICompDialogMgr m_dialogMgr`

- `Boolean m_hasInited`


## Properties

- `UICompDialogMgr dialogMgr`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitDialogController : PageSingleComponent, IHotfixable
{
	private RectTransform _dialogContainer; // 0x20
	private UICompDialogMgr m_dialogMgr; // 0x28
	private Boolean m_hasInited; // 0x30
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x26f243c VA: 0x7594d0a43c
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x26f24f8 VA: 0x7594d0a4f8
	private Void _InitIfNot() { }
	// RVA: 0x26f25b8 VA: 0x7594d0a5b8
	public Void .ctor() { }
}
```