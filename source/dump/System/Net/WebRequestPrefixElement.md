# WebRequestPrefixElement

**Namespace:** `System.Net`


## Fields

- `String Prefix`


## Properties

- `IWebRequestCreate Creator`


## Methods

- `IWebRequestCreate get_Creator()`

- `Void set_Creator(IWebRequestCreate)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebRequestPrefixElement
{
	public String Prefix; // 0x10
	internal IWebRequestCreate creator; // 0x18
	internal Type creatorType; // 0x20

	public IWebRequestCreate Creator { get; set; }

	// RVA: 0x642a370 VA: 0x7598a42370
	public IWebRequestCreate get_Creator() { }
	// RVA: 0x642a584 VA: 0x7598a42584
	public Void set_Creator(IWebRequestCreate value) { }
	// RVA: 0x642a58c VA: 0x7598a4258c
	public Void .ctor(String P, IWebRequestCreate C) { }
}
```