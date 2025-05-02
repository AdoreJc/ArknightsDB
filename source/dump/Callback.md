# Callback

**Namespace:** ` `


## Fields

- `Boolean m_complete`

- `String <data>k__BackingField`


## Properties

- `String data`


## Methods

- `Void Clear()`

- `String get_data()`

- `Void set_data(String)`

- `Void onLatestGame(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Callback : CustomYieldInstruction, IHGGameUpdateSDKCallback
{
	private Boolean m_complete; // 0x10
	public static Callback instance; // 0x0
	private String <data>k__BackingField; // 0x18

	public override Boolean keepWaiting { get; }
	public String data { get; set; }

	// RVA: 0x27c38f8 VA: 0x7594ddb8f8
	private Void .ctor() { }
	// RVA: 0x27c3900 VA: 0x7594ddb900
	public Void Clear() { }
	// RVA: 0x27c3910 VA: 0x7594ddb910
	public override Boolean get_keepWaiting() { }
	// RVA: 0x27c3920 VA: 0x7594ddb920
	public String get_data() { }
	// RVA: 0x27c3928 VA: 0x7594ddb928
	private Void set_data(String value) { }
	// RVA: 0x27c3930 VA: 0x7594ddb930
	public Void onLatestGame(String pData) { }
	// RVA: 0x27c3940 VA: 0x7594ddb940
	private static Void .cctor() { }
}
```