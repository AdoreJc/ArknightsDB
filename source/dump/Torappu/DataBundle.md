# DataBundle

**Namespace:** `Torappu`


## Methods

- `Void SetInt(String, Int32)`

- `Int32 GetInt(String, Int32)`

- `Void SetLong(String, Int64)`

- `Int64 GetLong(String, Int64)`

- `Void SetFloat(String, Single)`

- `Single GetFloat(String, Single)`

- `Void SetBool(String, Boolean)`

- `Boolean GetBool(String, Boolean)`

- `Void SetDouble(String, Double)`

- `Double GetDouble(String, Double)`

- `Void SetString(String, String)`

- `String GetString(String, String)`

- `Void SetDataBundle(String, DataBundle)`

- `DataBundle GetDataBundle(String, DataBundle)`

- `Void SetDataBundleList(String, List`1)`

- `Void SetStringList(String, List`1)`

- `Void SetIntList(String, List`1)`

- `Void SetTypeParam(String, Type)`

- `Type GetTypeParam(String, Type)`

- `Boolean Remove(String)`

- `Void _Set(String, TValue)`

- `TValue _Get(String, TValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DataBundle : ILuaCallCSharp, IHotfixable
{
	private ListDict`2 m_storage; // 0x10
	private static DelegateBridge __Hotfix0_SetInt; // 0x0
	private static DelegateBridge __Hotfix0_GetInt; // 0x8
	private static DelegateBridge __Hotfix0_SetLong; // 0x10
	private static DelegateBridge __Hotfix0_GetLong; // 0x18
	private static DelegateBridge __Hotfix0_SetFloat; // 0x20
	private static DelegateBridge __Hotfix0_GetFloat; // 0x28
	private static DelegateBridge __Hotfix0_SetBool; // 0x30
	private static DelegateBridge __Hotfix0_GetBool; // 0x38
	private static DelegateBridge __Hotfix0_SetDouble; // 0x40
	private static DelegateBridge __Hotfix0_GetDouble; // 0x48
	private static DelegateBridge __Hotfix0_SetString; // 0x50
	private static DelegateBridge __Hotfix0_GetString; // 0x58
	private static DelegateBridge __Hotfix0_SetDataBundle; // 0x60
	private static DelegateBridge __Hotfix0_GetDataBundle; // 0x68
	private static DelegateBridge __Hotfix0_SetDataBundleList; // 0x70
	private static DelegateBridge __Hotfix0_GetDataBundleList; // 0x78
	private static DelegateBridge __Hotfix0_SetStringList; // 0x80
	private static DelegateBridge __Hotfix0_GetStringList; // 0x88
	private static DelegateBridge __Hotfix0_SetIntList; // 0x90
	private static DelegateBridge __Hotfix0_GetIntList; // 0x98
	private static DelegateBridge __Hotfix0_SetTypeParam; // 0xa0
	private static DelegateBridge __Hotfix0_GetTypeParam; // 0xa8
	private static DelegateBridge __Hotfix0_Remove; // 0xb0
	private static DelegateBridge __Hotfix0__Set; // 0xb8
	private static DelegateBridge __Hotfix0__Get; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x2f43220 VA: 0x759555b220
	public Void SetInt(String key, Int32 value) { }
	// RVA: 0x2f432c4 VA: 0x759555b2c4
	public Int32 GetInt(String key, Int32 defValue) { }
	// RVA: 0x2f43368 VA: 0x759555b368
	public Void SetLong(String key, Int64 value) { }
	// RVA: 0x2f4340c VA: 0x759555b40c
	public Int64 GetLong(String key, Int64 defValue) { }
	// RVA: 0x2f434b0 VA: 0x759555b4b0
	public Void SetFloat(String key, Single value) { }
	// RVA: 0x2f43560 VA: 0x759555b560
	public Single GetFloat(String key, Single defValue) { }
	// RVA: 0x2f43610 VA: 0x759555b610
	public Void SetBool(String key, Boolean value) { }
	// RVA: 0x2f436b4 VA: 0x759555b6b4
	public Boolean GetBool(String key, Boolean defValue) { }
	// RVA: 0x2f43758 VA: 0x759555b758
	public Void SetDouble(String key, Double value) { }
	// RVA: 0x2f43808 VA: 0x759555b808
	public Double GetDouble(String key, Double defValue) { }
	// RVA: 0x2f438b8 VA: 0x759555b8b8
	public Void SetString(String key, String value) { }
	// RVA: 0x2f4395c VA: 0x759555b95c
	public String GetString(String key, String defValue) { }
	// RVA: 0x2f43a00 VA: 0x759555ba00
	public Void SetDataBundle(String key, DataBundle value) { }
	// RVA: 0x2f43aa4 VA: 0x759555baa4
	public DataBundle GetDataBundle(String key, DataBundle defValue) { }
	// RVA: 0x2f43b48 VA: 0x759555bb48
	public Void SetDataBundleList(String key, List`1 bundles) { }
	// RVA: 0x2f43bec VA: 0x759555bbec
	public List`1 GetDataBundleList(String key, List`1 defValue) { }
	// RVA: 0x2f43c90 VA: 0x759555bc90
	public Void SetStringList(String key, List`1 strs) { }
	// RVA: 0x2f43d34 VA: 0x759555bd34
	public List`1 GetStringList(String key, List`1 defValue) { }
	// RVA: 0x2f43dd8 VA: 0x759555bdd8
	public Void SetIntList(String key, List`1 ints) { }
	// RVA: 0x2f43e7c VA: 0x759555be7c
	public List`1 GetIntList(String key, List`1 defValue) { }
	// RVA: 0x2f43f20 VA: 0x759555bf20
	public Void SetTypeParam(String key, Type type) { }
	// RVA: 0x2f43fc4 VA: 0x759555bfc4
	public Type GetTypeParam(String key, Type defValue) { }
	// RVA: 0x2f44068 VA: 0x759555c068
	public Boolean Remove(String key) { }
	// RVA: 0x VA: 0x0
	private Void _Set(String key, TValue value) { }
	// RVA: 0x VA: 0x0
	private TValue _Get(String key, TValue defValue) { }
	// RVA: 0x2f44114 VA: 0x759555c114
	public Void .ctor() { }
}
```