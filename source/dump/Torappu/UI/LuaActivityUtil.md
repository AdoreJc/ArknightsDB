# LuaActivityUtil

**Namespace:** `Torappu.UI`


## Fields

- `ILuaActivityUtil m_impl`


## Methods

- `Void FindValidHomeActs(List`1, List`1, List`1, List`1)`

- `String EnsureActivityDialogClass(LuaActClsConfig)`

- `Boolean CheckIfActivityUncomplete(ActivityType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LuaActivityUtil : Singleton`1
{
	private ILuaActivityUtil m_impl; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_BindInterface; // 0x8
	private static DelegateBridge __Hotfix0_FindValidHomeActs; // 0x10
	private static DelegateBridge __Hotfix0_EnsureActivityDialogClass; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfActivityUncomplete; // 0x20


	// RVA: 0x2102ed4 VA: 0x759471aed4
	private Void .ctor() { }
	// RVA: 0x2102f64 VA: 0x759471af64
	public static Void BindInterface(ILuaActivityUtil impl) { }
	// RVA: 0x2102ff4 VA: 0x759471aff4
	public Void FindValidHomeActs(List`1 validActs, List`1 uncompleteActs, List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x2103124 VA: 0x759471b124
	public String EnsureActivityDialogClass(LuaActClsConfig config) { }
	// RVA: 0x21010f4 VA: 0x75947190f4
	public Boolean CheckIfActivityUncomplete(ActivityType type, String actId) { }
}
```