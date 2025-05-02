# Act27sideEntryGroceryViewModel

**Namespace:** `Torappu.Activity.Act27side`


## Fields

- `Status currStatus`

- `String lockedToastDesc`

- `String lockedDesc`

- `String m_actId`

- `DateTime m_actEndTs`

- `DateTime m_actRewardEndTs`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act27side
public class Act27sideEntryGroceryViewModel : TemplateActivityViewModel, IHotfixable
{
	public Status currStatus; // 0x20
	public String lockedToastDesc; // 0x28
	public String lockedDesc; // 0x30
	private String m_actId; // 0x38
	private DateTime m_actEndTs; // 0x40
	private DateTime m_actRewardEndTs; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x32699a0 VA: 0x75958819a0
	public Void .ctor(Object param) { }
	// RVA: 0x32690b8 VA: 0x75958810b8
	public Void RefreshPlayerData() { }
}
```