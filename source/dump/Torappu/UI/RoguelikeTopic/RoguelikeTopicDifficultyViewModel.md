# RoguelikeTopicDifficultyViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicDifficulty diffcultyData`

- `PlayerRoguelikeDifficultyStatus status`

- `String topicId`

- `String m_cachedRuleDesc`


## Properties

- `Boolean isUnlock`

- `RoguelikeTopicMode modeDifficulty`

- `Int32 grade`

- `RoguelikeTopicDifficultyID id`

- `String ruleDescAfterReplacement`


## Methods

- `Boolean get_isUnlock()`

- `RoguelikeTopicMode get_modeDifficulty()`

- `Int32 get_grade()`

- `RoguelikeTopicDifficultyID get_id()`

- `String get_ruleDescAfterReplacement()`

- `Void InitRuleDesc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicDifficultyViewModel
{
	public RoguelikeTopicDifficulty diffcultyData; // 0x10
	public PlayerRoguelikeDifficultyStatus status; // 0x18
	public String topicId; // 0x20
	private String m_cachedRuleDesc; // 0x28

	public Boolean isUnlock { get; }
	public RoguelikeTopicMode modeDifficulty { get; }
	public Int32 grade { get; }
	public RoguelikeTopicDifficultyID id { get; }
	public String ruleDescAfterReplacement { get; }

	// RVA: 0x2678c60 VA: 0x7594c90c60
	public Boolean get_isUnlock() { }
	// RVA: 0x267836c VA: 0x7594c9036c
	public RoguelikeTopicMode get_modeDifficulty() { }
	// RVA: 0x2678c70 VA: 0x7594c90c70
	public Int32 get_grade() { }
	// RVA: 0x2678c8c VA: 0x7594c90c8c
	public RoguelikeTopicDifficultyID get_id() { }
	// RVA: 0x2678cbc VA: 0x7594c90cbc
	public String get_ruleDescAfterReplacement() { }
	// RVA: 0x2678cc4 VA: 0x7594c90cc4
	public Void InitRuleDesc() { }
	// RVA: 0x2678da4 VA: 0x7594c90da4
	public Void .ctor() { }
}
```