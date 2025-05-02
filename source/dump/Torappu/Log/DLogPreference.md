# DLogPreference

**Namespace:** `Torappu.Log`


## Fields

- `Data m_data`


## Methods

- `Void InitAndApply(Boolean)`

- `Data ResetToCurrentSettings()`

- `Void <InitAndApply>b__5_0(String)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Log
public class DLogPreference : Singleton`1
{
	public const String LOG_PREF_FILE; // 0x0
	private const Int32 PREF_VERSION; // 0x0
	private Data m_data; // 0x10
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate9 __Hotfix0_InitAndApply; // 0x8
	private static __XLua_Gen_Delegate175 __Hotfix0_ResetToCurrentSettings; // 0x10
	private static __XLua_Gen_Delegate176 __Hotfix0__AdjustDataFromCurrentSettings; // 0x18
	private static __XLua_Gen_Delegate175 __Hotfix0__MigrateData; // 0x20
	private static __XLua_Gen_Delegate1 __Hotfix0__MakeDefaultChannels; // 0x28
	private static __XLua_Gen_Delegate1 __Hotfix0__ApplyDataToDLog; // 0x30
	private static __XLua_Gen_Delegate5 __Hotfix0__EnablePreference; // 0x38


	// RVA: 0x67b59bc VA: 0x7598dcd9bc
	private Void .ctor() { }
	// RVA: 0x67b5a54 VA: 0x7598dcda54
	public Void InitAndApply(Boolean forceReloadData) { }
	// RVA: 0x67b65e8 VA: 0x7598dce5e8
	public Data ResetToCurrentSettings() { }
	// RVA: 0x67b5d60 VA: 0x7598dcdd60
	private static Void _AdjustDataFromCurrentSettings(ref Data data) { }
	// RVA: 0x67b6a68 VA: 0x7598dcea68
	private static Data _MigrateData(Data data) { }
	// RVA: 0x67b67b4 VA: 0x7598dce7b4
	private static Void _MakeDefaultChannels(Data data) { }
	// RVA: 0x67b6468 VA: 0x7598dce468
	private static Void _ApplyDataToDLog(Data data) { }
	// RVA: 0x67b5cf8 VA: 0x7598dcdcf8
	private static Boolean _EnablePreference() { }
	// RVA: 0x67b6ad8 VA: 0x7598dcead8
	private Void <InitAndApply>b__5_0(String text) { }
}
```