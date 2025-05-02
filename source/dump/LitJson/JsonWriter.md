# JsonWriter

**Namespace:** `LitJson`


## Fields

- `WriterContext context`

- `Boolean has_reached_end`

- `Int32 indentation`

- `Int32 indent_value`

- `StringBuilder inst_string_builder`

- `Boolean pretty_print`

- `Boolean validate`

- `TextWriter writer`


## Properties

- `Int32 IndentValue`

- `Boolean PrettyPrint`

- `TextWriter TextWriter`

- `Boolean Validate`


## Methods

- `Int32 get_IndentValue()`

- `Void set_IndentValue(Int32)`

- `Boolean get_PrettyPrint()`

- `Void set_PrettyPrint(Boolean)`

- `TextWriter get_TextWriter()`

- `Boolean get_Validate()`

- `Void set_Validate(Boolean)`

- `Void DoValidation(Condition)`

- `Void Init()`

- `Void Indent()`

- `Void Put(String)`

- `Void PutNewline()`

- `Void PutNewline(Boolean)`

- `Void PutString(String)`

- `Void Unindent()`

- `Void Reset()`

- `Void Write(Boolean)`

- `Void Write(Decimal)`

- `Void Write(Double)`

- `Void Write(Int32)`

- `Void Write(Int64)`

- `Void Write(String)`

- `Void Write(UInt64)`

- `Void WriteArrayEnd()`

- `Void WriteArrayStart()`

- `Void WriteObjectEnd()`

- `Void WriteObjectStart()`

- `Void WritePropertyName(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
public class JsonWriter
{
	private static NumberFormatInfo number_format; // 0x0
	private WriterContext context; // 0x10
	private Stack`1 ctx_stack; // 0x18
	private Boolean has_reached_end; // 0x20
	private Char[] hex_seq; // 0x28
	private Int32 indentation; // 0x30
	private Int32 indent_value; // 0x34
	private StringBuilder inst_string_builder; // 0x38
	private Boolean pretty_print; // 0x40
	private Boolean validate; // 0x41
	private TextWriter writer; // 0x48

	public Int32 IndentValue { get; set; }
	public Boolean PrettyPrint { get; set; }
	public TextWriter TextWriter { get; }
	public Boolean Validate { get; set; }

	// RVA: 0x65f27a8 VA: 0x7598c0a7a8
	public Int32 get_IndentValue() { }
	// RVA: 0x65f27b0 VA: 0x7598c0a7b0
	public Void set_IndentValue(Int32 value) { }
	// RVA: 0x65f27c4 VA: 0x7598c0a7c4
	public Boolean get_PrettyPrint() { }
	// RVA: 0x65f27cc VA: 0x7598c0a7cc
	public Void set_PrettyPrint(Boolean value) { }
	// RVA: 0x65f27d8 VA: 0x7598c0a7d8
	public TextWriter get_TextWriter() { }
	// RVA: 0x65f27e0 VA: 0x7598c0a7e0
	public Boolean get_Validate() { }
	// RVA: 0x65f27e8 VA: 0x7598c0a7e8
	public Void set_Validate(Boolean value) { }
	// RVA: 0x65f27f4 VA: 0x7598c0a7f4
	private static Void .cctor() { }
	// RVA: 0x65e8428 VA: 0x7598c00428
	public Void .ctor() { }
	// RVA: 0x65f2984 VA: 0x7598c0a984
	public Void .ctor(StringBuilder sb) { }
	// RVA: 0x65f29f8 VA: 0x7598c0a9f8
	public Void .ctor(TextWriter writer) { }
	// RVA: 0x65f2a80 VA: 0x7598c0aa80
	private Void DoValidation(Condition cond) { }
	// RVA: 0x65f2850 VA: 0x7598c0a850
	private Void Init() { }
	// RVA: 0x65f2c1c VA: 0x7598c0ac1c
	private static Void IntToHex(Int32 n, Char[] hex) { }
	// RVA: 0x65f2c94 VA: 0x7598c0ac94
	private Void Indent() { }
	// RVA: 0x65f2cac VA: 0x7598c0acac
	private Void Put(String str) { }
	// RVA: 0x65f2d38 VA: 0x7598c0ad38
	private Void PutNewline() { }
	// RVA: 0x65f2d40 VA: 0x7598c0ad40
	private Void PutNewline(Boolean add_comma) { }
	// RVA: 0x65f2dc8 VA: 0x7598c0adc8
	private Void PutString(String str) { }
	// RVA: 0x65f30d0 VA: 0x7598c0b0d0
	private Void Unindent() { }
	// RVA: 0x65f30e8 VA: 0x7598c0b0e8
	public override String ToString() { }
	// RVA: 0x65ef870 VA: 0x7598c07870
	public Void Reset() { }
	// RVA: 0x65eefb8 VA: 0x7598c06fb8
	public Void Write(Boolean boolean) { }
	// RVA: 0x65f0458 VA: 0x7598c08458
	public Void Write(Decimal number) { }
	// RVA: 0x65eeda8 VA: 0x7598c06da8
	public Void Write(Double number) { }
	// RVA: 0x65eeee4 VA: 0x7598c06ee4
	public Void Write(Int32 number) { }
	// RVA: 0x65ef050 VA: 0x7598c07050
	public Void Write(Int64 number) { }
	// RVA: 0x65eed1c VA: 0x7598c06d1c
	public Void Write(String str) { }
	// RVA: 0x65ef624 VA: 0x7598c07624
	public Void Write(UInt64 number) { }
	// RVA: 0x65ef21c VA: 0x7598c0721c
	public Void WriteArrayEnd() { }
	// RVA: 0x65ef124 VA: 0x7598c07124
	public Void WriteArrayStart() { }
	// RVA: 0x65ef524 VA: 0x7598c07524
	public Void WriteObjectEnd() { }
	// RVA: 0x65ef31c VA: 0x7598c0731c
	public Void WriteObjectStart() { }
	// RVA: 0x65ef414 VA: 0x7598c07414
	public Void WritePropertyName(String property_name) { }
}
```