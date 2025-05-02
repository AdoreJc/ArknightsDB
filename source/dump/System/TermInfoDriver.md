# TermInfoDriver

**Namespace:** `System`


## Fields

- `TermInfoReader reader`

- `Int32 cursorLeft`

- `Int32 cursorTop`

- `String title`

- `String titleFormat`

- `Boolean cursorVisible`

- `String csrVisible`

- `String csrInvisible`

- `String clear`

- `String bell`

- `String term`

- `StreamReader stdin`

- `CStreamWriter stdout`

- `Int32 windowWidth`

- `Int32 windowHeight`

- `Int32 bufferHeight`

- `Int32 bufferWidth`

- `Int32 readpos`

- `Int32 writepos`

- `String keypadXmit`

- `String keypadLocal`

- `Boolean inited`

- `Object initLock`

- `Boolean initKeys`

- `String origPair`

- `String origColors`

- `String cursorAddress`

- `ConsoleColor fgcolor`

- `String setfgcolor`

- `String setbgcolor`

- `Int32 maxColors`

- `Boolean noGetPosition`

- `Hashtable keymap`

- `ByteMatcher rootmap`

- `Int32 rl_startx`

- `Int32 rl_starty`

- `Int32 echon`


## Properties

- `Boolean Initialized`

- `Int32 WindowHeight`

- `Int32 WindowWidth`


## Methods

- `Void WriteConsole(String)`

- `Boolean get_Initialized()`

- `Void Init()`

- `Void IncrementX()`

- `Void WriteSpecialKey(ConsoleKeyInfo)`

- `Void WriteSpecialKey(Char)`

- `Boolean IsSpecialKey(ConsoleKeyInfo)`

- `Boolean IsSpecialKey(Char)`

- `Void GetCursorPosition()`

- `Void CheckWindowDimensions()`

- `Int32 get_WindowHeight()`

- `Int32 get_WindowWidth()`

- `Void AddToBuffer(Int32)`

- `Void AdjustBuffer()`

- `ConsoleKeyInfo CreateKeyInfoFromInt(Int32, Boolean)`

- `Object GetKeyFromBuffer(Boolean)`

- `ConsoleKeyInfo ReadKeyInternal(out)`

- `Boolean InputPending()`

- `Void QueueEcho(Char)`

- `Void Echo(ConsoleKeyInfo)`

- `Void EchoFlush()`

- `Int32 Read([In], Int32, Int32)`

- `ConsoleKeyInfo ReadKey(Boolean)`

- `String ReadLine()`

- `String ReadToEnd()`

- `String ReadUntilConditionInternal(Boolean)`

- `Void SetCursorPosition(Int32, Int32)`

- `Void CreateKeyMap()`

- `Void InitKeys()`

- `Void AddStringMapping(TermInfoStrings)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class TermInfoDriver : IConsoleDriver
{
	private static Int32* native_terminal_size; // 0x0
	private static Int32 terminal_size; // 0x8
	private static readonly String[] locations; // 0x10
	private TermInfoReader reader; // 0x10
	private Int32 cursorLeft; // 0x18
	private Int32 cursorTop; // 0x1c
	private String title; // 0x20
	private String titleFormat; // 0x28
	private Boolean cursorVisible; // 0x30
	private String csrVisible; // 0x38
	private String csrInvisible; // 0x40
	private String clear; // 0x48
	private String bell; // 0x50
	private String term; // 0x58
	private StreamReader stdin; // 0x60
	private CStreamWriter stdout; // 0x68
	private Int32 windowWidth; // 0x70
	private Int32 windowHeight; // 0x74
	private Int32 bufferHeight; // 0x78
	private Int32 bufferWidth; // 0x7c
	private Char[] buffer; // 0x80
	private Int32 readpos; // 0x88
	private Int32 writepos; // 0x8c
	private String keypadXmit; // 0x90
	private String keypadLocal; // 0x98
	private Boolean inited; // 0xa0
	private Object initLock; // 0xa8
	private Boolean initKeys; // 0xb0
	private String origPair; // 0xb8
	private String origColors; // 0xc0
	private String cursorAddress; // 0xc8
	private ConsoleColor fgcolor; // 0xd0
	private String setfgcolor; // 0xd8
	private String setbgcolor; // 0xe0
	private Int32 maxColors; // 0xe8
	private Boolean noGetPosition; // 0xec
	private Hashtable keymap; // 0xf0
	private ByteMatcher rootmap; // 0xf8
	private Int32 rl_startx; // 0x100
	private Int32 rl_starty; // 0x104
	private Byte[] control_characters; // 0x108
	private static readonly Int32[] _consoleColorToAnsiCode; // 0x18
	private Char[] echobuf; // 0x110
	private Int32 echon; // 0x118

	public Boolean Initialized { get; }
	public Int32 WindowHeight { get; }
	public Int32 WindowWidth { get; }

	// RVA: 0x6106a88 VA: 0x759871ea88
	private static String TryTermInfoDir(String dir, String term) { }
	// RVA: 0x6106bb4 VA: 0x759871ebb4
	private static String SearchTerminfo(String term) { }
	// RVA: 0x6106d20 VA: 0x759871ed20
	private Void WriteConsole(String str) { }
	// RVA: 0x60fdd48 VA: 0x7598715d48
	public Void .ctor(String term) { }
	// RVA: 0x61070c8 VA: 0x759871f0c8
	public Boolean get_Initialized() { }
	// RVA: 0x61070d0 VA: 0x759871f0d0
	public Void Init() { }
	// RVA: 0x6107d78 VA: 0x759871fd78
	private Void IncrementX() { }
	// RVA: 0x6107e3c VA: 0x759871fe3c
	public Void WriteSpecialKey(ConsoleKeyInfo key) { }
	// RVA: 0x610816c VA: 0x759872016c
	public Void WriteSpecialKey(Char c) { }
	// RVA: 0x6108318 VA: 0x7598720318
	public Boolean IsSpecialKey(ConsoleKeyInfo key) { }
	// RVA: 0x610839c VA: 0x759872039c
	public Boolean IsSpecialKey(Char c) { }
	// RVA: 0x6107ae8 VA: 0x759871fae8
	private Void GetCursorPosition() { }
	// RVA: 0x61084b4 VA: 0x75987204b4
	private Void CheckWindowDimensions() { }
	// RVA: 0x6107e10 VA: 0x759871fe10
	public Int32 get_WindowHeight() { }
	// RVA: 0x6107de4 VA: 0x759871fde4
	public Int32 get_WindowWidth() { }
	// RVA: 0x61083c4 VA: 0x75987203c4
	private Void AddToBuffer(Int32 b) { }
	// RVA: 0x61085d4 VA: 0x75987205d4
	private Void AdjustBuffer() { }
	// RVA: 0x6108194 VA: 0x7598720194
	private ConsoleKeyInfo CreateKeyInfoFromInt(Int32 n, Boolean alt) { }
	// RVA: 0x61085e8 VA: 0x75987205e8
	private Object GetKeyFromBuffer(Boolean cooked) { }
	// RVA: 0x6108dc8 VA: 0x7598720dc8
	private ConsoleKeyInfo ReadKeyInternal(out Boolean fresh) { }
	// RVA: 0x6109104 VA: 0x7598721104
	private Boolean InputPending() { }
	// RVA: 0x6109138 VA: 0x7598721138
	private Void QueueEcho(Char c) { }
	// RVA: 0x6109224 VA: 0x7598721224
	private Void Echo(ConsoleKeyInfo key) { }
	// RVA: 0x6109278 VA: 0x7598721278
	private Void EchoFlush() { }
	// RVA: 0x61092ac VA: 0x75987212ac
	public Int32 Read([In] [Out] Char[] dest, Int32 index, Int32 count) { }
	// RVA: 0x61095b0 VA: 0x75987215b0
	public ConsoleKeyInfo ReadKey(Boolean intercept) { }
	// RVA: 0x6109614 VA: 0x7598721614
	public String ReadLine() { }
	// RVA: 0x61097e4 VA: 0x75987217e4
	public String ReadToEnd() { }
	// RVA: 0x610961c VA: 0x759872161c
	private String ReadUntilConditionInternal(Boolean haltOnNewLine) { }
	// RVA: 0x6107f50 VA: 0x759871ff50
	public Void SetCursorPosition(Int32 left, Int32 top) { }
	// RVA: 0x6109990 VA: 0x7598721990
	private Void CreateKeyMap() { }
	// RVA: 0x6108f88 VA: 0x7598720f88
	private Void InitKeys() { }
	// RVA: 0x610b8cc VA: 0x75987238cc
	private Void AddStringMapping(TermInfoStrings s) { }
	// RVA: 0x610bacc VA: 0x7598723acc
	private static Void .cctor() { }
}
```