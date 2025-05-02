# AVGDisplayableManager

**Namespace:** `Torappu.AVG`


## Fields

- `Transform m_bgOverlay`

- `Transform m_charOverlay`


## Methods

- `Void OnReset()`

- `Void Display(Command)`

- `Void _DisplayInternal(Command)`

- `AVGDisplayableHolder _GenearteDisplayable(AVGDisplaySlot)`

- `Transform _GetSlotContainer(AVGDisplaySlot)`

- `Void _ClearHolders()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGDisplayableManager : IHotfixable
{
	private Transform m_bgOverlay; // 0x10
	private Transform m_charOverlay; // 0x18
	private Dictionary`2 m_holders; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_Display; // 0x10
	private static DelegateBridge __Hotfix0__DisplayInternal; // 0x18
	private static DelegateBridge __Hotfix0__GenearteDisplayable; // 0x20
	private static DelegateBridge __Hotfix0__GetSlotContainer; // 0x28
	private static DelegateBridge __Hotfix0__ClearHolders; // 0x30


	// RVA: 0x3e5480c VA: 0x759646c80c
	public Void .ctor(Param param) { }
	// RVA: 0x3e54440 VA: 0x759646c440
	public Void OnReset() { }
	// RVA: 0x3e5475c VA: 0x759646c75c
	public Void Display(Command command) { }
	// RVA: 0x3e56ad0 VA: 0x759646ead0
	private Void _DisplayInternal(Command command) { }
	// RVA: 0x3e56e04 VA: 0x759646ee04
	private AVGDisplayableHolder _GenearteDisplayable(AVGDisplaySlot slot) { }
	// RVA: 0x3e57100 VA: 0x759646f100
	private Transform _GetSlotContainer(AVGDisplaySlot slot) { }
	// RVA: 0x3e568e4 VA: 0x759646e8e4
	private Void _ClearHolders() { }
}
```