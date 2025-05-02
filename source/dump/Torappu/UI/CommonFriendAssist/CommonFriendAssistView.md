# CommonFriendAssistView

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `Text _tips`

- `SimpleLayoutContent _profList`

- `SimpleLayoutContent _assistList`

- `GameObject _emptyList`

- `ProfTabAdapter _profTabAdapter`

- `AssistItemAdapter _assistItemAdapter`

- `ICtrl <ctrl>k__BackingField`


## Properties

- `ICtrl ctrl`


## Methods

- `ICtrl get_ctrl()`

- `Void set_ctrl(ICtrl)`

- `Void _InitIfNot()`

- `Void EventOnRefresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistView : DataBinder`1
{
	private Text _tips; // 0x20
	private SimpleLayoutContent _profList; // 0x28
	private SimpleLayoutContent _assistList; // 0x30
	private GameObject _emptyList; // 0x38
	private ProfTabAdapter _profTabAdapter; // 0x40
	private AssistItemAdapter _assistItemAdapter; // 0x48
	private ICtrl <ctrl>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_ctrl; // 0x0
	private static DelegateBridge __Hotfix0_set_ctrl; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_EventOnRefresh; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ICtrl ctrl { get; set; }

	// RVA: 0x2c4af5c VA: 0x7595262f5c
	public ICtrl get_ctrl() { }
	// RVA: 0x2c4938c VA: 0x759526138c
	public Void set_ctrl(ICtrl value) { }
	// RVA: 0x2c4afc4 VA: 0x7595262fc4
	public override Void OnValueChanged(CommonFriendAssistViewModelProperty property) { }
	// RVA: 0x2c4b134 VA: 0x7595263134
	private Void _InitIfNot() { }
	// RVA: 0x2c4b354 VA: 0x7595263354
	public Void EventOnRefresh() { }
	// RVA: 0x2c4b458 VA: 0x7595263458
	public Void .ctor() { }
}
```