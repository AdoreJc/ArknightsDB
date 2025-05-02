# HandBookUnlockInfo

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String charId`

- `HandbookUnlockParam unlockParam`

- `String overrideString`


## Properties

- `Boolean isUnlock`


## Methods

- `Boolean get_isUnlock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookUnlockInfo : IHotfixable
{
	public String charId; // 0x10
	public HandbookUnlockParam unlockParam; // 0x18
	public String overrideString; // 0x20
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isUnlock { get; }

	// RVA: 0x2eb70ec VA: 0x75954cf0ec
	public Boolean get_isUnlock() { }
	// RVA: 0x2ec05ac VA: 0x75954d85ac
	public Void .ctor() { }
}
```