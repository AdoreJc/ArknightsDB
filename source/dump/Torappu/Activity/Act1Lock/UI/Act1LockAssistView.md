# Act1LockAssistView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `RectTransform _illustrationLayout`

- `Single _illustScaleFactor`

- `Text _levelText`

- `Image _eliteImg`

- `Image _rarityImg`

- `Text _nickNameText`

- `Image _professionImg`

- `Text _realNameText`

- `SimpleLayoutContent _skillLayoutContent`

- `TwoStateToggle _confirmToggle`

- `Action onConfirmClick`

- `Boolean m_isInited`

- `UICharacterIllust m_illust`

- `PlayerCharacter m_playerCharacter`

- `CharUISkinStruct m_skinStruct`

- `SkillViewAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void _LoadAndSetIllusts(CharUISkinStruct)`

- `Void _ClearIllusts()`

- `Void _OnSkillViewClick(Int32)`

- `Void OnConfirmBtnClick()`

- `Void OnDetailBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAssistView : DataBinder`1
{
	private RectTransform _illustrationLayout; // 0x20
	private Single _illustScaleFactor; // 0x28
	private Text _levelText; // 0x30
	private Image _eliteImg; // 0x38
	private Image _rarityImg; // 0x40
	private Text _nickNameText; // 0x48
	private Image _professionImg; // 0x50
	private Text _realNameText; // 0x58
	private SimpleLayoutContent _skillLayoutContent; // 0x60
	private TwoStateToggle _confirmToggle; // 0x68
	public Action`1 onSkillClick; // 0x70
	public Action onConfirmClick; // 0x78
	private Boolean m_isInited; // 0x80
	private UICharacterIllust m_illust; // 0x88
	private PlayerCharacter m_playerCharacter; // 0x90
	private CharUISkinStruct m_skinStruct; // 0x98
	private SkillViewAdapter m_adapter; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__LoadAndSetIllusts; // 0x10
	private static DelegateBridge __Hotfix0__ClearIllusts; // 0x18
	private static DelegateBridge __Hotfix0__OnSkillViewClick; // 0x20
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_OnDetailBtnClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x33a811c VA: 0x75959c011c
	private Void _InitIfNot() { }
	// RVA: 0x33a8210 VA: 0x75959c0210
	public override Void OnValueChanged(Act1LockAssistViewProperty property) { }
	// RVA: 0x33a84f8 VA: 0x75959c04f8
	private Void _LoadAndSetIllusts(CharUISkinStruct skinStruct) { }
	// RVA: 0x33a8764 VA: 0x75959c0764
	private Void _ClearIllusts() { }
	// RVA: 0x33a882c VA: 0x75959c082c
	private Void _OnSkillViewClick(Int32 position) { }
	// RVA: 0x33a88cc VA: 0x75959c08cc
	public Void OnConfirmBtnClick() { }
	// RVA: 0x33a8950 VA: 0x75959c0950
	public Void OnDetailBtnClick() { }
	// RVA: 0x33a8a64 VA: 0x75959c0a64
	public Void .ctor() { }
}
```