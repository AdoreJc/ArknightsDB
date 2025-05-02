# ActVecBreakDefenseEntryViewModel

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `String actId`

- `String lockedText`

- `Boolean isUnlock`


## Properties

- `Boolean hasNew`


## Methods

- `Boolean get_hasNew()`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakDefenseEntryViewModel : TemplateActivityViewModel, IHotfixable
{
	public String actId; // 0x20
	public String lockedText; // 0x28
	public Boolean isUnlock; // 0x30
	private static DelegateBridge __Hotfix0_get_hasNew; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean hasNew { get; }

	// RVA: 0x30d6eec VA: 0x75956eeeec
	public Boolean get_hasNew() { }
	// RVA: 0x30d6f58 VA: 0x75956eef58
	public Void LoadData() { }
	// RVA: 0x30d6fd4 VA: 0x75956eefd4
	public Void .ctor(Object param) { }
}
```