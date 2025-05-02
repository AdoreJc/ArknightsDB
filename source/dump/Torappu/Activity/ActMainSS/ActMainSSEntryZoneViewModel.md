# ActMainSSEntryZoneViewModel

**Namespace:** `Torappu.Activity.ActMainSS`


## Fields

- `String zoneId`

- `Status currStatus`

- `String lockedTip`

- `String retroZoneId`

- `Int32 currPoint`

- `DateTime m_endTime`

- `String m_milestoneGroupId`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMainSS
public class ActMainSSEntryZoneViewModel : TemplateActivityViewModel, IHotfixable
{
	public String zoneId; // 0x20
	public Status currStatus; // 0x28
	public String lockedTip; // 0x30
	public String retroZoneId; // 0x38
	public Int32 currPoint; // 0x40
	private DateTime m_endTime; // 0x48
	private String m_milestoneGroupId; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x318c2d8 VA: 0x75957a42d8
	public Void .ctor(Object param) { }
	// RVA: 0x318bed0 VA: 0x75957a3ed0
	public Void RefreshPlayerData() { }
}
```