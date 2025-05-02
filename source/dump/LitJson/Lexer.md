# Lexer

**Namespace:** `LitJson`


## Fields

- `Boolean allow_comments`

- `Boolean allow_single_quoted_strings`

- `Boolean end_of_input`

- `FsmContext fsm_context`

- `Int32 input_buffer`

- `Int32 input_char`

- `TextReader reader`

- `Int32 state`

- `StringBuilder string_buffer`

- `String string_value`

- `Int32 token`

- `Int32 unichar`


## Properties

- `Boolean AllowComments`

- `Boolean AllowSingleQuotedStrings`

- `Boolean EndOfInput`

- `Int32 Token`

- `String StringValue`


## Methods

- `Boolean get_AllowComments()`

- `Void set_AllowComments(Boolean)`

- `Boolean get_AllowSingleQuotedStrings()`

- `Void set_AllowSingleQuotedStrings(Boolean)`

- `Boolean get_EndOfInput()`

- `Int32 get_Token()`

- `String get_StringValue()`

- `Boolean GetChar()`

- `Int32 NextChar()`

- `Boolean NextToken()`

- `Void UngetChar()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
internal class Lexer
{
	private static Int32[] fsm_return_table; // 0x0
	private static StateHandler[] fsm_handler_table; // 0x8
	private Boolean allow_comments; // 0x10
	private Boolean allow_single_quoted_strings; // 0x11
	private Boolean end_of_input; // 0x12
	private FsmContext fsm_context; // 0x18
	private Int32 input_buffer; // 0x20
	private Int32 input_char; // 0x24
	private TextReader reader; // 0x28
	private Int32 state; // 0x30
	private StringBuilder string_buffer; // 0x38
	private String string_value; // 0x40
	private Int32 token; // 0x48
	private Int32 unichar; // 0x4c

	public Boolean AllowComments { get; set; }
	public Boolean AllowSingleQuotedStrings { get; set; }
	public Boolean EndOfInput { get; }
	public Int32 Token { get; }
	public String StringValue { get; }

	// RVA: 0x65f3158 VA: 0x7598c0b158
	public Boolean get_AllowComments() { }
	// RVA: 0x65f3160 VA: 0x7598c0b160
	public Void set_AllowComments(Boolean value) { }
	// RVA: 0x65f316c VA: 0x7598c0b16c
	public Boolean get_AllowSingleQuotedStrings() { }
	// RVA: 0x65f3174 VA: 0x7598c0b174
	public Void set_AllowSingleQuotedStrings(Boolean value) { }
	// RVA: 0x65f3180 VA: 0x7598c0b180
	public Boolean get_EndOfInput() { }
	// RVA: 0x65f3188 VA: 0x7598c0b188
	public Int32 get_Token() { }
	// RVA: 0x65f3190 VA: 0x7598c0b190
	public String get_StringValue() { }
	// RVA: 0x65f3198 VA: 0x7598c0b198
	private static Void .cctor() { }
	// RVA: 0x65f1e88 VA: 0x7598c09e88
	public Void .ctor(TextReader reader) { }
	// RVA: 0x65f3d34 VA: 0x7598c0bd34
	private static Int32 HexValue(Int32 digit) { }
	// RVA: 0x65f319c VA: 0x7598c0b19c
	private static Void PopulateFsmTables() { }
	// RVA: 0x65f3ef4 VA: 0x7598c0bef4
	private static Char ProcessEscChar(Int32 esc_char) { }
	// RVA: 0x65f3fe4 VA: 0x7598c0bfe4
	private static Boolean State1(FsmContext ctx) { }
	// RVA: 0x65f41e8 VA: 0x7598c0c1e8
	private static Boolean State2(FsmContext ctx) { }
	// RVA: 0x65f428c VA: 0x7598c0c28c
	private static Boolean State3(FsmContext ctx) { }
	// RVA: 0x65f43c8 VA: 0x7598c0c3c8
	private static Boolean State4(FsmContext ctx) { }
	// RVA: 0x65f44c4 VA: 0x7598c0c4c4
	private static Boolean State5(FsmContext ctx) { }
	// RVA: 0x65f4544 VA: 0x7598c0c544
	private static Boolean State6(FsmContext ctx) { }
	// RVA: 0x65f4640 VA: 0x7598c0c640
	private static Boolean State7(FsmContext ctx) { }
	// RVA: 0x65f46d4 VA: 0x7598c0c6d4
	private static Boolean State8(FsmContext ctx) { }
	// RVA: 0x65f4790 VA: 0x7598c0c790
	private static Boolean State9(FsmContext ctx) { }
	// RVA: 0x65f47fc VA: 0x7598c0c7fc
	private static Boolean State10(FsmContext ctx) { }
	// RVA: 0x65f4868 VA: 0x7598c0c868
	private static Boolean State11(FsmContext ctx) { }
	// RVA: 0x65f48d4 VA: 0x7598c0c8d4
	private static Boolean State12(FsmContext ctx) { }
	// RVA: 0x65f4940 VA: 0x7598c0c940
	private static Boolean State13(FsmContext ctx) { }
	// RVA: 0x65f49ac VA: 0x7598c0c9ac
	private static Boolean State14(FsmContext ctx) { }
	// RVA: 0x65f4a18 VA: 0x7598c0ca18
	private static Boolean State15(FsmContext ctx) { }
	// RVA: 0x65f4a84 VA: 0x7598c0ca84
	private static Boolean State16(FsmContext ctx) { }
	// RVA: 0x65f4af0 VA: 0x7598c0caf0
	private static Boolean State17(FsmContext ctx) { }
	// RVA: 0x65f4b5c VA: 0x7598c0cb5c
	private static Boolean State18(FsmContext ctx) { }
	// RVA: 0x65f4bc8 VA: 0x7598c0cbc8
	private static Boolean State19(FsmContext ctx) { }
	// RVA: 0x65f4c70 VA: 0x7598c0cc70
	private static Boolean State20(FsmContext ctx) { }
	// RVA: 0x65f4cdc VA: 0x7598c0ccdc
	private static Boolean State21(FsmContext ctx) { }
	// RVA: 0x65f4e14 VA: 0x7598c0ce14
	private static Boolean State22(FsmContext ctx) { }
	// RVA: 0x65f4f90 VA: 0x7598c0cf90
	private static Boolean State23(FsmContext ctx) { }
	// RVA: 0x65f5038 VA: 0x7598c0d038
	private static Boolean State24(FsmContext ctx) { }
	// RVA: 0x65f50ac VA: 0x7598c0d0ac
	private static Boolean State25(FsmContext ctx) { }
	// RVA: 0x65f5128 VA: 0x7598c0d128
	private static Boolean State26(FsmContext ctx) { }
	// RVA: 0x65f5190 VA: 0x7598c0d190
	private static Boolean State27(FsmContext ctx) { }
	// RVA: 0x65f51f8 VA: 0x7598c0d1f8
	private static Boolean State28(FsmContext ctx) { }
	// RVA: 0x65f41bc VA: 0x7598c0c1bc
	private Boolean GetChar() { }
	// RVA: 0x65f5270 VA: 0x7598c0d270
	private Int32 NextChar() { }
	// RVA: 0x65f257c VA: 0x7598c0a57c
	public Boolean NextToken() { }
	// RVA: 0x65f43bc VA: 0x7598c0c3bc
	private Void UngetChar() { }
}
```