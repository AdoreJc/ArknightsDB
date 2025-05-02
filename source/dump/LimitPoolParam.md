# LimitPoolParam

**Namespace:** ` `


## Fields

- `Boolean m_hasFreeChar`

- `Int32 m_freeCount`

- `String m_limitedCharId`


## Methods

- `Void UpdateData(GachaPoolClientData)`

- `Boolean HasFreeChar()`

- `Int32 GetFreeCount()`

- `String GetLimitedCharId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LimitPoolParam : IHotfixable
{
	private const String BOOL_HASFREECHAR; // 0x0
	private const String INT_FREECOUNT; // 0x0
	private const String STRING_LIMITEDCHARID; // 0x0
	private Boolean m_hasFreeChar; // 0x10
	private Int32 m_freeCount; // 0x14
	private String m_limitedCharId; // 0x18
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_HasFreeChar; // 0x8
	private static DelegateBridge __Hotfix0_GetFreeCount; // 0x10
	private static DelegateBridge __Hotfix0_GetLimitedCharId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x271740c VA: 0x7594d2f40c
	public Void UpdateData(GachaPoolClientData poolClientData) { }
	// RVA: 0x27166e4 VA: 0x7594d2e6e4
	public Boolean HasFreeChar() { }
	// RVA: 0x2716c38 VA: 0x7594d2ec38
	public Int32 GetFreeCount() { }
	// RVA: 0x2717550 VA: 0x7594d2f550
	public String GetLimitedCharId() { }
	// RVA: 0x27178b4 VA: 0x7594d2f8b4
	public Void .ctor() { }
}
```