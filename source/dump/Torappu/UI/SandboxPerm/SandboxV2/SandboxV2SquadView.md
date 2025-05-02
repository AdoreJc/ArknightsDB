# SandboxV2SquadView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _charList`

- `SimpleLayoutContent _toolList`

- `GameObject _naviPanelGo`

- `GameObject _btnNaviToolGo`

- `CanvasGroup _alphaHandler`

- `Single _fadeDuraton`

- `ScrollRect _squadScrollRect`

- `Single _scrollDuration`

- `GameObject _charUsedAlertGo`

- `GameObject _toolLackAlertGo`

- `Boolean m_hasInited`

- `FadeSwitchTween m_switchTween`

- `CharListAdapter m_charListAdapter`

- `ToolListAdapter m_toolListAdapter`

- `Int32 m_cacheScrollSeq`

- `Tween m_scrollTween`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void set_onCharDineClick(Action`1)`

- `Void set_onSlotClick(Action`1)`

- `Void set_onToolClick(Action`1)`

- `Void set_onToolBtnBuildClick(Action`1)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void _ScrollToVal(Int32, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadView : DataBinder`1
{
	private SimpleLayoutContent _charList; // 0x20
	private SimpleLayoutContent _toolList; // 0x28
	private GameObject _naviPanelGo; // 0x30
	private GameObject _btnNaviToolGo; // 0x38
	private CanvasGroup _alphaHandler; // 0x40
	private Single _fadeDuraton; // 0x48
	private ScrollRect _squadScrollRect; // 0x50
	private Single _scrollDuration; // 0x58
	private GameObject _charUsedAlertGo; // 0x60
	private GameObject _toolLackAlertGo; // 0x68
	private Boolean m_hasInited; // 0x70
	private FadeSwitchTween m_switchTween; // 0x78
	private CharListAdapter m_charListAdapter; // 0x80
	private ToolListAdapter m_toolListAdapter; // 0x88
	private Int32 m_cacheScrollSeq; // 0x90
	private Tween m_scrollTween; // 0x98
	private Action`2 <onSkillSelect>k__BackingField; // 0xa0
	private Action`1 <onCharDineClick>k__BackingField; // 0xa8
	private Action`1 <onSlotClick>k__BackingField; // 0xb0
	private Action`1 <onToolClick>k__BackingField; // 0xb8
	private Action`1 <onToolBtnBuildClick>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onCharDineClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onCharDineClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onToolClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onToolClick; // 0x38
	private static DelegateBridge __Hotfix0_get_onToolBtnBuildClick; // 0x40
	private static DelegateBridge __Hotfix0_set_onToolBtnBuildClick; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x60
	private static DelegateBridge __Hotfix0__ScrollToVal; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Action`2 onSkillSelect { get; set; }
	private Action`1 onCharDineClick { get; set; }
	private Action`1 onSlotClick { get; set; }
	private Action`1 onToolClick { get; set; }
	private Action`1 onToolBtnBuildClick { get; set; }

	// RVA: 0x261cae0 VA: 0x7594c34ae0
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x2612ecc VA: 0x7594c2aecc
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x261cb48 VA: 0x7594c34b48
	private Action`1 get_onCharDineClick() { }
	// RVA: 0x2612f50 VA: 0x7594c2af50
	public Void set_onCharDineClick(Action`1 value) { }
	// RVA: 0x261cbb0 VA: 0x7594c34bb0
	private Action`1 get_onSlotClick() { }
	// RVA: 0x2612fd4 VA: 0x7594c2afd4
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x261cc18 VA: 0x7594c34c18
	private Action`1 get_onToolClick() { }
	// RVA: 0x2613058 VA: 0x7594c2b058
	public Void set_onToolClick(Action`1 value) { }
	// RVA: 0x261cc80 VA: 0x7594c34c80
	private Action`1 get_onToolBtnBuildClick() { }
	// RVA: 0x26130dc VA: 0x7594c2b0dc
	public Void set_onToolBtnBuildClick(Action`1 value) { }
	// RVA: 0x261cce8 VA: 0x7594c34ce8
	public override Void OnValueChanged(SandboxV2SquadGroupProp property) { }
	// RVA: 0x261cea8 VA: 0x7594c34ea8
	private Void _InitIfNot() { }
	// RVA: 0x261d19c VA: 0x7594c3519c
	private Void _RegisterTutorialGo() { }
	// RVA: 0x261d0a0 VA: 0x7594c350a0
	private Void _ScrollToVal(Int32 seqNum, Single scrollTweenVal) { }
	// RVA: 0x261d288 VA: 0x7594c35288
	public Void .ctor() { }
}
```