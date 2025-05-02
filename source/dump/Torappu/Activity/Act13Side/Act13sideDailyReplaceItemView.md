# Act13sideDailyReplaceItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `GameObject _selectedPartGo`

- `Text _textEmptyHint`

- `CanvasGroup _normalAlphaHandler`

- `Single _selectAlphaVal`

- `Text _textPrincipalName`

- `Text _textMissionName`

- `Text _textMissionDesc`

- `Text _textPrestigeDesc`

- `Text _textAgenda`

- `Image _imgOrgLogo`

- `Image _imgPrincipalBg`

- `SimpleLayoutContent _rewardList`

- `Single _itemCardScale`

- `Button _btnClick`

- `Adapter m_adapter`

- `Act13sideDailyMissionItemViewModel m_itemModel`

- `Int32 m_position`

- `Boolean m_isSelect`


## Methods

- `Void set_onItemClick(Action`2)`

- `Void Render(Int32, String, Act13sideDailyMissionItemViewModel)`

- `Void SetSelect(Boolean)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyReplaceItemView : MonoBehaviour, IHotfixable
{
	private GameObject _normalPartGo; // 0x18
	private GameObject _emptyPartGo; // 0x20
	private GameObject _selectedPartGo; // 0x28
	private Text _textEmptyHint; // 0x30
	private CanvasGroup _normalAlphaHandler; // 0x38
	private Single _selectAlphaVal; // 0x40
	private Text _textPrincipalName; // 0x48
	private Text _textMissionName; // 0x50
	private Text _textMissionDesc; // 0x58
	private Text _textPrestigeDesc; // 0x60
	private Text _textAgenda; // 0x68
	private Image _imgOrgLogo; // 0x70
	private Image _imgPrincipalBg; // 0x78
	private SimpleLayoutContent _rewardList; // 0x80
	private Single _itemCardScale; // 0x88
	private Button _btnClick; // 0x90
	private Action`2 <onItemClick>k__BackingField; // 0x98
	private Adapter m_adapter; // 0xa0
	private Act13sideDailyMissionItemViewModel m_itemModel; // 0xa8
	private Int32 m_position; // 0xb0
	private Boolean m_isSelect; // 0xb4
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SetSelect; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onItemClick { get; set; }

	// RVA: 0x34403c4 VA: 0x7595a583c4
	private Action`2 get_onItemClick() { }
	// RVA: 0x343f2e4 VA: 0x7595a572e4
	public Void set_onItemClick(Action`2 value) { }
	// RVA: 0x343e8d4 VA: 0x7595a568d4
	public Void Render(Int32 position, String actId, Act13sideDailyMissionItemViewModel itemModel) { }
	// RVA: 0x343edc4 VA: 0x7595a56dc4
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x34404c0 VA: 0x7595a584c0
	public Void OnItemClick() { }
	// RVA: 0x344056c VA: 0x7595a5856c
	public Void .ctor() { }
}
```