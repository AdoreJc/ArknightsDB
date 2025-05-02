# Act29sideEntryTuningViewModel

**Namespace:** `Torappu.Activity.Act29side`


## Fields

- `DateTime m_actEndTs`

- `DateTime m_actRewardEndTs`

- `Status currStatus`

- `String lockedToastDesc`

- `String lockedDesc`

- `String crossDayTrackId`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side
public class Act29sideEntryTuningViewModel : TemplateActivityViewModel, IHotfixable
{
	private DateTime m_actEndTs; // 0x20
	private DateTime m_actRewardEndTs; // 0x28
	public Status currStatus; // 0x30
	public String lockedToastDesc; // 0x38
	public String lockedDesc; // 0x40
	public String crossDayTrackId; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x3263508 VA: 0x759587b508
	public Void .ctor(Object param) { }
	// RVA: 0x3262e78 VA: 0x759587ae78
	public Void RefreshPlayerData() { }
}
```