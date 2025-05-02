# EndbookModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Boolean showDetail`

- `Int32 focusedEndIndex`

- `Boolean isInit`


## Methods

- `String GetDefaultEndID()`

- `Void LoadData(String, ActArchiveInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class EndbookModel : IHotfixable
{
	public ListDict`2 endbookItems; // 0x10
	public ListDict`2 endbookEnds; // 0x18
	public Boolean showDetail; // 0x20
	public Int32 focusedEndIndex; // 0x24
	public Boolean isInit; // 0x28
	private static DelegateBridge __Hotfix0_GetDefaultEndID; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3051994 VA: 0x7595669994
	public String GetDefaultEndID() { }
	// RVA: 0x3051b4c VA: 0x7595669b4c
	public Void LoadData(String archiveId, ActArchiveInfo archiveInfo) { }
	// RVA: 0x30526ec VA: 0x759566a6ec
	public Void .ctor() { }
}
```