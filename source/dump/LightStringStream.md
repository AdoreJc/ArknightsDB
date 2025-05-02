# LightStringStream

**Namespace:** ` `


## Fields

- `String m_source`

- `Int32 m_length`

- `Int32 m_head`


## Properties

- `Boolean isEnd`

- `Int32 head`


## Methods

- `LightStringStream Reset(String)`

- `Boolean get_isEnd()`

- `Char Peek()`

- `Char Read()`

- `Int32 get_head()`

- `String Range(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LightStringStream
{
	private String m_source; // 0x10
	private Int32 m_length; // 0x18
	private Int32 m_head; // 0x1c

	public Boolean isEnd { get; }
	public Int32 head { get; }

	// RVA: 0x3114470 VA: 0x759572c470
	public Void .ctor() { }
	// RVA: 0x3114478 VA: 0x759572c478
	public Void .ctor(String source) { }
	// RVA: 0x310c274 VA: 0x7595724274
	public LightStringStream Reset(String source) { }
	// RVA: 0x310cd78 VA: 0x7595724d78
	public Boolean get_isEnd() { }
	// RVA: 0x31144a4 VA: 0x759572c4a4
	public Char Peek() { }
	// RVA: 0x310cb8c VA: 0x7595724b8c
	public Char Read() { }
	// RVA: 0x31144d8 VA: 0x759572c4d8
	public Int32 get_head() { }
	// RVA: 0x310cbcc VA: 0x7595724bcc
	public String Range(Int32 start, Int32 end) { }
}
```