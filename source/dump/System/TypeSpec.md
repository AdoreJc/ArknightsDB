# TypeSpec

**Namespace:** `System`


## Fields

- `TypeIdentifier name`

- `String assembly_name`

- `Boolean is_byref`

- `String display_fullname`


## Methods

- `String GetDisplayFullName(DisplayNameFormat)`

- `StringBuilder GetModifierString(StringBuilder)`

- `Void AddName(String)`

- `Void AddModifier(ModifierSpec)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class TypeSpec
{
	private TypeIdentifier name; // 0x10
	private String assembly_name; // 0x18
	private List`1 nested; // 0x20
	private List`1 generic_params; // 0x28
	private List`1 modifier_spec; // 0x30
	private Boolean is_byref; // 0x38
	private String display_fullname; // 0x40

	internal Boolean HasModifiers { get; }
	internal String DisplayFullName { get; }

	// RVA: 0x610d8a0 VA: 0x75987258a0
	internal Boolean get_HasModifiers() { }
	// RVA: 0x610d8b0 VA: 0x75987258b0
	private String GetDisplayFullName(DisplayNameFormat flags) { }
	// RVA: 0x610dd20 VA: 0x7598725d20
	private StringBuilder GetModifierString(StringBuilder sb) { }
	// RVA: 0x610dcdc VA: 0x7598725cdc
	internal String get_DisplayFullName() { }
	// RVA: 0x610df14 VA: 0x7598725f14
	internal static TypeSpec Parse(String typeName) { }
	// RVA: 0x610d4f8 VA: 0x75987254f8
	internal static String UnescapeInternalName(String displayName) { }
	// RVA: 0x610ebec VA: 0x7598726bec
	internal Type Resolve(Func`2 assemblyResolver, Func`4 typeResolver, Boolean throwOnError, Boolean ignoreCase, ref StackCrawlMark stackMark) { }
	// RVA: 0x610f524 VA: 0x7598727524
	private Void AddName(String type_name) { }
	// RVA: 0x610f664 VA: 0x7598727664
	private Void AddModifier(ModifierSpec md) { }
	// RVA: 0x610f76c VA: 0x759872776c
	private static Void SkipSpace(String name, ref Int32 pos) { }
	// RVA: 0x610f81c VA: 0x759872781c
	private static Void BoundCheck(Int32 idx, String s) { }
	// RVA: 0x610f660 VA: 0x7598727660
	private static TypeIdentifier ParsedTypeIdentifier(String displayName) { }
	// RVA: 0x610dfec VA: 0x7598725fec
	private static TypeSpec Parse(String name, ref Int32 p, Boolean is_recurse, Boolean allow_aqn) { }
	// RVA: 0x610f8a4 VA: 0x75987278a4
	public Void .ctor() { }
}
```