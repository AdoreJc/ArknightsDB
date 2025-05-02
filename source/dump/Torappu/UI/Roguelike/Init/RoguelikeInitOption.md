# RoguelikeInitOption

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `Text _titleText`

- `Text _descriptionText`

- `Image _iconImage`

- `Image _underTex`

- `GameObject _endingPanel`

- `UIAtlasImage _endingIconPrefab`

- `UIAtlasImage _endingFrameUp`

- `UIAtlasImage _endingFrameDown`

- `GameObject _newPanel`

- `GameObject _lockPanel`

- `Text _lockMessageLabel`

- `Button _activeButton`

- `Button _selectButton`

- `Int32 m_optionIndex`

- `Model m_data`

- `Boolean m_active`


## Properties

- `Int32 optionIndex`


## Methods

- `Void Setup(Int32, Model)`

- `Void SetupDescriptionAlignment()`

- `Vector3 GetSubViewPosition()`

- `Int32 get_optionIndex()`

- `Void SetOptionActive(Boolean)`

- `Void EventActiveButtonPressed()`

- `Void EventSelectButtonPressed()`

- `UIAtlasImage _CreateIcon()`

- `UIAtlasImage <Setup>b__25_0()`

- `UIAtlasImage <Setup>b__25_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitOption : RoguelikeInitCardBase
{
	private Text _titleText; // 0x28
	private Text _descriptionText; // 0x30
	private Image _iconImage; // 0x38
	private GameObject[] _levels; // 0x40
	private Image _underTex; // 0x48
	private GameObject _endingPanel; // 0x50
	private UIAtlasImage _endingIconPrefab; // 0x58
	private UIAtlasImage _endingFrameUp; // 0x60
	private UIAtlasImage _endingFrameDown; // 0x68
	private GameObject _newPanel; // 0x70
	private GameObject _lockPanel; // 0x78
	private Text _lockMessageLabel; // 0x80
	private Button _activeButton; // 0x88
	private Button _selectButton; // 0x90
	private const String ANIM_ACTIVE; // 0x0
	private const String ANIM_DISACTIVE; // 0x0
	private Int32 m_optionIndex; // 0x98
	private Model m_data; // 0xa0
	private Boolean m_active; // 0xe0
	private ItemPool`1 m_endingIcons; // 0xe8
	private ItemPool`1 m_endingFrameUps; // 0xf0
	private ItemPool`1 m_endingFrameDowns; // 0xf8
	public Action`1 selectCallback; // 0x100
	public Action`1 activeCallback; // 0x108
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_SetupDescriptionAlignment; // 0x8
	private static DelegateBridge __Hotfix0_GetSubViewPosition; // 0x10
	private static DelegateBridge __Hotfix0_get_optionIndex; // 0x18
	private static DelegateBridge __Hotfix0_SetOptionActive; // 0x20
	private static DelegateBridge __Hotfix0_EventActiveButtonPressed; // 0x28
	private static DelegateBridge __Hotfix0_EventSelectButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0__CreateIcon; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 optionIndex { get; }

	// RVA: 0x2b862bc VA: 0x759519e2bc
	public Void Setup(Int32 optionIdx, Model data) { }
	// RVA: 0x2b86be4 VA: 0x759519ebe4
	public Void SetupDescriptionAlignment() { }
	// RVA: 0x2b86cc4 VA: 0x759519ecc4
	public Vector3 GetSubViewPosition() { }
	// RVA: 0x2b86d40 VA: 0x759519ed40
	public Int32 get_optionIndex() { }
	// RVA: 0x2b86ac8 VA: 0x759519eac8
	public Void SetOptionActive(Boolean active) { }
	// RVA: 0x2b86da8 VA: 0x759519eda8
	public Void EventActiveButtonPressed() { }
	// RVA: 0x2b86e38 VA: 0x759519ee38
	public Void EventSelectButtonPressed() { }
	// RVA: 0x2b86ec8 VA: 0x759519eec8
	private UIAtlasImage _CreateIcon() { }
	// RVA: 0x2b86f90 VA: 0x759519ef90
	public Void .ctor() { }
	// RVA: 0x2b87004 VA: 0x759519f004
	private UIAtlasImage <Setup>b__25_0() { }
	// RVA: 0x2b87094 VA: 0x759519f094
	private UIAtlasImage <Setup>b__25_1() { }
}
```