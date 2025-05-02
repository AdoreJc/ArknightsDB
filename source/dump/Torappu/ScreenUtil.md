# ScreenUtil

**Namespace:** `Torappu`


## Fields

- `Int64 m_activeBlockerIndex`


## Methods

- `UISleepBlocker _RequestSleepBlocker()`

- `Void _ReleaseSleepBlocker(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ScreenUtil : Singleton`1, IHotfixable
{
	private const Int64 UISLEEPBLOCK_INVALID_ID; // 0x0
	private readonly ListSet`1 m_activeBlockers; // 0x10
	private Int64 m_activeBlockerIndex; // 0x18
	private static DelegateBridge __Hotfix0_BlockSleep; // 0x0
	private static DelegateBridge __Hotfix0__RequestSleepBlocker; // 0x8
	private static DelegateBridge __Hotfix0__ReleaseSleepBlocker; // 0x10
	private static DelegateBridge __Hotfix0__BlockSleep; // 0x18
	private static DelegateBridge __Hotfix0__UnblockSleep; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3114cac VA: 0x759572ccac
	public static UISleepBlocker BlockSleep() { }
	// RVA: 0x31169e4 VA: 0x759572e9e4
	private UISleepBlocker _RequestSleepBlocker() { }
	// RVA: 0x3116b40 VA: 0x759572eb40
	private Void _ReleaseSleepBlocker(Int64 id) { }
	// RVA: 0x3116ad8 VA: 0x759572ead8
	private static Void _BlockSleep() { }
	// RVA: 0x3116c48 VA: 0x759572ec48
	private static Void _UnblockSleep() { }
	// RVA: 0x3116cac VA: 0x759572ecac
	private Void .ctor() { }
}
```