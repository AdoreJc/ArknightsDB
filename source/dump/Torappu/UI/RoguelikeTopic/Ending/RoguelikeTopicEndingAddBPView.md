# RoguelikeTopicEndingAddBPView

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending`


## Fields

- `Text _bpCount`

- `Image _bpImage`

- `AnimationWrapper _anim`

- `GameObject _getNode`

- `GameObject _fullTint`

- `GameObject _maxTag`

- `Selectable _iconColor`

- `GameObject _addtionNode`

- `Text _addtionLabel`


## Methods

- `Void Flush(String, GameSettleBpInfo, Single, Boolean, Boolean)`

- `Void PlayShowAnim(Single)`

- `Void _DoPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending
public class RoguelikeTopicEndingAddBPView : MonoBehaviour, IHotfixable
{
	private Text _bpCount; // 0x18
	private Image _bpImage; // 0x20
	private AnimationWrapper _anim; // 0x28
	private GameObject _getNode; // 0x30
	private GameObject _fullTint; // 0x38
	private GameObject _maxTag; // 0x40
	private Selectable _iconColor; // 0x48
	private GameObject _addtionNode; // 0x50
	private Text _addtionLabel; // 0x58
	private const String SHOW_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0_PlayShowAnim; // 0x8
	private static DelegateBridge __Hotfix0__DoPlay; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26d9b7c VA: 0x7594cf1b7c
	public Void Flush(String topic, GameSettleBpInfo bpAdd, Single addition, Boolean needFactor, Boolean alwaysShow) { }
	// RVA: 0x26d9ed8 VA: 0x7594cf1ed8
	public Void PlayShowAnim(Single delay) { }
	// RVA: 0x26dabd8 VA: 0x7594cf2bd8
	private Void _DoPlay() { }
	// RVA: 0x26dac64 VA: 0x7594cf2c64
	public Void .ctor() { }
}
```