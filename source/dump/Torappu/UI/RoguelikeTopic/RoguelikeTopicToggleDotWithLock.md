# RoguelikeTopicToggleDotWithLock

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIColorToggle _colorToggle`

- `UIAtlasImage _lockDotImg`

- `UIAtlasImage _unCompleteDotImg`

- `UIAtlasImage _completeDotImg`

- `RoguelikeTopicToggleDotWithLockPlugin _plugin`


## Properties

- `Boolean isOn`

- `ROGUELIKE_TOPIC_TOGGLE_DOT_STATE toggleState`


## Methods

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `Void set_toggleState(ROGUELIKE_TOPIC_TOGGLE_DOT_STATE)`

- `Void Init(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicToggleDotWithLock : MonoBehaviour, IHotfixable
{
	private UIColorToggle _colorToggle; // 0x18
	private UIAtlasImage _lockDotImg; // 0x20
	private UIAtlasImage _unCompleteDotImg; // 0x28
	private UIAtlasImage _completeDotImg; // 0x30
	private RoguelikeTopicToggleDotWithLockPlugin _plugin; // 0x38
	private static DelegateBridge __Hotfix0_get_isOn; // 0x0
	private static DelegateBridge __Hotfix0_set_isOn; // 0x8
	private static DelegateBridge __Hotfix0_set_toggleState; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isOn { get; set; }
	public ROGUELIKE_TOPIC_TOGGLE_DOT_STATE toggleState { set; }

	// RVA: 0x264c27c VA: 0x7594c6427c
	public Boolean get_isOn() { }
	// RVA: 0x264c2f0 VA: 0x7594c642f0
	public Void set_isOn(Boolean value) { }
	// RVA: 0x264c37c VA: 0x7594c6437c
	public Void set_toggleState(ROGUELIKE_TOPIC_TOGGLE_DOT_STATE value) { }
	// RVA: 0x264c490 VA: 0x7594c64490
	public Void Init(Int32 dotIndex, Int32 dotsCountPerGroup) { }
	// RVA: 0x264c578 VA: 0x7594c64578
	public Void .ctor() { }
}
```