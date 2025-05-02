# Act12D6OuterBuffItemView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Image _imgLevelBg`

- `Image _imgLevel`

- `Image _imgBuffIcon`

- `Text _txtBuffName`

- `Text _txtBuffLevel`

- `Text _txtBuffDesc`

- `Text _txtBuffEffect`

- `Button _btnLevelUp`

- `Button _btnMaxLevel`

- `String m_buffId`

- `UIStringEvent <onUpgradeClicked>k__BackingField`

- `UIStringEvent <onMaxLevelClicked>k__BackingField`


## Properties

- `UIStringEvent onUpgradeClicked`

- `UIStringEvent onMaxLevelClicked`


## Methods

- `UIStringEvent get_onUpgradeClicked()`

- `Void set_onUpgradeClicked(UIStringEvent)`

- `UIStringEvent get_onMaxLevelClicked()`

- `Void set_onMaxLevelClicked(UIStringEvent)`

- `Void Render(RoguelikeOuterBuff)`

- `Void EventOnClicked()`

- `Void EventOnMaxLevelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6OuterBuffItemView : MonoBehaviour, IHotfixable
{
	private Image _imgLevelBg; // 0x18
	private Image _imgLevel; // 0x20
	private Image _imgBuffIcon; // 0x28
	private Text _txtBuffName; // 0x30
	private Text _txtBuffLevel; // 0x38
	private Text _txtBuffDesc; // 0x40
	private Text _txtBuffEffect; // 0x48
	private Button _btnLevelUp; // 0x50
	private Button _btnMaxLevel; // 0x58
	private String m_buffId; // 0x60
	private UIStringEvent <onUpgradeClicked>k__BackingField; // 0x68
	private UIStringEvent <onMaxLevelClicked>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onUpgradeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onUpgradeClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onMaxLevelClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onMaxLevelClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnMaxLevelClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public UIStringEvent onUpgradeClicked { get; set; }
	public UIStringEvent onMaxLevelClicked { get; set; }

	// RVA: 0x3477c08 VA: 0x7595a8fc08
	public UIStringEvent get_onUpgradeClicked() { }
	// RVA: 0x3476ca8 VA: 0x7595a8eca8
	public Void set_onUpgradeClicked(UIStringEvent value) { }
	// RVA: 0x3477c70 VA: 0x7595a8fc70
	public UIStringEvent get_onMaxLevelClicked() { }
	// RVA: 0x3476d2c VA: 0x7595a8ed2c
	public Void set_onMaxLevelClicked(UIStringEvent value) { }
	// RVA: 0x3476db0 VA: 0x7595a8edb0
	public Void Render(RoguelikeOuterBuff buffData) { }
	// RVA: 0x3477cd8 VA: 0x7595a8fcd8
	public Void EventOnClicked() { }
	// RVA: 0x3477d80 VA: 0x7595a8fd80
	public Void EventOnMaxLevelClicked() { }
	// RVA: 0x3477e28 VA: 0x7595a8fe28
	public Void .ctor() { }
}
```