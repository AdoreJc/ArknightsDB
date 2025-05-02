# HomeMailArchiveViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int32 selectItemIndex`


## Methods

- `Void Clear()`

- `Void LoadData(List`1, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveViewModel : IHotfixable
{
	public List`1 itemModelList; // 0x10
	public List`1 itemModelWithoutTitle; // 0x18
	public List`1 titleItemModelList; // 0x20
	public Int32 selectItemIndex; // 0x28
	private Dictionary`2 m_infoDict; // 0x30
	private static DelegateBridge __Hotfix0_Clear; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x281fde8 VA: 0x7594e37de8
	public Void Clear() { }
	// RVA: 0x281ff0c VA: 0x7594e37f0c
	public Void LoadData(List`1 unlockList, List`1 extraData) { }
	// RVA: 0x2820990 VA: 0x7594e38990
	public Void .ctor() { }
}
```