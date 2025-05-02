# RoguelikeTopicDifficultyItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicDifficulty m_diffData`

- `Sprite m_relicIcon`


## Properties

- `Int32 sortId`

- `Sprite relicIcon`

- `RoguelikeTopicDifficulty difficultyData`


## Methods

- `Int32 get_sortId()`

- `Sprite get_relicIcon()`

- `RoguelikeTopicDifficulty get_difficultyData()`

- `Void Load(RoguelikeTopicDifficulty, RoguelikeTopicNormalModelStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicDifficultyItemModel : IHotfixable
{
	private RoguelikeTopicDifficulty m_diffData; // 0x10
	private Sprite m_relicIcon; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x0
	private static DelegateBridge __Hotfix0_get_relicIcon; // 0x8
	private static DelegateBridge __Hotfix0_get_difficultyData; // 0x10
	private static DelegateBridge __Hotfix0_Load; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 sortId { get; }
	public Sprite relicIcon { get; }
	public RoguelikeTopicDifficulty difficultyData { get; }

	// RVA: 0x264c658 VA: 0x7594c64658
	public Int32 get_sortId() { }
	// RVA: 0x264c6d0 VA: 0x7594c646d0
	public Sprite get_relicIcon() { }
	// RVA: 0x264c738 VA: 0x7594c64738
	public RoguelikeTopicDifficulty get_difficultyData() { }
	// RVA: 0x264c7a0 VA: 0x7594c647a0
	public Void Load(RoguelikeTopicDifficulty difficultyData, RoguelikeTopicNormalModelStyle normalModeStyle) { }
	// RVA: 0x264c8b0 VA: 0x7594c648b0
	public Void .ctor() { }
}
```