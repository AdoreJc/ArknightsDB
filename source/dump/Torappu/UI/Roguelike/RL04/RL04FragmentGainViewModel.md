# RL04FragmentGainViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 showIndex`


## Properties

- `Boolean isLastItem`


## Methods

- `Boolean get_isLastItem()`

- `Void LoadData(Options)`

- `Void ShowNextItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentGainViewModel : IHotfixable
{
	public List`1 fragmentList; // 0x10
	public Int32 showIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_isLastItem; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ShowNextItem; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isLastItem { get; }

	// RVA: 0x2b237c0 VA: 0x759513b7c0
	public Boolean get_isLastItem() { }
	// RVA: 0x2b22e1c VA: 0x759513ae1c
	public Void LoadData(Options input) { }
	// RVA: 0x2b230f8 VA: 0x759513b0f8
	public Void ShowNextItem() { }
	// RVA: 0x2b23a1c VA: 0x759513ba1c
	public Void .ctor() { }
}
```