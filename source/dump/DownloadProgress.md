# DownloadProgress

**Namespace:** ` `


## Fields

- `String m_info`

- `Int64 m_curBytes`

- `Int64 m_totalBytes`

- `String m_formatCache`


## Methods

- `Void SetProgress(Int64, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DownloadProgress : Progress
{
	private String m_info; // 0x18
	private Int64 m_curBytes; // 0x20
	private Int64 m_totalBytes; // 0x28
	private String m_formatCache; // 0x30


	// RVA: 0x27bbcac VA: 0x7594dd3cac
	public Void .ctor(String downloadInfoFormat) { }
	// RVA: 0x27bbce4 VA: 0x7594dd3ce4
	public Void SetProgress(Int64 curBytes, Int64 totalBytes) { }
	// RVA: 0x27bbd10 VA: 0x7594dd3d10
	public override Double GetCurrent() { }
	// RVA: 0x27bbd1c VA: 0x7594dd3d1c
	public override Double GetTotal() { }
	// RVA: 0x27bbd28 VA: 0x7594dd3d28
	public override String GetInfo() { }
}
```