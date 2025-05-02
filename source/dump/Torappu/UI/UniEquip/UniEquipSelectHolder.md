# UniEquipSelectHolder

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `SimpleLayoutContent _content`

- `UniEquipAttributeView _attibuteView`

- `UniEquipDescView _traitDescView`

- `UniEquipInfoDetailTalentContentGroup _talentGroup`

- `ScrollRect _scrollRect`

- `UIStringEvent _onUnlockAction`

- `UIStringEvent _onDetailAction`

- `UIStringEvent _onSelectAction`

- `UIStringEvent _onChangeAction`

- `UIStringEvent _onLevelUpAction`

- `GameObject _panelLocked`

- `Action onRenderFinish`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `Tween m_tween`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `Void set_page(UIPage)`

- `UIPage get_page()`

- `Void _InitIfNot()`

- `Void _OnRenderFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSelectHolder : DataBinder`1
{
	private const Single TWEEN_DURATION; // 0x0
	private SimpleLayoutContent _content; // 0x20
	private UniEquipAttributeView _attibuteView; // 0x28
	private UniEquipDescView _traitDescView; // 0x30
	private UniEquipInfoDetailTalentContentGroup _talentGroup; // 0x38
	private ScrollRect _scrollRect; // 0x40
	private UIStringEvent _onUnlockAction; // 0x48
	private UIStringEvent _onDetailAction; // 0x50
	private UIStringEvent _onSelectAction; // 0x58
	private UIStringEvent _onChangeAction; // 0x60
	private UIStringEvent _onLevelUpAction; // 0x68
	private GameObject _panelLocked; // 0x70
	public Action onRenderFinish; // 0x78
	private Adapter m_adapter; // 0x80
	private Boolean m_isInited; // 0x88
	private Tween m_tween; // 0x90
	private UIPage <page>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_set_page; // 0x0
	private static DelegateBridge __Hotfix0_get_page; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnRenderFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private UIPage page { get; set; }

	// RVA: 0x2303814 VA: 0x759491b814
	public Void set_page(UIPage value) { }
	// RVA: 0x2303898 VA: 0x759491b898
	private UIPage get_page() { }
	// RVA: 0x2303900 VA: 0x759491b900
	private Void _InitIfNot() { }
	// RVA: 0x2303aa4 VA: 0x759491baa4
	public override Void OnValueChanged(UniEquipSelectProperty property) { }
	// RVA: 0x2303f90 VA: 0x759491bf90
	private Void _OnRenderFinish() { }
	// RVA: 0x2304014 VA: 0x759491c014
	public Void .ctor() { }
}
```