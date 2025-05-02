# BattleDialogVariableGetter

**Namespace:** `Torappu.Battle.Dialog`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
internal class BattleDialogVariableGetter : Singleton`1, IHotfixable
{
	private readonly Dictionary`2 m_delegateDic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetVariableValue; // 0x8
	private static DelegateBridge __Hotfix0__Equals; // 0x10


	// RVA: 0x1d27440 VA: 0x759433f440
	private Void .ctor() { }
	// RVA: 0x1d27680 VA: 0x759433f680
	public static String GetVariableValue(String varName) { }
	// RVA: 0x1d277dc VA: 0x759433f7dc
	private static Boolean _Equals(String l, String r) { }
}
```