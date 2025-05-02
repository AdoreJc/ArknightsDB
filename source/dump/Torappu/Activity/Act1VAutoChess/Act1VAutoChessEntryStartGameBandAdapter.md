# Act1VAutoChessEntryStartGameBandAdapter

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEntryStartGameBandItemView _itemViewPrefab`

- `BandViewModel <selected>k__BackingField`


## Properties

- `BandViewModel selected`


## Methods

- `BandViewModel get_selected()`

- `Void set_selected(BandViewModel)`

- `Void _TutorialOnly_TryRegisterAVGFirstItem(Int32, Act1VAutoChessEntryStartGameBandItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryStartGameBandAdapter : LoopScrollAdapter`2
{
	private Act1VAutoChessEntryStartGameBandItemView _itemViewPrefab; // 0x58
	private BandViewModel <selected>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_selected; // 0x0
	private static DelegateBridge __Hotfix0_set_selected; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterAVGFirstItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private BandViewModel selected { get; set; }

	// RVA: 0x334abf0 VA: 0x7595962bf0
	private BandViewModel get_selected() { }
	// RVA: 0x334ac58 VA: 0x7595962c58
	public Void set_selected(BandViewModel value) { }
	// RVA: 0x334acdc VA: 0x7595962cdc
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x334add8 VA: 0x7595962dd8
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, BandViewModel data) { }
	// RVA: 0x334b1d0 VA: 0x75959631d0
	private Void _TutorialOnly_TryRegisterAVGFirstItem(Int32 position, Act1VAutoChessEntryStartGameBandItemView view) { }
	// RVA: 0x334b374 VA: 0x7595963374
	public Void .ctor() { }
}
```