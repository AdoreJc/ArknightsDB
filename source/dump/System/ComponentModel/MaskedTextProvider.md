# MaskedTextProvider

**Namespace:** `System.ComponentModel`


## Fields

- `BitVector32 _flagState`

- `StringBuilder _testString`

- `Int32 _requiredCharCount`

- `Int32 _requiredEditChars`

- `Int32 _optionalEditChars`

- `Char _passwordChar`

- `Char _promptChar`

- `Int32 <AssignedEditPositionCount>k__BackingField`


## Properties

- `Boolean AllowPromptAsInput`

- `Int32 AssignedEditPositionCount`

- `Int32 AvailableEditPositionCount`

- `CultureInfo Culture`

- `Int32 EditPositionCount`

- `IEnumerator EditPositions`

- `Boolean IncludeLiterals`

- `Boolean IncludePrompt`

- `Boolean AsciiOnly`

- `Boolean IsPassword`

- `Int32 LastAssignedPosition`

- `Int32 Length`

- `String Mask`

- `Boolean MaskCompleted`

- `Boolean MaskFull`

- `Char PasswordChar`

- `Char PromptChar`

- `Boolean ResetOnPrompt`

- `Boolean ResetOnSpace`

- `Boolean SkipLiterals`

- `Char Item`


## Methods

- `Void Initialize()`

- `Boolean get_AllowPromptAsInput()`

- `Int32 get_AssignedEditPositionCount()`

- `Void set_AssignedEditPositionCount(Int32)`

- `Int32 get_AvailableEditPositionCount()`

- `Object Clone()`

- `CultureInfo get_Culture()`

- `Int32 get_EditPositionCount()`

- `IEnumerator get_EditPositions()`

- `Boolean get_IncludeLiterals()`

- `Void set_IncludeLiterals(Boolean)`

- `Boolean get_IncludePrompt()`

- `Void set_IncludePrompt(Boolean)`

- `Boolean get_AsciiOnly()`

- `Boolean get_IsPassword()`

- `Void set_IsPassword(Boolean)`

- `Int32 get_LastAssignedPosition()`

- `Int32 get_Length()`

- `String get_Mask()`

- `Boolean get_MaskCompleted()`

- `Boolean get_MaskFull()`

- `Char get_PasswordChar()`

- `Void set_PasswordChar(Char)`

- `Char get_PromptChar()`

- `Void set_PromptChar(Char)`

- `Boolean get_ResetOnPrompt()`

- `Void set_ResetOnPrompt(Boolean)`

- `Boolean get_ResetOnSpace()`

- `Void set_ResetOnSpace(Boolean)`

- `Boolean get_SkipLiterals()`

- `Void set_SkipLiterals(Boolean)`

- `Char get_Item(Int32)`

- `Boolean Add(Char)`

- `Boolean Add(Char, out, out)`

- `Boolean Add(String)`

- `Boolean Add(String, out, out)`

- `Void Clear()`

- `Void Clear(out)`

- `Int32 FindAssignedEditPositionFrom(Int32, Boolean)`

- `Int32 FindAssignedEditPositionInRange(Int32, Int32, Boolean)`

- `Int32 FindEditPositionFrom(Int32, Boolean)`

- `Int32 FindEditPositionInRange(Int32, Int32, Boolean)`

- `Int32 FindEditPositionInRange(Int32, Int32, Boolean, Byte)`

- `Int32 FindNonEditPositionFrom(Int32, Boolean)`

- `Int32 FindNonEditPositionInRange(Int32, Int32, Boolean)`

- `Int32 FindPositionInRange(Int32, Int32, Boolean, CharType)`

- `Int32 FindUnassignedEditPositionFrom(Int32, Boolean)`

- `Int32 FindUnassignedEditPositionInRange(Int32, Int32, Boolean)`

- `Boolean InsertAt(Char, Int32)`

- `Boolean InsertAt(Char, Int32, out, out)`

- `Boolean InsertAt(String, Int32)`

- `Boolean InsertAt(String, Int32, out, out)`

- `Boolean InsertAtInt(String, Int32, out, out, Boolean)`

- `Boolean IsAvailablePosition(Int32)`

- `Boolean IsEditPosition(Int32)`

- `Boolean Remove()`

- `Boolean Remove(out, out)`

- `Boolean RemoveAt(Int32)`

- `Boolean RemoveAt(Int32, Int32)`

- `Boolean RemoveAt(Int32, Int32, out, out)`

- `Boolean RemoveAtInt(Int32, Int32, out, out, Boolean)`

- `Boolean Replace(Char, Int32)`

- `Boolean Replace(Char, Int32, out, out)`

- `Boolean Replace(Char, Int32, Int32, out, out)`

- `Boolean Replace(String, Int32)`

- `Boolean Replace(String, Int32, out, out)`

- `Boolean Replace(String, Int32, Int32, out, out)`

- `Void ResetChar(Int32)`

- `Void ResetString(Int32, Int32)`

- `Boolean Set(String)`

- `Boolean Set(String, out, out)`

- `Void SetChar(Char, Int32)`

- `Void SetChar(Char, Int32, CharDescriptor)`

- `Void SetString(String, Int32)`

- `Boolean TestChar(Char, Int32, out)`

- `Boolean TestEscapeChar(Char, Int32)`

- `Boolean TestEscapeChar(Char, Int32, CharDescriptor)`

- `Boolean TestSetChar(Char, Int32, out)`

- `Boolean TestSetString(String, Int32, out, out)`

- `Boolean TestString(String, Int32, out, out)`

- `String ToDisplayString()`

- `String ToString(Boolean)`

- `String ToString(Int32, Int32)`

- `String ToString(Boolean, Int32, Int32)`

- `String ToString(Boolean, Boolean)`

- `String ToString(Boolean, Boolean, Int32, Int32)`

- `String ToString(Boolean, Boolean, Boolean, Int32, Int32)`

- `Boolean VerifyChar(Char, Int32, out)`

- `Boolean VerifyEscapeChar(Char, Int32)`

- `Boolean VerifyString(String)`

- `Boolean VerifyString(String, out, out)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class MaskedTextProvider : ICloneable
{
	private const Char SPACE_CHAR; // 0x0
	private const Char DEFAULT_PROMPT_CHAR; // 0x0
	private const Char NULL_PASSWORD_CHAR; // 0x0
	private const Boolean DEFAULT_ALLOW_PROMPT; // 0x0
	private const Int32 INVALID_INDEX; // 0x0
	private const Byte EDIT_ANY; // 0x0
	private const Byte EDIT_UNASSIGNED; // 0x0
	private const Byte EDIT_ASSIGNED; // 0x0
	private const Boolean FORWARD; // 0x0
	private const Boolean BACKWARD; // 0x0
	private static Int32 s_ASCII_ONLY; // 0x0
	private static Int32 s_ALLOW_PROMPT_AS_INPUT; // 0x4
	private static Int32 s_INCLUDE_PROMPT; // 0x8
	private static Int32 s_INCLUDE_LITERALS; // 0xc
	private static Int32 s_RESET_ON_PROMPT; // 0x10
	private static Int32 s_RESET_ON_LITERALS; // 0x14
	private static Int32 s_SKIP_SPACE; // 0x18
	private static Type s_maskTextProviderType; // 0x20
	private BitVector32 _flagState; // 0x10
	private StringBuilder _testString; // 0x18
	private Int32 _requiredCharCount; // 0x20
	private Int32 _requiredEditChars; // 0x24
	private Int32 _optionalEditChars; // 0x28
	private Char _passwordChar; // 0x2c
	private Char _promptChar; // 0x2e
	private List`1 _stringDescriptor; // 0x30
	private Int32 <AssignedEditPositionCount>k__BackingField; // 0x38
	private readonly CultureInfo <Culture>k__BackingField; // 0x40
	private readonly String <Mask>k__BackingField; // 0x48

	public Boolean AllowPromptAsInput { get; }
	public Int32 AssignedEditPositionCount { get; set; }
	public Int32 AvailableEditPositionCount { get; }
	public CultureInfo Culture { get; }
	public static Char DefaultPasswordChar { get; }
	public Int32 EditPositionCount { get; }
	public IEnumerator EditPositions { get; }
	public Boolean IncludeLiterals { get; set; }
	public Boolean IncludePrompt { get; set; }
	public Boolean AsciiOnly { get; }
	public Boolean IsPassword { get; set; }
	public static Int32 InvalidIndex { get; }
	public Int32 LastAssignedPosition { get; }
	public Int32 Length { get; }
	public String Mask { get; }
	public Boolean MaskCompleted { get; }
	public Boolean MaskFull { get; }
	public Char PasswordChar { get; set; }
	public Char PromptChar { get; set; }
	public Boolean ResetOnPrompt { get; set; }
	public Boolean ResetOnSpace { get; set; }
	public Boolean SkipLiterals { get; set; }
	public Char Item { get; }

	// RVA: 0x63c8614 VA: 0x75989e0614
	public Void .ctor(String mask) { }
	// RVA: 0x63c8a4c VA: 0x75989e0a4c
	public Void .ctor(String mask, Boolean restrictToAscii) { }
	// RVA: 0x63c8a64 VA: 0x75989e0a64
	public Void .ctor(String mask, CultureInfo culture) { }
	// RVA: 0x63c8a78 VA: 0x75989e0a78
	public Void .ctor(String mask, CultureInfo culture, Boolean restrictToAscii) { }
	// RVA: 0x63c8a8c VA: 0x75989e0a8c
	public Void .ctor(String mask, Char passwordChar, Boolean allowPromptAsInput) { }
	// RVA: 0x63c8aa4 VA: 0x75989e0aa4
	public Void .ctor(String mask, CultureInfo culture, Char passwordChar, Boolean allowPromptAsInput) { }
	// RVA: 0x63c862c VA: 0x75989e062c
	public Void .ctor(String mask, CultureInfo culture, Boolean allowPromptAsInput, Char promptChar, Char passwordChar, Boolean restrictToAscii) { }
	// RVA: 0x63c8b70 VA: 0x75989e0b70
	private Void Initialize() { }
	// RVA: 0x63c9024 VA: 0x75989e1024
	public Boolean get_AllowPromptAsInput() { }
	// RVA: 0x63c908c VA: 0x75989e108c
	public Int32 get_AssignedEditPositionCount() { }
	// RVA: 0x63c9094 VA: 0x75989e1094
	private Void set_AssignedEditPositionCount(Int32 value) { }
	// RVA: 0x63c909c VA: 0x75989e109c
	public Int32 get_AvailableEditPositionCount() { }
	// RVA: 0x63c90bc VA: 0x75989e10bc
	public Object Clone() { }
	// RVA: 0x63c9a70 VA: 0x75989e1a70
	public CultureInfo get_Culture() { }
	// RVA: 0x63c9a78 VA: 0x75989e1a78
	public static Char get_DefaultPasswordChar() { }
	// RVA: 0x63c90b0 VA: 0x75989e10b0
	public Int32 get_EditPositionCount() { }
	// RVA: 0x63c9a80 VA: 0x75989e1a80
	public IEnumerator get_EditPositions() { }
	// RVA: 0x63c98b0 VA: 0x75989e18b0
	public Boolean get_IncludeLiterals() { }
	// RVA: 0x63c9918 VA: 0x75989e1918
	public Void set_IncludeLiterals(Boolean value) { }
	// RVA: 0x63c9990 VA: 0x75989e1990
	public Boolean get_IncludePrompt() { }
	// RVA: 0x63c99f8 VA: 0x75989e19f8
	public Void set_IncludePrompt(Boolean value) { }
	// RVA: 0x63c9588 VA: 0x75989e1588
	public Boolean get_AsciiOnly() { }
	// RVA: 0x63c9d48 VA: 0x75989e1d48
	public Boolean get_IsPassword() { }
	// RVA: 0x63c9d58 VA: 0x75989e1d58
	public Void set_IsPassword(Boolean value) { }
	// RVA: 0x63c9dd4 VA: 0x75989e1dd4
	public static Int32 get_InvalidIndex() { }
	// RVA: 0x63c9ddc VA: 0x75989e1ddc
	public Int32 get_LastAssignedPosition() { }
	// RVA: 0x63c9ea4 VA: 0x75989e1ea4
	public Int32 get_Length() { }
	// RVA: 0x63c9ec0 VA: 0x75989e1ec0
	public String get_Mask() { }
	// RVA: 0x63c9ec8 VA: 0x75989e1ec8
	public Boolean get_MaskCompleted() { }
	// RVA: 0x63c9ed8 VA: 0x75989e1ed8
	public Boolean get_MaskFull() { }
	// RVA: 0x63c9ef0 VA: 0x75989e1ef0
	public Char get_PasswordChar() { }
	// RVA: 0x63c9ef8 VA: 0x75989e1ef8
	public Void set_PasswordChar(Char value) { }
	// RVA: 0x63ca068 VA: 0x75989e2068
	public Char get_PromptChar() { }
	// RVA: 0x63ca070 VA: 0x75989e2070
	public Void set_PromptChar(Char value) { }
	// RVA: 0x63c9778 VA: 0x75989e1778
	public Boolean get_ResetOnPrompt() { }
	// RVA: 0x63c95f0 VA: 0x75989e15f0
	public Void set_ResetOnPrompt(Boolean value) { }
	// RVA: 0x63c97e0 VA: 0x75989e17e0
	public Boolean get_ResetOnSpace() { }
	// RVA: 0x63c9668 VA: 0x75989e1668
	public Void set_ResetOnSpace(Boolean value) { }
	// RVA: 0x63c9848 VA: 0x75989e1848
	public Boolean get_SkipLiterals() { }
	// RVA: 0x63c96e0 VA: 0x75989e16e0
	public Void set_SkipLiterals(Boolean value) { }
	// RVA: 0x63ca2c4 VA: 0x75989e22c4
	public Char get_Item(Int32 index) { }
	// RVA: 0x63ca380 VA: 0x75989e2380
	public Boolean Add(Char input) { }
	// RVA: 0x63ca3a0 VA: 0x75989e23a0
	public Boolean Add(Char input, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63ca530 VA: 0x75989e2530
	public Boolean Add(String input) { }
	// RVA: 0x63ca550 VA: 0x75989e2550
	public Boolean Add(String input, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63ca650 VA: 0x75989e2650
	public Void Clear() { }
	// RVA: 0x63ca668 VA: 0x75989e2668
	public Void Clear(out MaskedTextResultHint resultHint) { }
	// RVA: 0x63c9e28 VA: 0x75989e1e28
	public Int32 FindAssignedEditPositionFrom(Int32 position, Boolean direction) { }
	// RVA: 0x63ca78c VA: 0x75989e278c
	public Int32 FindAssignedEditPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction) { }
	// RVA: 0x63ca478 VA: 0x75989e2478
	public Int32 FindEditPositionFrom(Int32 position, Boolean direction) { }
	// RVA: 0x63ca8a0 VA: 0x75989e28a0
	public Int32 FindEditPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction) { }
	// RVA: 0x63ca7a8 VA: 0x75989e27a8
	private Int32 FindEditPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction, Byte assignedStatus) { }
	// RVA: 0x63ca9a4 VA: 0x75989e29a4
	public Int32 FindNonEditPositionFrom(Int32 position, Boolean direction) { }
	// RVA: 0x63ca9fc VA: 0x75989e29fc
	public Int32 FindNonEditPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction) { }
	// RVA: 0x63ca8ac VA: 0x75989e28ac
	private Int32 FindPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction, CharType charTypeFlags) { }
	// RVA: 0x63caa08 VA: 0x75989e2a08
	public Int32 FindUnassignedEditPositionFrom(Int32 position, Boolean direction) { }
	// RVA: 0x63caa60 VA: 0x75989e2a60
	public Int32 FindUnassignedEditPositionInRange(Int32 startPosition, Int32 endPosition, Boolean direction) { }
	// RVA: 0x63cab78 VA: 0x75989e2b78
	public static Boolean GetOperationResultFromHint(MaskedTextResultHint hint) { }
	// RVA: 0x63cab84 VA: 0x75989e2b84
	public Boolean InsertAt(Char input, Int32 position) { }
	// RVA: 0x63cac58 VA: 0x75989e2c58
	public Boolean InsertAt(Char input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cac38 VA: 0x75989e2c38
	public Boolean InsertAt(String input, Int32 position) { }
	// RVA: 0x63cacf0 VA: 0x75989e2cf0
	public Boolean InsertAt(String input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cadc8 VA: 0x75989e2dc8
	private Boolean InsertAtInt(String input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint, Boolean testOnly) { }
	// RVA: 0x63cb7ec VA: 0x75989e37ec
	private static Boolean IsAscii(Char c) { }
	// RVA: 0x63cb800 VA: 0x75989e3800
	private static Boolean IsAciiAlphanumeric(Char c) { }
	// RVA: 0x63cb83c VA: 0x75989e383c
	private static Boolean IsAlphanumeric(Char c) { }
	// RVA: 0x63cb8c4 VA: 0x75989e38c4
	private static Boolean IsAsciiLetter(Char c) { }
	// RVA: 0x63cb8f0 VA: 0x75989e38f0
	public Boolean IsAvailablePosition(Int32 position) { }
	// RVA: 0x63ca204 VA: 0x75989e2204
	public Boolean IsEditPosition(Int32 position) { }
	// RVA: 0x63c9000 VA: 0x75989e1000
	private static Boolean IsEditPosition(CharDescriptor charDescriptor) { }
	// RVA: 0x63cb9bc VA: 0x75989e39bc
	private static Boolean IsLiteralPosition(CharDescriptor charDescriptor) { }
	// RVA: 0x63c8ab8 VA: 0x75989e0ab8
	private static Boolean IsPrintableChar(Char c) { }
	// RVA: 0x63cb9e8 VA: 0x75989e39e8
	public static Boolean IsValidInputChar(Char c) { }
	// RVA: 0x63cba3c VA: 0x75989e3a3c
	public static Boolean IsValidMaskChar(Char c) { }
	// RVA: 0x63ca000 VA: 0x75989e2000
	public static Boolean IsValidPasswordChar(Char c) { }
	// RVA: 0x63cba90 VA: 0x75989e3a90
	public Boolean Remove() { }
	// RVA: 0x63cbabc VA: 0x75989e3abc
	public Boolean Remove(out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cbb1c VA: 0x75989e3b1c
	public Boolean RemoveAt(Int32 position) { }
	// RVA: 0x63cbb40 VA: 0x75989e3b40
	public Boolean RemoveAt(Int32 startPosition, Int32 endPosition) { }
	// RVA: 0x63cbb60 VA: 0x75989e3b60
	public Boolean RemoveAt(Int32 startPosition, Int32 endPosition, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cbbf8 VA: 0x75989e3bf8
	private Boolean RemoveAtInt(Int32 startPosition, Int32 endPosition, out Int32 testPosition, out MaskedTextResultHint resultHint, Boolean testOnly) { }
	// RVA: 0x63c9758 VA: 0x75989e1758
	public Boolean Replace(Char input, Int32 position) { }
	// RVA: 0x63cbf54 VA: 0x75989e3f54
	public Boolean Replace(Char input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cc098 VA: 0x75989e4098
	public Boolean Replace(Char input, Int32 startPosition, Int32 endPosition, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cc4b0 VA: 0x75989e44b0
	public Boolean Replace(String input, Int32 position) { }
	// RVA: 0x63cc4d0 VA: 0x75989e44d0
	public Boolean Replace(String input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cc1bc VA: 0x75989e41bc
	public Boolean Replace(String input, Int32 startPosition, Int32 endPosition, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63ca6d0 VA: 0x75989e26d0
	private Void ResetChar(Int32 testPosition) { }
	// RVA: 0x63cbec8 VA: 0x75989e3ec8
	private Void ResetString(Int32 startPosition, Int32 endPosition) { }
	// RVA: 0x63cc5d0 VA: 0x75989e45d0
	public Boolean Set(String input) { }
	// RVA: 0x63cc5f0 VA: 0x75989e45f0
	public Boolean Set(String input, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cb6d4 VA: 0x75989e36d4
	private Void SetChar(Char input, Int32 position) { }
	// RVA: 0x63cc6e8 VA: 0x75989e46e8
	private Void SetChar(Char input, Int32 position, CharDescriptor charDescriptor) { }
	// RVA: 0x63cb74c VA: 0x75989e374c
	private Void SetString(String input, Int32 testPosition) { }
	// RVA: 0x63cb244 VA: 0x75989e3244
	private Boolean TestChar(Char input, Int32 position, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cc020 VA: 0x75989e4020
	private Boolean TestEscapeChar(Char input, Int32 position) { }
	// RVA: 0x63cc890 VA: 0x75989e4890
	private Boolean TestEscapeChar(Char input, Int32 position, CharDescriptor charDex) { }
	// RVA: 0x63ca4d0 VA: 0x75989e24d0
	private Boolean TestSetChar(Char input, Int32 position, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63ca60c VA: 0x75989e260c
	private Boolean TestSetString(String input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cb0e0 VA: 0x75989e30e0
	private Boolean TestString(String input, Int32 position, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cc988 VA: 0x75989e4988
	public String ToDisplayString() { }
	// RVA: 0x63ccb04 VA: 0x75989e4b04
	public override String ToString() { }
	// RVA: 0x63cce54 VA: 0x75989e4e54
	public String ToString(Boolean ignorePasswordChar) { }
	// RVA: 0x63ccebc VA: 0x75989e4ebc
	public String ToString(Int32 startPosition, Int32 length) { }
	// RVA: 0x63ccf0c VA: 0x75989e4f0c
	public String ToString(Boolean ignorePasswordChar, Int32 startPosition, Int32 length) { }
	// RVA: 0x63ccf60 VA: 0x75989e4f60
	public String ToString(Boolean includePrompt, Boolean includeLiterals) { }
	// RVA: 0x63ccfac VA: 0x75989e4fac
	public String ToString(Boolean includePrompt, Boolean includeLiterals, Int32 startPosition, Int32 length) { }
	// RVA: 0x63ccb60 VA: 0x75989e4b60
	public String ToString(Boolean ignorePasswordChar, Boolean includePrompt, Boolean includeLiterals, Int32 startPosition, Int32 length) { }
	// RVA: 0x63ccfc8 VA: 0x75989e4fc8
	public Boolean VerifyChar(Char input, Int32 position, out MaskedTextResultHint hint) { }
	// RVA: 0x63cd048 VA: 0x75989e5048
	public Boolean VerifyEscapeChar(Char input, Int32 position) { }
	// RVA: 0x63cd0a4 VA: 0x75989e50a4
	public Boolean VerifyString(String input) { }
	// RVA: 0x63cd0e4 VA: 0x75989e50e4
	public Boolean VerifyString(String input, out Int32 testPosition, out MaskedTextResultHint resultHint) { }
	// RVA: 0x63cd114 VA: 0x75989e5114
	private static Void .cctor() { }
}
```