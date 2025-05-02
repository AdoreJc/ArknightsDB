# RoguelikeTaskCompleteView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textProgress`

- `Single _alphaComplted`

- `Slider _sliderProgress`

- `Text _textTaskName`

- `Text _textTaskDesc`

- `UIAtlasImage _imgRarity`

- `UIAtlasObject _atlas`

- `Action <onGetReward>k__BackingField`


## Properties

- `Action onGetReward`


## Methods

- `Action get_onGetReward()`

- `Void set_onGetReward(Action)`

- `Void Render(RoguelikeTaskCompleteModel)`

- `Void OnBtnGetReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTaskCompleteView : MonoBehaviour, IHotfixable
{
	private Text _textProgress; // 0x18
	private Single _alphaComplted; // 0x20
	private Slider _sliderProgress; // 0x28
	private Text _textTaskName; // 0x30
	private Text _textTaskDesc; // 0x38
	private UIAtlasImage _imgRarity; // 0x40
	private UIAtlasObject _atlas; // 0x48
	private Action <onGetReward>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onGetReward; // 0x0
	private static DelegateBridge __Hotfix0_set_onGetReward; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnGetReward; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onGetReward { get; set; }

	// RVA: 0x2af9ec8 VA: 0x7595111ec8
	private Action get_onGetReward() { }
	// RVA: 0x2af94d0 VA: 0x75951114d0
	public Void set_onGetReward(Action value) { }
	// RVA: 0x2af9164 VA: 0x7595111164
	public Void Render(RoguelikeTaskCompleteModel taskModel) { }
	// RVA: 0x2af9f30 VA: 0x7595111f30
	public Void OnBtnGetReward() { }
	// RVA: 0x2af9fcc VA: 0x7595111fcc
	public Void .ctor() { }
}
```