# ItemRepoIssueVoucherView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `CanvasGroup _chooseGroup`

- `Text _consume0Text`

- `Text _possessCountText`

- `LoopScrollRect _chooseScrollRect`

- `ItemRepoIssueVoucherItemListAdapter _chooseAdapter`

- `GameObject _confirmValidPanel`

- `GameObject _confirmInvalidPanel`

- `CanvasGroup _outputGroup`

- `Text _consume1Text`

- `RectTransform _inputHolder`

- `Text _inputCountText`

- `ScrollRect _outputScrollRect`

- `SimpleLayoutContent _outputContent`

- `Single m_itemCardScale`

- `Boolean m_hasInited`

- `UIItemCard m_inputItemCard`

- `OutputAdapter m_outputAdapter`

- `UIStateFinder m_finder`

- `FadeSwitchTween m_choosePanelShowTween`

- `FadeSwitchTween m_outputPanelShowTween`

- `Boolean m_cachedIsChoosing`


## Methods

- `Void set_onSelectItem(Func`3)`

- `Void OnChooseConfirm()`

- `Void OnOutputCancel()`

- `Void OnOutputConfirm()`

- `Void _InitIfNot()`

- `Void _ShowItemDesc(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoIssueVoucherView : DataBinder`1
{
	private const Single TWEEN_DUR; // 0x0
	private CanvasGroup _chooseGroup; // 0x20
	private Text _consume0Text; // 0x28
	private Text _possessCountText; // 0x30
	private LoopScrollRect _chooseScrollRect; // 0x38
	private ItemRepoIssueVoucherItemListAdapter _chooseAdapter; // 0x40
	private GameObject _confirmValidPanel; // 0x48
	private GameObject _confirmInvalidPanel; // 0x50
	private CanvasGroup _outputGroup; // 0x58
	private Text _consume1Text; // 0x60
	private RectTransform _inputHolder; // 0x68
	private Text _inputCountText; // 0x70
	private ScrollRect _outputScrollRect; // 0x78
	private SimpleLayoutContent _outputContent; // 0x80
	private Single m_itemCardScale; // 0x88
	private Boolean m_hasInited; // 0x8c
	private UIItemCard m_inputItemCard; // 0x90
	private OutputAdapter m_outputAdapter; // 0x98
	private UIStateFinder m_finder; // 0xa0
	private FadeSwitchTween m_choosePanelShowTween; // 0xb0
	private FadeSwitchTween m_outputPanelShowTween; // 0xb8
	private List`1 m_cachedOutputItems; // 0xc0
	private Boolean m_cachedIsChoosing; // 0xc8
	private Func`3 <onSelectItem>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_onSelectItem; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectItem; // 0x8
	private static DelegateBridge __Hotfix0_OnChooseConfirm; // 0x10
	private static DelegateBridge __Hotfix0_OnOutputCancel; // 0x18
	private static DelegateBridge __Hotfix0_OnOutputConfirm; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Func`3 onSelectItem { get; set; }

	// RVA: 0x2d345a8 VA: 0x759534c5a8
	private Func`3 get_onSelectItem() { }
	// RVA: 0x2d34610 VA: 0x759534c610
	public Void set_onSelectItem(Func`3 value) { }
	// RVA: 0x2d34694 VA: 0x759534c694
	public Void OnChooseConfirm() { }
	// RVA: 0x2d34748 VA: 0x759534c748
	public Void OnOutputCancel() { }
	// RVA: 0x2d347fc VA: 0x759534c7fc
	public Void OnOutputConfirm() { }
	// RVA: 0x2d348b0 VA: 0x759534c8b0
	public override Void OnValueChanged(ItemRepoIssueVoucherViewProperty property) { }
	// RVA: 0x2d34cf4 VA: 0x759534ccf4
	private Void _InitIfNot() { }
	// RVA: 0x2d350b4 VA: 0x759534d0b4
	private Void _ShowItemDesc(Int32 _) { }
	// RVA: 0x2d351bc VA: 0x759534d1bc
	public Void .ctor() { }
}
```