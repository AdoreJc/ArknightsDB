# NameCardV2AssistCharItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `TwoStateToggle _emptyToggle`

- `Image _eliteIcon`

- `GameObject _specMaxPart`

- `UIAtlasImage _portraitIcon`

- `Text _level`

- `Image _potentialLevel`

- `Image _skillIcon`

- `Image _equipIcon`

- `TwoStateToggle _equipToggle`

- `UIAnimationLocation _switchAnim`

- `UIColorGraphic _clickColorGraphic`

- `UISwitchTween m_switchTween`

- `Boolean m_hasTweenInited`


## Properties

- `Boolean isSwitchTweenShow`

- `UIColorGraphic clickColorGraphic`


## Methods

- `Boolean get_isSwitchTweenShow()`

- `UIColorGraphic get_clickColorGraphic()`

- `Void ApplyFriendData(SharedCharData)`

- `Void ApplyEmpty()`

- `Void ApplyData(PlayerFriendAssist)`

- `Void SetTweenShow(Boolean, Boolean)`

- `Void _ApplyData(PlayerCharacter, String, String)`

- `Void _EnsureSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2AssistCharItem : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _emptyToggle; // 0x18
	private Image _eliteIcon; // 0x20
	private GameObject _specMaxPart; // 0x28
	private UIAtlasImage _portraitIcon; // 0x30
	private Text _level; // 0x38
	private Image _potentialLevel; // 0x40
	private Image _skillIcon; // 0x48
	private Image _equipIcon; // 0x50
	private TwoStateToggle _equipToggle; // 0x58
	private UIAnimationLocation _switchAnim; // 0x60
	private UIColorGraphic _clickColorGraphic; // 0x70
	private UISwitchTween m_switchTween; // 0x78
	private Boolean m_hasTweenInited; // 0x80
	private static DelegateBridge __Hotfix0_get_isSwitchTweenShow; // 0x0
	private static DelegateBridge __Hotfix0_get_clickColorGraphic; // 0x8
	private static DelegateBridge __Hotfix0_ApplyFriendData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyEmpty; // 0x18
	private static DelegateBridge __Hotfix0_ApplyData; // 0x20
	private static DelegateBridge __Hotfix0_SetTweenShow; // 0x28
	private static DelegateBridge __Hotfix0__ApplyData; // 0x30
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isSwitchTweenShow { get; }
	public UIColorGraphic clickColorGraphic { get; }

	// RVA: 0x28de8b8 VA: 0x7594ef68b8
	public Boolean get_isSwitchTweenShow() { }
	// RVA: 0x28de92c VA: 0x7594ef692c
	public UIColorGraphic get_clickColorGraphic() { }
	// RVA: 0x28de994 VA: 0x7594ef6994
	public Void ApplyFriendData(SharedCharData assist) { }
	// RVA: 0x28ded58 VA: 0x7594ef6d58
	public Void ApplyEmpty() { }
	// RVA: 0x28dedd0 VA: 0x7594ef6dd0
	public Void ApplyData(PlayerFriendAssist assist) { }
	// RVA: 0x28df2fc VA: 0x7594ef72fc
	public Void SetTweenShow(Boolean fastMode, Boolean isShow) { }
	// RVA: 0x28def68 VA: 0x7594ef6f68
	private Void _ApplyData(PlayerCharacter charData, String skillId, String equipId) { }
	// RVA: 0x28df3ac VA: 0x7594ef73ac
	private Void _EnsureSwitchTween() { }
	// RVA: 0x28df49c VA: 0x7594ef749c
	public Void .ctor() { }
}
```