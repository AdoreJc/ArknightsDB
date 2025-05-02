# AVGParser

**Namespace:** `Torappu.AVG`


## Fields

- `IAVGVariableConverter <variableConverter>k__BackingField`


## Properties

- `IAVGVariableConverter variableConverter`


## Methods

- `IAVGVariableConverter get_variableConverter()`

- `Void set_variableConverter(IAVGVariableConverter)`

- `Boolean TryParse(String, out)`

- `Void _StoreOriginLinesToCmd(Command, TextBlock)`

- `Boolean TryParse(String, out)`

- `Boolean TryParse(String, StoryParam, out)`

- `String GetErrorMessage()`

- `Void _AppendError(String)`

- `Command _ParseCommand(TextBlock)`

- `TextBlock _ReadNextBlock(StringReader)`

- `String _ReplaceEqualSignWithColon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGParser : IAVGParser
{
	private const Char ESCAPE_CHAR; // 0x0
	private static readonly Regex COMMAND_REGEX; // 0x0
	private static readonly Regex COMMENT_REGEX; // 0x8
	private static readonly Regex ONLY_SPACE_REGEX; // 0x10
	private List`1 m_errors; // 0x10
	private IAVGVariableConverter <variableConverter>k__BackingField; // 0x18

	private IAVGVariableConverter variableConverter { get; set; }

	// RVA: 0x3e92730 VA: 0x75964aa730
	private IAVGVariableConverter get_variableConverter() { }
	// RVA: 0x3e92738 VA: 0x75964aa738
	public Void set_variableConverter(IAVGVariableConverter value) { }
	// RVA: 0x3e92740 VA: 0x75964aa740
	public Boolean TryParse(String content, out List`1 commands) { }
	// RVA: 0x3e93580 VA: 0x75964ab580
	private Void _StoreOriginLinesToCmd(Command cmd, TextBlock block) { }
	// RVA: 0x3e93584 VA: 0x75964ab584
	public Boolean TryParse(String content, out Story story) { }
	// RVA: 0x3e935ac VA: 0x75964ab5ac
	public Boolean TryParse(String content, StoryParam param, out Story story) { }
	// RVA: 0x3e93b78 VA: 0x75964abb78
	public String GetErrorMessage() { }
	// RVA: 0x3e92cd8 VA: 0x75964aacd8
	public static Boolean CheckIfSkipLine(String str) { }
	// RVA: 0x3e93c48 VA: 0x75964abc48
	public static Boolean CheckIfComment(String str) { }
	// RVA: 0x3e9330c VA: 0x75964ab30c
	private Void _AppendError(String error) { }
	// RVA: 0x3e92dac VA: 0x75964aadac
	private Command _ParseCommand(TextBlock block) { }
	// RVA: 0x3e933e8 VA: 0x75964ab3e8
	private TextBlock _ReadNextBlock(StringReader reader) { }
	// RVA: 0x3e93cd4 VA: 0x75964abcd4
	private String _ReplaceEqualSignWithColon(String str) { }
	// RVA: 0x3e93e08 VA: 0x75964abe08
	public Void .ctor() { }
	// RVA: 0x3e93e90 VA: 0x75964abe90
	private static Void .cctor() { }
}
```