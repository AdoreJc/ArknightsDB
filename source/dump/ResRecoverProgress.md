# ResRecoverProgress

**Namespace:** ` `


## Fields

- `Int32 m_cur`

- `Int32 m_total`

- `String m_info`


## Methods

- `Void Set(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ResRecoverProgress : Progress
{
	private Int32 m_cur; // 0x14
	private Int32 m_total; // 0x18
	private String m_info; // 0x20


	// RVA: 0x27c2734 VA: 0x7594dda734
	public override Double GetCurrent() { }
	// RVA: 0x27c2740 VA: 0x7594dda740
	public override String GetInfo() { }
	// RVA: 0x27c284c VA: 0x7594dda84c
	public override Double GetTotal() { }
	// RVA: 0x27c26bc VA: 0x7594dda6bc
	public Void Set(Int32 cur, Int32 total) { }
	// RVA: 0x27c2010 VA: 0x7594dda010
	public Void .ctor() { }
}
```