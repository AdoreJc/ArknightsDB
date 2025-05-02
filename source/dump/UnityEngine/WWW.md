# WWW

**Namespace:** `UnityEngine`


## Fields

- `UnityWebRequest _uwr`


## Properties

- `String error`

- `Boolean isDone`

- `String text`

- `String url`


## Methods

- `String get_error()`

- `Boolean get_isDone()`

- `String get_text()`

- `String get_url()`

- `Void Dispose()`

- `Boolean WaitUntilDoneIfPossible()`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestWWWModule.dll
// Namespace : UnityEngine
public class WWW : CustomYieldInstruction, IDisposable
{
	private UnityWebRequest _uwr; // 0x10

	public Byte[] bytes { get; }
	public String error { get; }
	public Boolean isDone { get; }
	public String text { get; }
	public String url { get; }
	public override Boolean keepWaiting { get; }

	// RVA: 0x6a888c4 VA: 0x75990a08c4
	public static String EscapeURL(String s, Encoding e) { }
	// RVA: 0x6a888cc VA: 0x75990a08cc
	public static String UnEscapeURL(String s) { }
	// RVA: 0x6a888f0 VA: 0x75990a08f0
	public static String UnEscapeURL(String s, Encoding e) { }
	// RVA: 0x6a888f8 VA: 0x75990a08f8
	public Void .ctor(String url) { }
	// RVA: 0x6a88948 VA: 0x75990a0948
	public Byte[] get_bytes() { }
	// RVA: 0x6a88ac0 VA: 0x75990a0ac0
	public String get_error() { }
	// RVA: 0x6a88be8 VA: 0x75990a0be8
	public Boolean get_isDone() { }
	// RVA: 0x6a88c04 VA: 0x75990a0c04
	public String get_text() { }
	// RVA: 0x6a88c94 VA: 0x75990a0c94
	public String get_url() { }
	// RVA: 0x6a88cb0 VA: 0x75990a0cb0
	public override Boolean get_keepWaiting() { }
	// RVA: 0x6a88cdc VA: 0x75990a0cdc
	public Void Dispose() { }
	// RVA: 0x6a889dc VA: 0x75990a09dc
	private Boolean WaitUntilDoneIfPossible() { }
}
```