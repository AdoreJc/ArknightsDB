# ArchiveTrapController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTrapListDataBinder _trapDataBinder`

- `Image _imgBkg`

- `GridLayoutGroup _layout`

- `Image _imgTitleText`


## Methods

- `Void set_onTrapItemClicked(Action`2)`

- `Int32 <Show>b__12_0()`

- `Void <Show>b__12_1(Int32)`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTrapController : ActArchiveController
{
	private const Int32 START_PADDING_TOP; // 0x0
	private ArchiveTrapListDataBinder _trapDataBinder; // 0x38
	private Image _imgBkg; // 0x40
	private GridLayoutGroup _layout; // 0x48
	private Image _imgTitleText; // 0x50
	private Action`2 <onTrapItemClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onTrapItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onTrapItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_Show; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`2 onTrapItemClicked { get; set; }

	// RVA: 0x308e508 VA: 0x75956a6508
	private Action`2 get_onTrapItemClicked() { }
	// RVA: 0x308e570 VA: 0x75956a6570
	public Void set_onTrapItemClicked(Action`2 value) { }
	// RVA: 0x308e5f4 VA: 0x75956a65f4
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x308e6b0 VA: 0x75956a66b0
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x308e860 VA: 0x75956a6860
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x308ea58 VA: 0x75956a6a58
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x308eb40 VA: 0x75956a6b40
	public Void .ctor() { }
	// RVA: 0x308ebb0 VA: 0x75956a6bb0
	private Int32 <Show>b__12_0() { }
	// RVA: 0x308ebd4 VA: 0x75956a6bd4
	private Void <Show>b__12_1(Int32 x) { }
	// RVA: 0x308ec60 VA: 0x75956a6c60
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x308ec68 VA: 0x75956a6c68
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x308ec70 VA: 0x75956a6c70
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```