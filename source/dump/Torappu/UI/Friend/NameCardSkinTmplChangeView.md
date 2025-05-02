# NameCardSkinTmplChangeView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UIAnimationLocation _switchAnim`

- `NameCardSkinListAdapter _skinTmplListAdapter`

- `Text _selectTips`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `AnimationSwitchTween m_switchTween`

- `Int32 m_skinTmplShowSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void OnCancelChangeSubSkin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinTmplChangeView : DataBinder`1
{
	private UIAnimationLocation _switchAnim; // 0x20
	private NameCardSkinListAdapter _skinTmplListAdapter; // 0x30
	private Text _selectTips; // 0x38
	private Boolean m_isInited; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private AnimationSwitchTween m_switchTween; // 0x58
	private Int32 m_skinTmplShowSeqNum; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnCancelChangeSubSkin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28de4e8 VA: 0x7594ef64e8
	public override Void OnValueChanged(NameCardSkinChangeProperty property) { }
	// RVA: 0x28de68c VA: 0x7594ef668c
	private Void _InitIfNot() { }
	// RVA: 0x28de774 VA: 0x7594ef6774
	public Void OnCancelChangeSubSkin() { }
	// RVA: 0x28de828 VA: 0x7594ef6828
	public Void .ctor() { }
}
```