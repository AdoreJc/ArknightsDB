# Group

**Namespace:** `System.Text.RegularExpressions`


## Properties

- `Boolean Success`

- `CaptureCollection Captures`


## Methods

- `Boolean get_Success()`

- `CaptureCollection get_Captures()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class Group : Capture
{
	internal static readonly Group s_emptyGroup; // 0x0
	internal readonly Int32[] _caps; // 0x20
	internal Int32 _capcount; // 0x28
	internal CaptureCollection _capcoll; // 0x30
	private readonly String <Name>k__BackingField; // 0x38

	public Boolean Success { get; }
	public CaptureCollection Captures { get; }

	// RVA: 0x63764bc VA: 0x759898e4bc
	internal Void .ctor(String text, Int32[] caps, Int32 capcount, String name) { }
	// RVA: 0x637657c VA: 0x759898e57c
	public Boolean get_Success() { }
	// RVA: 0x637658c VA: 0x759898e58c
	public CaptureCollection get_Captures() { }
	// RVA: 0x6376608 VA: 0x759898e608
	private static Void .cctor() { }
	// RVA: 0x637670c VA: 0x759898e70c
	internal Void .ctor() { }
}
```