# RegexMatchTimeoutException

**Namespace:** `System.Text.RegularExpressions`


## Properties

- `String Input`

- `String Pattern`

- `TimeSpan MatchTimeout`


## Methods

- `String get_Input()`

- `String get_Pattern()`

- `TimeSpan get_MatchTimeout()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class RegexMatchTimeoutException : TimeoutException, ISerializable
{
	private readonly String <Input>k__BackingField; // 0x90
	private readonly String <Pattern>k__BackingField; // 0x98
	private readonly TimeSpan <MatchTimeout>k__BackingField; // 0xa0

	public String Input { get; }
	public String Pattern { get; }
	public TimeSpan MatchTimeout { get; }

	// RVA: 0x638bab0 VA: 0x75989a3ab0
	public Void .ctor(String regexInput, String regexPattern, TimeSpan matchTimeout) { }
	// RVA: 0x638bbc8 VA: 0x75989a3bc8
	public Void .ctor() { }
	// RVA: 0x638bc7c VA: 0x75989a3c7c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x638bdf4 VA: 0x75989a3df4
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x638bef0 VA: 0x75989a3ef0
	public String get_Input() { }
	// RVA: 0x638bef8 VA: 0x75989a3ef8
	public String get_Pattern() { }
	// RVA: 0x638bf00 VA: 0x75989a3f00
	public TimeSpan get_MatchTimeout() { }
}
```