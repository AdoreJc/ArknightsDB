# Blackboard

**Namespace:** `Torappu`


## Methods

- `Void Reset(IList`1)`

- `Void Assign(IList`1)`

- `Void Assign(String, Single)`

- `Void RemoveKey(String)`

- `Void Assign(String, FP)`

- `Void Assign(String, String)`

- `Boolean ContainsKey(String)`

- `Void _AssignInternal(DataPair)`

- `Single GetFloat(String)`

- `FP GetFP(String)`

- `Int32 GetInt(String)`

- `Boolean GetBool(String)`

- `String GetString(String)`

- `Boolean TryGetFloat(String, out)`

- `Boolean TryGetFP(String, out)`

- `Boolean TryGetInt(String, out)`

- `Boolean TryGetBool(String, out)`

- `Boolean TryGetString(String, out)`

- `Boolean TryGetInternalData(String, out)`

- `TEnum GetEnumOrDefault(String, String)`

- `Single GetFloatOrDefault(String, Single, Boolean)`

- `FP GetFpOrDefault(String, FP, Boolean)`

- `Boolean GetBoolOrDefault(String, Boolean, Boolean)`

- `Int32 GetIntOrDefault(String, Int32, Boolean)`

- `String GetStringOrDefault(String, String, Boolean)`

- `Single EnsureFloat(String)`

- `Boolean EnsureBool(String)`

- `Int32 EnsureInt(String)`

- `String EnsureString(String)`

- `Void GenerateBlackboardWithPrefix(ref, String)`

- `Blackboard GenerateBlackboardWithPrefix(String)`

- `Void AssignByPrefix(IList`1, String)`

- `Void AssignValueStrByPrefix(IList`1, String)`

- `Void AddBlackboardStrictly(Blackboard)`

- `Void AddBlackboardBaseOneStrictly(Blackboard)`

- `Boolean _TryGetNumber(String, out)`

- `Boolean _TryToStripPrefix(String, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class Blackboard : List`1, IHotfixable
{
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x8
	private static DelegateBridge _c__Hotfix2_ctor; // 0x10
	private static DelegateBridge _c__Hotfix3_ctor; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_Assign; // 0x28
	private static DelegateBridge __Hotfix1_Assign; // 0x30
	private static DelegateBridge __Hotfix0_RemoveKey; // 0x38
	private static DelegateBridge __Hotfix2_Assign; // 0x40
	private static DelegateBridge __Hotfix3_Assign; // 0x48
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x50
	private static DelegateBridge __Hotfix0__AssignInternal; // 0x58
	private static DelegateBridge __Hotfix0_Of; // 0x60
	private static DelegateBridge __Hotfix0_MergeTo; // 0x68
	private static DelegateBridge __Hotfix1_MergeTo; // 0x70
	private static DelegateBridge __Hotfix0_Union; // 0x78
	private static DelegateBridge __Hotfix0_GetFloat; // 0x80
	private static DelegateBridge __Hotfix0_GetFP; // 0x88
	private static DelegateBridge __Hotfix0_GetInt; // 0x90
	private static DelegateBridge __Hotfix0_GetBool; // 0x98
	private static DelegateBridge __Hotfix0_GetString; // 0xa0
	private static DelegateBridge __Hotfix0_TryGetFloat; // 0xa8
	private static DelegateBridge __Hotfix0_TryGetFP; // 0xb0
	private static DelegateBridge __Hotfix0_TryGetInt; // 0xb8
	private static DelegateBridge __Hotfix0_TryGetBool; // 0xc0
	private static DelegateBridge __Hotfix0_TryGetString; // 0xc8
	private static DelegateBridge __Hotfix0_TryGetInternalData; // 0xd0
	private static DelegateBridge __Hotfix0_GetEnumOrDefault; // 0xd8
	private static DelegateBridge __Hotfix0_GetFloatOrDefault; // 0xe0
	private static DelegateBridge __Hotfix0_GetFpOrDefault; // 0xe8
	private static DelegateBridge __Hotfix0_GetBoolOrDefault; // 0xf0
	private static DelegateBridge __Hotfix0_GetIntOrDefault; // 0xf8
	private static DelegateBridge __Hotfix0_GetStringOrDefault; // 0x100
	private static DelegateBridge __Hotfix0_EnsureFloat; // 0x108
	private static DelegateBridge __Hotfix0_EnsureBool; // 0x110
	private static DelegateBridge __Hotfix0_EnsureInt; // 0x118
	private static DelegateBridge __Hotfix0_EnsureString; // 0x120
	private static DelegateBridge __Hotfix0_GenerateBlackboardWithPrefix; // 0x128
	private static DelegateBridge __Hotfix1_GenerateBlackboardWithPrefix; // 0x130
	private static DelegateBridge __Hotfix0_AssignByPrefix; // 0x138
	private static DelegateBridge __Hotfix0_AssignValueStrByPrefix; // 0x140
	private static DelegateBridge __Hotfix0_AddBlackboardStrictly; // 0x148
	private static DelegateBridge __Hotfix0_AddBlackboardBaseOneStrictly; // 0x150
	private static DelegateBridge __Hotfix0__TryGetNumber; // 0x158
	private static DelegateBridge __Hotfix0__TryToStripPrefix; // 0x160


	// RVA: 0x33c1c44 VA: 0x75959d9c44
	public Void .ctor() { }
	// RVA: 0x33c1cec VA: 0x75959d9cec
	public Void .ctor(IList`1 another) { }
	// RVA: 0x33c1dcc VA: 0x75959d9dcc
	public Void .ctor(IList`1 another, Single scale, IList`1 exceptKeys, Boolean isScaleDeltaToOne) { }
	// RVA: 0x33c2138 VA: 0x75959da138
	public Void .ctor(IList`1 another, Single scale, IList`1 certainKeys, Boolean isCertain, Boolean isScaleDeltaToOne) { }
	// RVA: 0x33c24a0 VA: 0x75959da4a0
	public Void Reset(IList`1 another) { }
	// RVA: 0x33c257c VA: 0x75959da57c
	public Void Assign(IList`1 another) { }
	// RVA: 0x33c2948 VA: 0x75959da948
	public Void Assign(String key, Single value) { }
	// RVA: 0x33c2b98 VA: 0x75959dab98
	public Void RemoveKey(String key) { }
	// RVA: 0x33c2c98 VA: 0x75959dac98
	public Void Assign(String key, FP value) { }
	// RVA: 0x33c2d64 VA: 0x75959dad64
	public Void Assign(String key, String value) { }
	// RVA: 0x33c2fac VA: 0x75959dafac
	public Boolean ContainsKey(String key) { }
	// RVA: 0x33c275c VA: 0x75959da75c
	private Void _AssignInternal(DataPair item) { }
	// RVA: 0x33c30a8 VA: 0x75959db0a8
	public static Blackboard Of(IList`1 data) { }
	// RVA: 0x33c3138 VA: 0x75959db138
	public static Void MergeTo(ref Blackboard to, Blackboard from) { }
	// RVA: 0x33c3204 VA: 0x75959db204
	public static Void MergeTo(ref List`1 to, List`1 from) { }
	// RVA: 0x33c3488 VA: 0x75959db488
	public static Blackboard Union(Blackboard lhs, Blackboard rhs) { }
	// RVA: 0x33c353c VA: 0x75959db53c
	public Single GetFloat(String key) { }
	// RVA: 0x33c377c VA: 0x75959db77c
	public FP GetFP(String key) { }
	// RVA: 0x33c383c VA: 0x75959db83c
	public Int32 GetInt(String key) { }
	// RVA: 0x33c3924 VA: 0x75959db924
	public Boolean GetBool(String key) { }
	// RVA: 0x33c39f0 VA: 0x75959db9f0
	public String GetString(String key) { }
	// RVA: 0x33c3c44 VA: 0x75959dbc44
	public Boolean TryGetFloat(String key, out Single value) { }
	// RVA: 0x33c3cd0 VA: 0x75959dbcd0
	public Boolean TryGetFP(String key, out FP value) { }
	// RVA: 0x33c3dac VA: 0x75959dbdac
	public Boolean TryGetInt(String key, out Int32 value) { }
	// RVA: 0x33c3eb4 VA: 0x75959dbeb4
	public Boolean TryGetBool(String key, out Boolean value) { }
	// RVA: 0x33c3ad8 VA: 0x75959dbad8
	public Boolean TryGetString(String key, out String value) { }
	// RVA: 0x33c3fc0 VA: 0x75959dbfc0
	public Boolean TryGetInternalData(String key, out DataPair data) { }
	// RVA: 0x VA: 0x0
	public TEnum GetEnumOrDefault(String key, String defaultStr) { }
	// RVA: 0x33c4104 VA: 0x75959dc104
	public Single GetFloatOrDefault(String key, Single defaultValue, Boolean showWarning) { }
	// RVA: 0x33c41ac VA: 0x75959dc1ac
	public FP GetFpOrDefault(String key, FP defaultValue, Boolean showWarning) { }
	// RVA: 0x33c4254 VA: 0x75959dc254
	public Boolean GetBoolOrDefault(String key, Boolean defaultValue, Boolean showWarning) { }
	// RVA: 0x33c4308 VA: 0x75959dc308
	public Int32 GetIntOrDefault(String key, Int32 defaultValue, Boolean showWarning) { }
	// RVA: 0x33c43b0 VA: 0x75959dc3b0
	public String GetStringOrDefault(String key, String defaultValue, Boolean showWarning) { }
	// RVA: 0x33c4458 VA: 0x75959dc458
	public Single EnsureFloat(String key) { }
	// RVA: 0x33c4514 VA: 0x75959dc514
	public Boolean EnsureBool(String key) { }
	// RVA: 0x33c45c4 VA: 0x75959dc5c4
	public Int32 EnsureInt(String key) { }
	// RVA: 0x33c4668 VA: 0x75959dc668
	public String EnsureString(String key) { }
	// RVA: 0x33c4730 VA: 0x75959dc730
	public Void GenerateBlackboardWithPrefix(ref Blackboard blackboard, String prefix) { }
	// RVA: 0x33c4984 VA: 0x75959dc984
	public Blackboard GenerateBlackboardWithPrefix(String prefix) { }
	// RVA: 0x33c4b3c VA: 0x75959dcb3c
	public Void AssignByPrefix(IList`1 another, String prefixToStrip) { }
	// RVA: 0x33c4e40 VA: 0x75959dce40
	public Void AssignValueStrByPrefix(IList`1 another, String prefixToStrip) { }
	// RVA: 0x33c50c0 VA: 0x75959dd0c0
	public Void AddBlackboardStrictly(Blackboard other) { }
	// RVA: 0x33c5324 VA: 0x75959dd324
	public Void AddBlackboardBaseOneStrictly(Blackboard other) { }
	// RVA: 0x33c3624 VA: 0x75959db624
	private Boolean _TryGetNumber(String key, out Single value) { }
	// RVA: 0x33c4d4c VA: 0x75959dcd4c
	private Boolean _TryToStripPrefix(String key, String prefixToStrip, out String outKey) { }
}
```