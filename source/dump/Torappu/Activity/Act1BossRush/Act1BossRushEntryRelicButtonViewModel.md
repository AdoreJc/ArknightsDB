# Act1BossRushEntryRelicButtonViewModel

**Namespace:** `Torappu.Activity.Act1BossRush`


## Methods

- `Boolean HasRelicUnlock()`

- `Boolean HasRelicCanUpgrade()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushEntryRelicButtonViewModel : TemplateActivityViewModel, IHotfixable
{
	private Func`1 m_checkIfRelicUnlockFunc; // 0x20
	private Func`1 m_checkIfRelicCanUpgradeFunc; // 0x28
	private static DelegateBridge __Hotfix0_HasRelicUnlock; // 0x0
	private static DelegateBridge __Hotfix0_HasRelicCanUpgrade; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31914b4 VA: 0x75957a94b4
	public Boolean HasRelicUnlock() { }
	// RVA: 0x319153c VA: 0x75957a953c
	public Boolean HasRelicCanUpgrade() { }
	// RVA: 0x31917b0 VA: 0x75957a97b0
	public Void .ctor(Object param) { }
}
```