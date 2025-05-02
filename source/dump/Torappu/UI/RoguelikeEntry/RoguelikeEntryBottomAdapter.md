# RoguelikeEntryBottomAdapter

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `GameObject _itemPrefab`

- `Int32 <focusIndex>k__BackingField`


## Properties

- `Int32 focusIndex`


## Methods

- `Int32 get_focusIndex()`

- `Void set_focusIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryBottomAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemPrefab; // 0x58
	private Int32 <focusIndex>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_focusIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_focusIndex; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Int32 focusIndex { get; set; }

	// RVA: 0x262f3e0 VA: 0x7594c473e0
	private Int32 get_focusIndex() { }
	// RVA: 0x262f448 VA: 0x7594c47448
	public Void set_focusIndex(Int32 value) { }
	// RVA: 0x262f4c4 VA: 0x7594c474c4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x262f584 VA: 0x7594c47584
	public override Void UpdateView(Int32 position, GameObject view, RoguelikeEntryBottomViewHolder holder, RoguelikeEntryItemViewModel data) { }
	// RVA: 0x262fa88 VA: 0x7594c47a88
	public Void .ctor() { }
}
```