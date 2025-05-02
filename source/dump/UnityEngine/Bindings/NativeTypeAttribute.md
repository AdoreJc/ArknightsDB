# NativeTypeAttribute

**Namespace:** `UnityEngine.Bindings`


## Fields

- `String <Header>k__BackingField`

- `String <IntermediateScriptingStructName>k__BackingField`

- `CodegenOptions <CodegenOptions>k__BackingField`


## Properties

- `String Header`

- `String IntermediateScriptingStructName`

- `CodegenOptions CodegenOptions`


## Methods

- `Void set_Header(String)`

- `Void set_IntermediateScriptingStructName(String)`

- `Void set_CodegenOptions(CodegenOptions)`


## Dump
```C#
// Dll : UnityEngine.SharedInternalsModule.dll
// Namespace : UnityEngine.Bindings
internal class NativeTypeAttribute : Attribute
{
	private String <Header>k__BackingField; // 0x10
	private String <IntermediateScriptingStructName>k__BackingField; // 0x18
	private CodegenOptions <CodegenOptions>k__BackingField; // 0x20

	public String Header { set; }
	public String IntermediateScriptingStructName { set; }
	public CodegenOptions CodegenOptions { set; }

	// RVA: 0x68e17d8 VA: 0x7598ef97d8
	public Void set_Header(String value) { }
	// RVA: 0x68e17e0 VA: 0x7598ef97e0
	public Void set_IntermediateScriptingStructName(String value) { }
	// RVA: 0x68e17e8 VA: 0x7598ef97e8
	public Void set_CodegenOptions(CodegenOptions value) { }
	// RVA: 0x68e17f0 VA: 0x7598ef97f0
	public Void .ctor() { }
	// RVA: 0x68e180c VA: 0x7598ef980c
	public Void .ctor(CodegenOptions codegenOptions) { }
	// RVA: 0x68e1834 VA: 0x7598ef9834
	public Void .ctor(String header) { }
	// RVA: 0x68e1944 VA: 0x7598ef9944
	public Void .ctor(CodegenOptions codegenOptions, String intermediateStructName) { }
}
```