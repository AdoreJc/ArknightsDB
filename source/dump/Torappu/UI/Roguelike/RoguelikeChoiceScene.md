# RoguelikeChoiceScene

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SceneContent m_playerScene`

- `RoguelikeChoiceFactory m_choiceFactory`

- `RoguelikeChoiceHintFactory m_hintFactory`

- `String m_topicId`

- `RoguelikeGameChoiceSceneData m_data`


## Properties

- `RoguelikeChoiceHintFactory hintFactory`

- `String topicId`

- `String sceneId`

- `String dialogTitle`

- `String dialogContent`

- `String titleIconName`

- `String bgName`

- `Boolean useHiddenMusic`

- `Int32 choiceCount`


## Methods

- `Void set_hintFactory(RoguelikeChoiceHintFactory)`

- `String get_topicId()`

- `String get_sceneId()`

- `Void _ClearData()`

- `Boolean IsEmpty()`

- `Void UpdateData(String, SceneContent)`

- `String get_dialogTitle()`

- `String get_dialogContent()`

- `String get_titleIconName()`

- `String get_bgName()`

- `Boolean get_useHiddenMusic()`

- `Int32 get_choiceCount()`

- `IRoguelikeGameChoice GetChoice(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceScene : IHotfixable
{
	private SceneContent m_playerScene; // 0x10
	private List`1 m_choices; // 0x18
	private RoguelikeChoiceFactory m_choiceFactory; // 0x20
	private RoguelikeChoiceHintFactory m_hintFactory; // 0x28
	private String m_topicId; // 0x30
	private RoguelikeGameChoiceSceneData m_data; // 0x38
	private static DelegateBridge __Hotfix0_set_hintFactory; // 0x0
	private static DelegateBridge __Hotfix0_get_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_sceneId; // 0x10
	private static DelegateBridge __Hotfix0__ClearData; // 0x18
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x20
	private static DelegateBridge __Hotfix0_UpdateData; // 0x28
	private static DelegateBridge __Hotfix0_get_dialogTitle; // 0x30
	private static DelegateBridge __Hotfix0_get_dialogContent; // 0x38
	private static DelegateBridge __Hotfix0_get_titleIconName; // 0x40
	private static DelegateBridge __Hotfix0_get_bgName; // 0x48
	private static DelegateBridge __Hotfix0_get_useHiddenMusic; // 0x50
	private static DelegateBridge __Hotfix0_get_choiceCount; // 0x58
	private static DelegateBridge __Hotfix0_GetChoice; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public RoguelikeChoiceHintFactory hintFactory { set; }
	public String topicId { get; }
	public String sceneId { get; }
	public String dialogTitle { get; }
	public String dialogContent { get; }
	public String titleIconName { get; }
	public String bgName { get; }
	public Boolean useHiddenMusic { get; }
	public Int32 choiceCount { get; }

	// RVA: 0x29f00d0 VA: 0x75950080d0
	public Void set_hintFactory(RoguelikeChoiceHintFactory value) { }
	// RVA: 0x29f13a8 VA: 0x75950093a8
	public String get_topicId() { }
	// RVA: 0x29f1234 VA: 0x7595009234
	public String get_sceneId() { }
	// RVA: 0x29f1410 VA: 0x7595009410
	private Void _ClearData() { }
	// RVA: 0x29f0154 VA: 0x7595008154
	public Boolean IsEmpty() { }
	// RVA: 0x29f0dd0 VA: 0x7595008dd0
	public Void UpdateData(String topicId, SceneContent sceneContent) { }
	// RVA: 0x29f14e0 VA: 0x75950094e0
	public String get_dialogTitle() { }
	// RVA: 0x29f1574 VA: 0x7595009574
	public String get_dialogContent() { }
	// RVA: 0x29f1608 VA: 0x7595009608
	public String get_titleIconName() { }
	// RVA: 0x29f01f0 VA: 0x75950081f0
	public String get_bgName() { }
	// RVA: 0x29f044c VA: 0x759500844c
	public Boolean get_useHiddenMusic() { }
	// RVA: 0x29f167c VA: 0x759500967c
	public Int32 get_choiceCount() { }
	// RVA: 0x29f16fc VA: 0x75950096fc
	public IRoguelikeGameChoice GetChoice(Int32 idx) { }
	// RVA: 0x29f12ac VA: 0x75950092ac
	public Void .ctor() { }
}
```