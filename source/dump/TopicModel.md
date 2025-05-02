# TopicModel

**Namespace:** ` `


## Fields

- `String m_displayId`

- `String m_topicId`

- `Boolean m_isOnBattle`

- `Boolean m_isPinned`

- `RoguelikeTopicBasicData m_basicData`


## Properties

- `String displayId`

- `String topicId`

- `Boolean isOnBattle`

- `Boolean isPinned`

- `RoguelikeTopicBasicData basicData`


## Methods

- `String get_displayId()`

- `String get_topicId()`

- `Boolean get_isOnBattle()`

- `Boolean get_isPinned()`

- `RoguelikeTopicBasicData get_basicData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TopicModel
{
	private String m_displayId; // 0x10
	private String m_topicId; // 0x18
	private Boolean m_isOnBattle; // 0x20
	private Boolean m_isPinned; // 0x21
	private RoguelikeTopicBasicData m_basicData; // 0x28

	public String displayId { get; }
	public String topicId { get; }
	public Boolean isOnBattle { get; }
	public Boolean isPinned { get; }
	public RoguelikeTopicBasicData basicData { get; }

	// RVA: 0x2f11ba4 VA: 0x7595529ba4
	public Void .ctor(String topicId, Boolean isOnBattle, Boolean isPinned) { }
	// RVA: 0x2f11d48 VA: 0x7595529d48
	public String get_displayId() { }
	// RVA: 0x2f11d50 VA: 0x7595529d50
	public String get_topicId() { }
	// RVA: 0x2f11d58 VA: 0x7595529d58
	public Boolean get_isOnBattle() { }
	// RVA: 0x2f11d60 VA: 0x7595529d60
	public Boolean get_isPinned() { }
	// RVA: 0x2f11d68 VA: 0x7595529d68
	public RoguelikeTopicBasicData get_basicData() { }
}
```