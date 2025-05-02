# HomeCharRotationPresetListView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textCurrNum`

- `Text _textTotalNum`

- `GameObject _pnlNewPreset`

- `GameObject _pnlPresetLimit`

- `SimpleLayoutContent _presetList`

- `ScrollRect _scrollRect`

- `Action <onBtnCreateClick>k__BackingField`

- `Boolean m_inited`

- `Adapter m_adapter`

- `HomeCharRotationPresetListViewModel m_cachedViewModel`

- `Int32 m_cachedCreatePresetSeqNum`

- `Tween m_scrollRectTween`


## Properties

- `Action onBtnCreateClick`


## Methods

- `Void set_onBtnNameClick(Action`1)`

- `Void set_onBtnDeleteClick(Action`1)`

- `Void set_onBtnEditClick(Action`1)`

- `Void set_onBtnApplyClick(Action`1)`

- `Action get_onBtnCreateClick()`

- `Void set_onBtnCreateClick(Action)`

- `Void _InitIfNot()`

- `Void OnBtnCreatePresetClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetListView : DataBinder`1
{
	private const String TOTAL_PRESET_NUM_FORMAT; // 0x0
	private Text _textCurrNum; // 0x20
	private Text _textTotalNum; // 0x28
	private GameObject _pnlNewPreset; // 0x30
	private GameObject _pnlPresetLimit; // 0x38
	private SimpleLayoutContent _presetList; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private Action`1 <onBtnNameClick>k__BackingField; // 0x50
	private Action`1 <onBtnDeleteClick>k__BackingField; // 0x58
	private Action`1 <onBtnEditClick>k__BackingField; // 0x60
	private Action`1 <onBtnApplyClick>k__BackingField; // 0x68
	private Action <onBtnCreateClick>k__BackingField; // 0x70
	private Boolean m_inited; // 0x78
	private Adapter m_adapter; // 0x80
	private HomeCharRotationPresetListViewModel m_cachedViewModel; // 0x88
	private Int32 m_cachedCreatePresetSeqNum; // 0x90
	private Tween m_scrollRectTween; // 0x98
	private static DelegateBridge __Hotfix0_get_onBtnNameClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnNameClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onBtnDeleteClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onBtnDeleteClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onBtnEditClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onBtnEditClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onBtnApplyClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onBtnApplyClick; // 0x38
	private static DelegateBridge __Hotfix0_get_onBtnCreateClick; // 0x40
	private static DelegateBridge __Hotfix0_set_onBtnCreateClick; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnCreatePresetClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Action`1 onBtnNameClick { get; set; }
	public Action`1 onBtnDeleteClick { get; set; }
	public Action`1 onBtnEditClick { get; set; }
	public Action`1 onBtnApplyClick { get; set; }
	public Action onBtnCreateClick { get; set; }

	// RVA: 0x27dfd5c VA: 0x7594df7d5c
	public Action`1 get_onBtnNameClick() { }
	// RVA: 0x27dcec8 VA: 0x7594df4ec8
	public Void set_onBtnNameClick(Action`1 value) { }
	// RVA: 0x27dfdc4 VA: 0x7594df7dc4
	public Action`1 get_onBtnDeleteClick() { }
	// RVA: 0x27dcf4c VA: 0x7594df4f4c
	public Void set_onBtnDeleteClick(Action`1 value) { }
	// RVA: 0x27dfe2c VA: 0x7594df7e2c
	public Action`1 get_onBtnEditClick() { }
	// RVA: 0x27dcfd0 VA: 0x7594df4fd0
	public Void set_onBtnEditClick(Action`1 value) { }
	// RVA: 0x27dfe94 VA: 0x7594df7e94
	public Action`1 get_onBtnApplyClick() { }
	// RVA: 0x27dd054 VA: 0x7594df5054
	public Void set_onBtnApplyClick(Action`1 value) { }
	// RVA: 0x27dfefc VA: 0x7594df7efc
	public Action get_onBtnCreateClick() { }
	// RVA: 0x27dd0d8 VA: 0x7594df50d8
	public Void set_onBtnCreateClick(Action value) { }
	// RVA: 0x27dff64 VA: 0x7594df7f64
	private Void _InitIfNot() { }
	// RVA: 0x27e00c8 VA: 0x7594df80c8
	public override Void OnValueChanged(HomeCharRotationPresetListViewProperty property) { }
	// RVA: 0x27e036c VA: 0x7594df836c
	public Void OnBtnCreatePresetClick() { }
	// RVA: 0x27e0408 VA: 0x7594df8408
	public Void .ctor() { }
}
```