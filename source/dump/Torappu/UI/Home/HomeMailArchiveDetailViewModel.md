# HomeMailArchiveDetailViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int32 selectIndex`

- `Int32 enterSeq`

- `Int32 nextSeq`

- `Int32 prevSeq`


## Methods

- `HomeMailArchiveItemViewModel GetSelectedViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveDetailViewModel : IHotfixable
{
	public List`1 itemList; // 0x10
	public Int32 selectIndex; // 0x18
	public Int32 enterSeq; // 0x1c
	public Int32 nextSeq; // 0x20
	public Int32 prevSeq; // 0x24
	private static DelegateBridge __Hotfix0_GetSelectedViewModel; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x281f9d8 VA: 0x7594e379d8
	public HomeMailArchiveItemViewModel GetSelectedViewModel() { }
	// RVA: 0x281fa60 VA: 0x7594e37a60
	public Void .ctor() { }
}
```