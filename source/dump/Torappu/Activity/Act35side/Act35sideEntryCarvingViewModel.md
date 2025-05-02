# Act35sideEntryCarvingViewModel

**Namespace:** `Torappu.Activity.Act35side`


## Fields

- `Status currStatus`

- `String m_actId`

- `DateTime m_actStartTs`

- `DateTime m_actEndTs`


## Methods

- `Void RefreshStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act35side
public class Act35sideEntryCarvingViewModel : TemplateActivityViewModel, IHotfixable
{
	public Status currStatus; // 0x20
	private String m_actId; // 0x28
	private DateTime m_actStartTs; // 0x30
	private DateTime m_actEndTs; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x8


	// RVA: 0x3251774 VA: 0x7595869774
	public Void .ctor(Object param) { }
	// RVA: 0x3251864 VA: 0x7595869864
	public Void RefreshStatus() { }
}
```