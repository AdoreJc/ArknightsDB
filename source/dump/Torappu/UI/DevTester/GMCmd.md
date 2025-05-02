# GMCmd

**Namespace:** `Torappu.UI.DevTester`


## Properties

- `Int32 argSize`


## Methods

- `Void Parse(String)`

- `Int32 get_argSize()`

- `Boolean IsCmd(String)`

- `Boolean HasArg(String)`

- `String GetArg(String)`

- `Int32 GetIntArg(String)`

- `String GetArgAt(Int32)`

- `Int32 GetIntArgAt(Int32)`

- `Boolean GetBoolArgAt(Int32)`

- `String MergeArgsToRawString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DevTester
public class GMCmd
{
	private const Char CHAR_SPLIT; // 0x0
	private String[] _cmds; // 0x10

	public Int32 argSize { get; }

	// RVA: 0x29bac40 VA: 0x7594fd2c40
	public Void Parse(String commandLine) { }
	// RVA: 0x29bac7c VA: 0x7594fd2c7c
	public Int32 get_argSize() { }
	// RVA: 0x29bac9c VA: 0x7594fd2c9c
	public Boolean IsCmd(String cmd) { }
	// RVA: 0x29bacd0 VA: 0x7594fd2cd0
	public Boolean HasArg(String name) { }
	// RVA: 0x29bad64 VA: 0x7594fd2d64
	public String GetArg(String name) { }
	// RVA: 0x29bae2c VA: 0x7594fd2e2c
	public Int32 GetIntArg(String name) { }
	// RVA: 0x29bae50 VA: 0x7594fd2e50
	public String GetArgAt(Int32 idx) { }
	// RVA: 0x29baea4 VA: 0x7594fd2ea4
	public Int32 GetIntArgAt(Int32 idx) { }
	// RVA: 0x29baec8 VA: 0x7594fd2ec8
	public Boolean GetBoolArgAt(Int32 idx) { }
	// RVA: 0x29baf50 VA: 0x7594fd2f50
	public String MergeArgsToRawString() { }
	// RVA: 0x29bb098 VA: 0x7594fd3098
	public Void .ctor() { }
}
```