# EntryViewController

**Namespace:** ` `


## Fields

- `ActivityCommonCheckinEntry m_closure`

- `CheckinViewType m_currentViewType`

- `ActivityCheckinEntryView m_currentView`


## Methods

- `Void Init()`

- `ActivityCheckinEntryView SwitchEntryView(CheckinViewType)`

- `ActivityCheckinEntryView _GetEntryView(CheckinViewType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class EntryViewController : IHotfixable
{
	private ActivityCommonCheckinEntry m_closure; // 0x10
	private ListDict`2 m_prefabMap; // 0x18
	private ListDict`2 m_instMap; // 0x20
	private CheckinViewType m_currentViewType; // 0x28
	private ActivityCheckinEntryView m_currentView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_SwitchEntryView; // 0x10
	private static DelegateBridge __Hotfix0__GetEntryView; // 0x18


	// RVA: 0x30cebcc VA: 0x75956e6bcc
	public Void .ctor(ActivityCommonCheckinEntry closure) { }
	// RVA: 0x30cf4f0 VA: 0x75956e74f0
	public Void Init() { }
	// RVA: 0x30cf56c VA: 0x75956e756c
	public ActivityCheckinEntryView SwitchEntryView(CheckinViewType viewType) { }
	// RVA: 0x30cf6d0 VA: 0x75956e76d0
	private ActivityCheckinEntryView _GetEntryView(CheckinViewType viewType) { }
}
```