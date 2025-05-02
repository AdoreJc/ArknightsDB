# DeepSeaRPNodeChoiceItemView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `GameObject _leavePanelGo`

- `GameObject _commonPanelGo`

- `GameObject _btnChoiceGo`

- `Image _activeBg`

- `LayoutElement _layoutElement`

- `Int32 _heightLow`

- `Int32 _heightHigh`

- `Text _textLeave`

- `Text _textDesc`

- `Text _textUnlockDes`

- `UIAtlasImage _imgTriangle`

- `Color _colorGrey`

- `Color _colorNormal`

- `Color _colorLocked`

- `Color _colorBgNormal`

- `Color _colorBgLocked`

- `Action <onLeave>k__BackingField`

- `Int32 m_position`

- `EventData m_eventData`


## Properties

- `Action onLeave`


## Methods

- `Void set_onItemSelect(Action`2)`

- `Action get_onLeave()`

- `Void set_onLeave(Action)`

- `Void Render(DeepSeaRPChoiceModel, Int32)`

- `Void OnItemSelected()`

- `Void OnBtnLeave()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPNodeChoiceItemView : MonoBehaviour, IHotfixable
{
	private GameObject _leavePanelGo; // 0x18
	private GameObject _commonPanelGo; // 0x20
	private GameObject _btnChoiceGo; // 0x28
	private Image _activeBg; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private Int32 _heightLow; // 0x40
	private Int32 _heightHigh; // 0x44
	private Text _textLeave; // 0x48
	private Text _textDesc; // 0x50
	private Text _textUnlockDes; // 0x58
	private UIAtlasImage _imgTriangle; // 0x60
	private Color _colorGrey; // 0x68
	private Color _colorNormal; // 0x78
	private Color _colorLocked; // 0x88
	private Color _colorBgNormal; // 0x98
	private Color _colorBgLocked; // 0xa8
	private Action`2 <onItemSelect>k__BackingField; // 0xb8
	private Action <onLeave>k__BackingField; // 0xc0
	private Int32 m_position; // 0xc8
	private EventData m_eventData; // 0xd0
	private static DelegateBridge __Hotfix0_get_onItemSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onLeave; // 0x10
	private static DelegateBridge __Hotfix0_set_onLeave; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnItemSelected; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnLeave; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`2 onItemSelect { get; set; }
	private Action onLeave { get; set; }

	// RVA: 0x29d9774 VA: 0x7594ff1774
	private Action`2 get_onItemSelect() { }
	// RVA: 0x29d97dc VA: 0x7594ff17dc
	public Void set_onItemSelect(Action`2 value) { }
	// RVA: 0x29d9860 VA: 0x7594ff1860
	private Action get_onLeave() { }
	// RVA: 0x29d98c8 VA: 0x7594ff18c8
	public Void set_onLeave(Action value) { }
	// RVA: 0x29d994c VA: 0x7594ff194c
	public Void Render(DeepSeaRPChoiceModel choiceModel, Int32 position) { }
	// RVA: 0x29d9d94 VA: 0x7594ff1d94
	public Void OnItemSelected() { }
	// RVA: 0x29d9e40 VA: 0x7594ff1e40
	public Void OnBtnLeave() { }
	// RVA: 0x29d9edc VA: 0x7594ff1edc
	public Void .ctor() { }
}
```